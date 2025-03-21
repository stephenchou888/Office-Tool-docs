# 預設設定模式 {#default-configuration}

當 Office ISO 包含預設設定檔時，啟動 Office Tool Plus 後，將自動載入 `ConfigForISO.xml` 設定檔。然後，Office Tool Plus 會自動跳轉至部署功能頁，詢問使用者是否要進行部署。使用者可以點選 [是] 立即開始安裝，或點選 [否] 來修改設定並重新部署。

在此模式下，Office Tool Plus 會先搜尋 XML 設定檔內指定的安裝檔案。如果找不到，則會自動在 Office Tool Plus 主目錄（Office Tool 資料夾）中搜尋 Office 安裝檔案。

---

前往「**部署**」功能頁，將「**部署模式**」變更為 [**建立 ISO 檔案**]。

請按照以下步驟操作：

- 新增產品。如果您只想安裝語言套件，則可忽略產品設定。
- 新增語言。如果語言未正確設定，可能導致安裝失敗或需要網際網路連線。
- 選取所需的架構。
- 選取適當的更新通道。
- 啟用 **[下載後再部署]**，如果沒有安裝檔案，將無法繼續操作。

其他進階設定可根據需求進行修改。完成上述步驟後，您可以點選 **[開始部署]**。

**Office ISO 建立完成後，`ConfigForISO.xml` 設定檔應自動包含在 ISO 內。**

::: tip 提示

如果您需要建立同時包含 32 位元和 64 位元版本的 Office ISO，請在 **下載 Office 時** 變更架構為 64 位元（或 32 位元），然後再次點選 **[開始部署]**。

掛載 Office ISO 後，您應該可以在 CD-ROM 右鍵選單中看到 [立即安裝] 選項，或正常啟動 Office Tool Plus 來確認安裝。

:::
