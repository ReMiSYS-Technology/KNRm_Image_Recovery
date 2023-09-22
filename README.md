# KNRm_Image_Recovery

Google Doc 好讀版 https://docs.google.com/document/d/1NXD5mdD-Mpjh1S2giAEFhX76eqKabNhdaeGjBfUA8Wc/edit?usp=sharing

KNRm OS6 Image Recovery
	 for LabVIEW 2019, KNRm OS3, OS4, and OS6 compatible

Preparation 準備工作
下載 KNRm OS6 Image Recovery Tool 及 image https://github.com/ReMiSYS-Technology/KNRm_Image_Recovery.git

Steps 使用步驟
Format KNRm 格式化


打開 NI MAX 選擇左邊 Remote Systems

對目標 KNRm 按右鍵，選擇 Format Disk

有需要的話輸入密碼



勾選 Attempt to restart into safe mode

按下 Format


等待

完成

Image Recovery 倒入還原映像檔


打開 KNRm Image Recovery.lvproj 再點兩下 KNRm_image_recovery.vi  
 


在 Session in 選擇接上的 KNRm，再執行程式



等待約5分鐘



完成後程式會自動停止。成功會顯示綠燈，否則會顯示紅燈及錯誤訊息

