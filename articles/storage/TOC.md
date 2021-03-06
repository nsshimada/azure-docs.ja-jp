# 概要

## [はじめに](storage-introduction.md)
## [BLOB、ファイル、またはデータ ディスクを選択する](storage-decide-blobs-files-disks.md)

# 作業の開始

## [ストレージ アカウントの作成](storage-create-storage-account.md)

## Blob Storage
### [.NET](storage-dotnet-how-to-use-blobs.md)
### [Java](storage-java-how-to-use-blob-storage.md)
### [Node.JS](storage-nodejs-how-to-use-blob-storage.md)
### [C++](storage-c-plus-plus-how-to-use-blobs.md)
### [PHP](storage-php-how-to-use-blobs.md)
### [Python](storage-python-how-to-use-blob-storage.md)
### [Ruby](storage-ruby-how-to-use-blob-storage.md)
### [iOS](storage-ios-how-to-use-blob-storage.md)
### [Xamarin](storage-xamarin-blob-storage.md)

## Queue Storage
### [.NET](storage-dotnet-how-to-use-queues.md)
### [Java](storage-java-how-to-use-queue-storage.md)
### [Node.JS](storage-nodejs-how-to-use-queues.md)
### [C++](storage-c-plus-plus-how-to-use-queues.md)
### [PHP](storage-php-how-to-use-queues.md)
### [Python](storage-python-how-to-use-queue-storage.md)
### [Ruby](storage-ruby-how-to-use-queue-storage.md)

## Table Storage
### [.NET](storage-dotnet-how-to-use-tables.md)
### [F#](/dotnet/articles/fsharp/using-fsharp-on-azure/table-storage)
### [Java](storage-java-how-to-use-table-storage.md)
### [Node.JS](storage-nodejs-how-to-use-table-storage.md)
### [C++](storage-c-plus-plus-how-to-use-tables.md)
### [PHP](storage-php-how-to-use-table-storage.md)
### [Python](storage-python-how-to-use-table-storage.md)
### [Ruby](storage-ruby-how-to-use-table-storage.md)

## [File Storage](storage-files-introduction.md)
### [ポータル](storage-file-how-to-use-files-portal.md)
### [.NET](storage-dotnet-how-to-use-files.md)
### [PowerShell](storage-file-how-to-use-files-powershell.md)
### [Windows](storage-file-how-to-use-files-windows.md)
### [Linux](storage-how-to-use-files-linux.md)
### [Mac](storage-file-how-to-use-files-mac.md)  
### [Java](storage-java-how-to-use-file-storage.md)
### [C++](storage-c-plus-plus-how-to-use-files.md)
### [Python](storage-python-how-to-use-file-storage.md)
### [ファイル共有の作成](storage-file-how-to-create-file-share.md)
### [FAQ](storage-files-faq.md)
## ディスク ストレージ 
### [Resource Manager と PowerShell を使用して VM を作成する](../virtual-machines/virtual-machines-windows-ps-create.md)
### [Azure CLI 2.0 を使用して Linux VM を作成する](../virtual-machines/linux/quick-create-cli.md)
### [PowerShell を使用して Windows VM に管理ディスクを接続する](../virtual-machines/windows/attach-disk-ps.md)
### [Linux VM に管理ディスクを追加する](../virtual-machines/linux/add-disk.md)
### [Windows のスナップショットを使用して管理ディスクとして格納された VHD のコピーを作成する](../virtual-machines/windows/snapshot-copy-managed-disk.md)
### [Linux のスナップショットを使用して管理ディスクとして格納された VHD のコピーを作成する](../virtual-machines/linux/snapshot-copy-managed-disk.md)
### [Resource Manager テンプレートでの Managed Disks の使用](storage-using-managed-disks-template-deployments.md)

# 方法
## [ストレージ アカウントの作成](storage-create-storage-account.md)
## BLOB の使用
### [サービスの概要](https://msdn.microsoft.com/library/dd179376.aspx)
### [Azure Search を使用した Blob Storage の検索](../search/search-blob-storage-integration.md)
### [ホット層およびクール層](storage-blob-storage-tiers.md)
### [カスタム ドメイン](storage-custom-domain-name.md)
### [Azure CDN を使用して HTTPS 経由でカスタム ドメイン付きの BLOB にアクセスする](storage-https-custom-domain-cdn.md) 
### [BLOB への匿名アクセス](storage-manage-access-to-resources.md)
### [サンプル](https://azure.microsoft.com/documentation/samples/?service=storage&term=blob)
## キューの使用
### [概念](https://msdn.microsoft.com/library/dd179353.aspx)
### [サンプル](https://azure.microsoft.com/documentation/samples/?service=storage&term=queue)
## テーブルの使用
### [概要](https://msdn.microsoft.com/library/dd179463.aspx)
### [テーブル設計ガイド](storage-table-design-guide.md)
### [サンプル](https://azure.microsoft.com/documentation/samples/?service=storage&term=table)
## ファイルの使用
### [概要](/rest/api/storageservices/File-Service-Concepts)
### [Azure Files のトラブルシューティング - Windows](storage-troubleshoot-windows-file-connection-problems.md)
### [Azure Files のトラブルシューティング - Linux](storage-troubleshoot-linux-file-connection-problems.md)
### [サンプル](https://azure.microsoft.com/documentation/samples/?service=storage&term=file)
## ディスクの使用
### [Windows VM 用のディスクと VHD](storage-about-disks-and-vhds-windows.md)
### [Linux VM 用のディスクと VHD](storage-about-disks-and-vhds-linux.md)
### [Azure Managed Disks の概要](storage-managed-disks-overview.md)
### [Azure VM を Azure Managed Disks に移行する](../virtual-machines/windows/migrate-to-managed-disks.md)
### [AWS やその他のプラットフォームから Managed Disks に移行する](../virtual-machines/windows/on-prem-to-azure.md)
### [Azure IaaS VM ディスクについてよく寄せられる質問](storage-faq-for-disks.md)
### Premium Storage
#### [VM ディスク向けの高パフォーマンス Premium Storage](storage-premium-storage.md)
#### [Azure Site Recovery を使用した Premium Storage への移行](storage-migrate-to-premium-storage-using-azure-site-recovery.md)
#### [高パフォーマンス用の設計](storage-premium-storage-performance.md)
### Standard Storage
#### [コスト効率に優れた Standard Storage および非管理対象と管理対象の VM ディスク](storage-standard-storage.md)
### 非管理対象ディスクの使用
#### [Premium Storage への移行](storage-migration-to-premium-storage.md)
#### [増分スナップショットを使用した非管理対象 VM ディスクのバックアップ](storage-incremental-snapshots.md)
## 計画と設計
### [レプリケーション](storage-redundancy.md)
### [スケーラビリティとパフォーマンスのターゲット](storage-scalability-targets.md)
### [パフォーマンスと拡張性のチェックリスト](storage-performance-checklist.md)
### [同時実行](storage-concurrency.md)
## 開発
### サンプル
#### [.NET](storage-samples-dotnet.md)
#### [Java](storage-samples-java.md)
### [RA-GRS を使用して HA アプリを設計する](storage-designing-ha-apps-with-ragrs.md)
### [接続文字列を構成する](storage-configure-connection-string.md)
### [ストレージ エミュレーターを使用する](storage-use-emulator.md)
### [プロパティおよびメタデータを設定および取得する](storage-properties-metadata.md)
## 管理
### [PowerShell](storage-powershell-guide-full.md)
### [Azure CLI 2.0](storage-azure-cli.md)
### [Azure CLI 1.0](storage-azure-cli-nodejs.md)
### [Azure Automation](automation-manage-storage.md)
## セキュリティ保護
### [セキュリティ ガイド](storage-security-guide.md)
### [保存データの暗号化](storage-service-encryption.md)
### [カスタマー キーでの保存時の暗号化](storage-service-encryption-customer-managed-keys.md)
### [共有キー認証](/rest/api/storageservices/Authentication-for-the-Azure-Storage-Services)
### [Shared Access Signatures (SAS)](storage-dotnet-shared-access-signature-part-1.md)
### [チュートリアル: Azure Key Vault を使用して BLOB を暗号化および復号化する](storage-encrypt-decrypt-blobs-key-vault.md)
### [安全な転送が必要](storage-require-secure-transfer.md)
### クライアント側暗号化
#### [.NET](storage-client-side-encryption.md)
#### [Java](storage-client-side-encryption-java.md)
#### [Python](storage-client-side-encryption-python.md)
## 監視とトラブルシューティング
### [障害復旧ガイダンス](storage-disaster-recovery-guidance.md)
### [IAAS ディスクのバックアップと DR](storage-backup-and-disaster-recovery-for-azure-iaas-disks.md)
### [ストレージ エクスプローラーのトラブルシューティング](storage-explorer-troubleshooting.md)
### メトリックとログ
#### [Storage Analytics](storage-analytics.md)
#### [メトリックスの有効化と表示](storage-enable-and-view-metrics.md)
#### [監視、診断、トラブルシューティング](storage-monitoring-diagnosing-troubleshooting.md)
#### [トラブルシューティングのチュートリアル](storage-e2e-troubleshooting.md)
### [ディスク削除エラーのトラブルシューティング](storage-resource-manager-cannot-delete-storage-account-container-vhd.md)
### [File Storage のトラブルシューティング](storage-troubleshoot-file-connection-problems.md)
## データの転送
### [Storage との間でデータを移動する](storage-moving-data.md)
### [Windows での AzCopy](storage-use-azcopy.md)
### [Linux での AzCopy](storage-use-azcopy-linux.md)
### [Import/Export サービスを使用する](storage-import-export-service.md)
### [Import/Export ツールを使用する](storage-import-export-tool-how-to.md)
#### [Import/Export ツールを設定する](storage-import-export-tool-setup.md)
#### [インポート ジョブ用のハード ドライブを準備する](storage-import-export-tool-preparing-hard-drives-import.md)
##### [インポート処理中にプロパティとメタデータを設定する](storage-import-export-tool-setting-properties-metadata-import.md)
##### [インポート ジョブ用のハード ドライブを準備するためのサンプル ワークフロー](storage-import-export-tool-sample-preparing-hard-drives-import-job-workflow.md)
##### [インポート ジョブで頻繁に使用するコマンドのクイック リファレンス](storage-import-export-tool-quick-reference.md)
#### [エクスポート ジョブのドライブ使用率のプレビュー](storage-import-export-tool-previewing-drive-usage-export-v1.md)
#### [コピー ログ ファイルによるジョブの状態の確認](storage-import-export-tool-reviewing-job-status-v1.md)
#### [インポート ジョブの修復](storage-import-export-tool-repairing-an-import-job-v1.md)
#### [エクスポート ジョブの修復](storage-import-export-tool-repairing-an-export-job-v1.md)
#### [Import/Export ツールのトラブルシューティング](storage-import-export-tool-troubleshooting-v1.md)
#### [Import/Export サービスのマニフェスト ファイルの形式](storage-import-export-file-format-manifest.md)
#### [Import/Export サービスのメタデータとプロパティ ファイルの形式](storage-import-export-file-format-metadata-and-properties.md)
#### [Import/Export サービスのログ ファイルの形式](storage-import-export-file-format-log.md)
### [Import/Export ツール (v1) を使用する](storage-import-export-tool-how-to-v1.md)
#### [Import/Export ツールを設定する](storage-import-export-tool-setup-v1.md)
#### [インポート ジョブ用のハード ドライブを準備する](storage-import-export-tool-preparing-hard-drives-import-v1.md)
##### [インポート処理中にプロパティとメタデータを設定する](storage-import-export-tool-setting-properties-metadata-import-v1.md)
##### [インポート ジョブ用のハード ドライブを準備するためのサンプル ワークフロー](storage-import-export-tool-sample-preparing-hard-drives-import-job-workflow-v1.md)
##### [インポート ジョブで頻繁に使用するコマンドのクイック リファレンス](storage-import-export-tool-quick-reference-v1.md)
#### [エクスポート ジョブのドライブ使用率のプレビュー](storage-import-export-tool-previewing-drive-usage-export-v1.md)
#### [コピー ログ ファイルによるジョブの状態の確認](storage-import-export-tool-reviewing-job-status-v1.md)
#### [インポート ジョブの修復](storage-import-export-tool-repairing-an-import-job-v1.md)
#### [エクスポート ジョブの修復](storage-import-export-tool-repairing-an-export-job-v1.md)
#### [Import/Export ツールのトラブルシューティング](storage-import-export-tool-troubleshooting-v1.md)
#### [Import/Export サービスのマニフェスト ファイルの形式](storage-import-export-file-format-manifest.md)
#### [Import/Export サービスのメタデータとプロパティ ファイルの形式](storage-import-export-file-format-metadata-and-properties.md)
#### [Import/Export サービスのログ ファイルの形式](storage-import-export-file-format-log.md)
### [Azure Import/Export サービス REST API の使用](storage-import-export-using-the-rest-api.md)
#### [インポート ジョブの作成](storage-import-export-creating-an-import-job.md)
#### [エクスポート ジョブの作成](storage-import-export-creating-an-export-job.md)
#### [ジョブの状態情報の取得](storage-import-export-retrieving-state-info-for-a-job.md)
#### [ジョブの列挙](storage-import-export-enumerating-jobs.md)
#### [ジョブのキャンセルと削除](storage-import-export-cancelling-and-deleting-jobs.md)
#### [ドライブ マニフェストのバックアップ](storage-import-export-backing-up-drive-manifests.md)
#### [Import/Export ジョブの診断とエラーからの回復](storage-import-export-diagnostics-and-error-recovery.md)
# リファレンス
## [コード サンプル](https://azure.microsoft.com/en-us/resources/samples/?service=storage)
## [PowerShell](/powershell/module/azure.storage)
## [Azure CLI](/cli/azure/storage)
## .NET
### [リソース マネージャー](/dotnet/api/microsoft.azure.management.storage)
### [データの移動](/dotnet/api/microsoft.windowsazure.storage.datamovement)
### [BLOB、キュー、テーブル、ファイル](https://msdn.microsoft.com/library/azure/mt347887.aspx)
## [Java](http://azure.github.io/azure-storage-java/)
## [Node.JS](http://azure.github.io/azure-storage-node)
## [Ruby](http://azure.github.io/azure-storage-ruby)
## [PHP](http://azure.github.io/azure-storage-php/)
## [Python](https://azure-storage.readthedocs.io/en/latest/index.html)
## [C++](http://azure.github.io/azure-storage-cpp)
## [iOS](http://azure.github.io/azure-storage-ios/)
## [Android](http://azure.github.io/azure-storage-android)
## REST ()
### [BLOB、キュー、テーブル、ファイル](/rest/api/storageservices)
### [リソース プロバイダー](/rest/api/storagerp)
### [Import/Export](/rest/api/storageimportexport)

# 関連項目
## クラシック ポータル
### [ストレージ アカウントの作成](storage-create-storage-account-classic-portal.md)
### [メトリックスの有効化と表示](storage-enable-and-view-metrics-classic-portal.md)
### [監視、診断、トラブルシューティング](storage-monitoring-diagnosing-troubleshooting-classic-portal.md)
### [トラブルシューティングのチュートリアル](storage-e2e-troubleshooting-classic-portal.md)

# リソース
## [Azure のロードマップ](https://azure.microsoft.com/roadmap/?category=storage)
## [Azure Storage クライアント ツール](storage-explorers.md)
## [フォーラム](https://social.msdn.microsoft.com/forums/azure/home?forum=windowsazuredata)
## [料金](https://azure.microsoft.com/pricing/details/storage/blobs/)
## [料金計算ツール](https://azure.microsoft.com/pricing/calculator/)
## [サービスの更新情報](https://azure.microsoft.com/updates/?product=storage)
## [Stack Overflow](http://stackoverflow.com/questions/tagged/windows-azure-storage)
## [ビデオ](https://azure.microsoft.com/documentation/videos/index/?services=storage)

## Azure ストレージ エクスプローラー
### [ストレージ エクスプローラー (プレビュー)](../vs-azure-tools-storage-manage-with-storage-explorer.md)
### [ストレージ エクスプローラーを使用した BLOB の管理 (プレビュー)](../vs-azure-tools-storage-explorer-blobs.md)
### [Azure File Storage でのストレージ エクスプローラー (プレビュー) の使用](../vs-azure-tools-storage-explorer-files.md)
### [ストレージ エクスプローラー (プレビュー) のリリース ノート](../vs-azure-tools-storage-explorer-relnotes.md)

## NuGet パッケージ
### [.NET 用 Azure Storage クライアント ライブラリ](https://www.nuget.org/packages/WindowsAzure.Storage/)
### [Azure Storage データ移動ライブラリ](https://www.nuget.org/packages/Microsoft.Azure.Storage.DataMovement/)
### [Azure Configuration Manager](https://www.nuget.org/packages/Microsoft.WindowsAzure.ConfigurationManager/)

## ソース コード
### .NET
#### [Blob、Queue、Table、File](https://github.com/Azure/azure-storage-net)
#### [データの移動](https://github.com/Azure/azure-storage-net-data-movement)
#### [リソース プロバイダー](https://github.com/Azure/azure-sdk-for-net)
### [Node.JS](http://azure.github.io/azure-storage-node/)
### [Java](https://github.com/Azure/azure-storage-java)
### [C++](https://github.com/Azure/azure-storage-cpp)
### [PHP](https://github.com/Azure/azure-storage-php)
### [Python](https://github.com/Azure/azure-storage-python)
### [Ruby](https://github.com/Azure/azure-storage-ruby)
### [iOS](https://github.com/Azure/azure-storage-ios)
