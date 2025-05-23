# 啟用管理 {#activation-management}

## 授權管理 {#licenses-management}

### 安裝授權 {#install-license}

您可以從清單中找到所需的授權並進行安裝。Office Tool Plus 內建零售授權的 Grace 產品金鑰，以及大量授權的 KMS 用戶端金鑰 (GVLK)，這些金鑰會在安裝授權後自動安裝。

安裝新授權時，不會覆蓋現有授權，因此不同授權可以共存。

::: tip 提示

安裝授權時，您可以按住 <kbd>Ctrl</kbd> 來選取多個項目。您也可以在篩選框中使用 `|` 來同時篩選多個條件。例如，輸入 `office ltsc 2021|visio 2021` 可篩選出 Office 2021 LTSC 授權與 Visio 2021 授權。

:::

### 安裝其他授權 {#install-other-licenses}

您可以根據需要安裝其他授權。通常，Office 授權儲存在 `C:\Program Files\Microsoft Office\root\Licenses16` 目錄內。此操作不會自動安裝對應的 Office 產品金鑰，因此在安裝授權後，您需要自行安裝對應的 Office 產品金鑰，否則 Office 授權可能無法顯示於 Office 應用程式或授權清單中。

### 解除安裝所有授權 {#uninstall-all-licenses}

此操作將移除所有授權，但不會影響產品金鑰。

## 金鑰管理 {#key-management}

### 安裝金鑰 {#install-key}

輸入有效的 Office 產品金鑰並安裝。如果在安裝金鑰時遇到錯誤代碼 [0xC004F069](/help/activation.md#_0xc004f069)，請先為對應的產品安裝 Office 授權。

### 解除安裝所有未啟用的金鑰 {#uninstall-all-unactivated-keys}

此操作將自動查詢所有授權，並解除安裝所有未啟用的金鑰。使用此功能時請小心。

### 安裝確認識別碼 (CID) {#install-confirmation-id-cid}

您可以透過電話取得安裝識別碼來啟用您的 Office。

## KMS 管理 {#kms-management}

KMS 主機可以是網域名稱或 IP 位址，例如 `kms.example.com` 或 `192.168.123.1`。

KMS 的預設連接埠為 1688，您可以根據需要更改，例如 `kms.example.com:1688` 或 `192.168.123.1:1688`。

## Office 授權清單 {#office-licenses-list}

您可以查詢所有已安裝的 Office 授權資訊，支援 vNext 授權與舊版授權。

### vNext 授權 {#vnext-licenses}

Office Tool Plus 支援查看 vNext 授權的狀態、到期日期及使用者資訊。在刪除授權前，請先登出 Office 應用程式中的 Microsoft 帳戶。

### Office 舊版授權 {#office-legacy-licenses}

Office Tool Plus 支援查詢授權的基本資訊。您可以解除安裝授權的金鑰，或複製確認識別碼 (CID) 以進行電話啟用。
