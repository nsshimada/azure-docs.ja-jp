---
title: "Azure ロールでのリモート デスクトップの使用 | Microsoft Docs"
description: "Azure ロールでのリモート デスクトップの使用"
services: visual-studio-online
documentationcenter: na
author: TomArcher
manager: douge
editor: 
ms.assetid: f5727ebe-9f57-4d7d-aff1-58761e8de8c1
ms.service: multiple
ms.devlang: multiple
ms.topic: article
ms.tgt_pltfrm: na
ms.workload: na
ms.date: 11/11/2016
ms.author: tarcher
ms.translationtype: Human Translation
ms.sourcegitcommit: f537befafb079256fba0529ee554c034d73f36b0
ms.openlocfilehash: 50c463588356cc4725b038cbf89a49b6ce2bdc3b
ms.contentlocale: ja-jp
ms.lasthandoff: 07/08/2017


---
# <a name="using-remote-desktop-with-azure-roles"></a>Azure ロールでのリモート デスクトップの使用
Azure SDK およびリモート デスクトップ サービスを使用すると、Azure のロールと Azure にホストされている仮想マシンにアクセスできます。 Visual Studio では、Azure クラウド サービス プロジェクトからリモート デスクトップ サービスを構成できます。 リモート デスクトップ サービスを有効にするには、1 つ以上のロールを含む作業用プロジェクトを作成し、Azure に発行する必要があります。

> [!IMPORTANT]
> Azure のロールには、トラブルシューティングまたは開発のためにのみアクセスする必要があります。 各仮想マシンの目的は、Azure アプリケーションで特定のロールを実行することであり、他のクライアント アプリケーションを実行することではありません。 任意の目的に使用できる仮想マシンをホストするのに Azure を使用する場合は、サーバー エクスプローラーから Azure Virtual Machines へのアクセスに関するページを参照してください。
> 
> 

## <a name="to-enable-and-use-remote-desktop-for-an-azure-role"></a>Azure ロールのためのリモート デスクトップを有効にして使用するには
1. ソリューション エクスプローラーでクラウド サービス プロジェクトのショートカット メニューを開き、**[発行]** を選びます。
   
    **Azure アプリケーションの公開** ウィザードが表示されます。
   
    ![Publish command for a Cloud Service project](./media/vs-azure-tools-remote-desktop-roles/IC799161.png)
2. ウィザードの **[Microsoft Azure 発行設定]** ページの下部にある、**[すべてのロールのリモート デスクトップを有効にする]** チェック ボックスをオンにします。 
   
    **[リモート デスクトップ構成]** ダイアログ ボックスが表示されます。
3. **[リモート デスクトップ構成]** ダイアログ ボックスの下にある **[その他のオプション]** をクリックします。 
   
    証明書を作成または選択できるドロップダウン ボックスが表示されます。証明書により、リモート デスクトップを使用して接続するときに資格情報を暗号化できます。
4. ドロップダウン リストで、**[&lt;作成>]** を選択するか、一覧から既存の証明書を選択します。 
   
    既存の証明書を選択した場合、次の手順は省略します。
   
   > [!NOTE]
   > リモート デスクトップ接続に必要な証明書は、他の Azure 操作で使用する証明書とは異なります。 リモート アクセス証明書には、秘密キーが必要です。
   > 
   > 
   
    **[証明書の作成]** ダイアログ ボックスが表示されます。
   
   1. 新しい証明書の表示名を入力し、 **[OK]** ボタンをクリックします。 ドロップダウン ボックスに新しい証明書が表示されます。
   2. **[リモート デスクトップ構成]** ダイアログ ボックスでユーザー名とパスワードを入力します。
      
       既存のアカウントを使用することはできません。 新しいアカウントのユーザー名として Administrator を指定しないでください。
      
      > [!NOTE]
      > パスワードが複雑さの要件を満たしていない場合、パスワードのテキスト ボックスの隣に赤いアイコンが表示されます。 パスワードは大文字と小文字、数字または記号を含める必要があります。
      > 
      > 
   3. アカウントが期限切れになり、リモート デスクトップ接続がブロックされる日付を選択します。
   4. 必要な情報をすべて入力したら、 **[OK]** をクリックします。
      
       .cscfg ファイルと .csdef ファイルに、リモート アクセス サービスを有効にするいくつかの設定が追加されます。
5. クラウド サービスを発行する準備ができたら、**Microsoft Azure 発行設定**ウィザードで **[OK]** をクリックします。
   
    発行する準備ができていない場合は、 **[キャンセル]** をクリックします。 構成設定が保存され、後でクラウド サービスを発行できるようになります。

## <a name="connect-to-an-azure-role-by-using-remote-desktop"></a>リモート デスクトップを使用して Azure ロールに接続する
Azure にクラウド サービスを発行したら、サーバー エクスプローラーを使用して Azure にホストされている仮想マシンにログインします。 

1. サーバー エクスプローラーで、 **[Azure]** ノードを展開し、いずれかのクラウド サービスのノードとそのロールを 1 つ展開して、インスタンスの一覧を表示します。
2. インスタンス ノードでショートカット メニューを開き、 **[リモート デスクトップを使用して接続]**をクリックします。
   
    ![Connecting via remote desktop](./media/vs-azure-tools-remote-desktop-roles/IC799162.png)
3. 以前作成したユーザー名とパスワードを入力します。 これでリモート セッションにログインした状態になります。


