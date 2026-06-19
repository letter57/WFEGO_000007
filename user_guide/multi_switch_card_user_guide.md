# **📘**   WFEGO RFID 多UID切換卡 & HID 一鍵拍照

[TOC]



## **🔹 1.產品介紹**

> 感謝您使用 WFEGO RFID 多 UID 切換 + BLE HID 一鍵拍照
> 
> 本產品整合 RFID 多卡身份切換與 BLE HID 無線拍照功能，一張卡即可整合多組門禁身份，同時可作為手機/平板藍牙自拍遙控器。   

## **🎯 2.產品特色**  
> - [x] 支援三組 UID 儲存與切換.   
> - [x] 一鍵切換身份，操作簡單直覺.   
> - [x] LED 狀態指示，清楚顯示目前所使用的身份.
> - [x] UID 支援長度: 4bytes、7bytes、10bytes.  
> - [x]  透過具備`NFC功能的手機`及 `NFC Tools` App 即可進行 UID 拷貝.
> - [x] BLE HID 無線一鍵拍照
> - [x] 可攜式設計

<div style="page-break-after: always;"></div>

## **💡 3.技術規格**  

|   **項目**    |            規格            |
| :-----------: | :------------------------: |
| RFID 工作頻率 |         13.56 MHz          |
| RFID 通訊協議 |      ISO/IEC 14443-3       |
| UID 支援長度  | 4 bytes, 7 bytes, 10 bytes |
|   LED 顯示    | 紅燈, 綠燈, 黃燈(紅 + 綠)  |
| BLE 工作頻率  |          2.4 GHz           |
| BLE 通訊協議  |            HID             |
|   控制介面    |          單一按鍵          |
|     電源      |           CR2032           |

## **🔧 4.所需工具**  

> * 手機 (需支援NFC功能).   
> * NFC Tools App
>   * [Android](https://play.google.com/store/apps/details?id=com.wakdev.wdnfc&hl=zh_TW)
>   * [IOS](https://apps.apple.com/tw/app/nfc-tools/id1252962749)
> * 欲複製的 RFID 卡
> * 本產品 WFEGO RFID 多UID切換卡.

## **🔹 5.外觀與功能介紹**  

<img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524200929987.svg" alt="1" align="left"  style="zoom: 80%;"/>


|  名稱  |        功能        |
| :----: | :----------------: |
|  按鍵  | 切換模式與功能操作 |
|  LED   |   顯示模式與狀態   |
| 感應區 |   感應門禁/手機    |
|  電池  |        供電        |

## **🔹 6.快速開始**  
###  **6-1 RFID使用**
1.按壓按鍵切換 UID.   
2.LED 顏色對應不同身份.   
3.感應門禁即可使用.   

### **6-2 一鍵拍照**   
1.長按按鍵 4 秒切換拍照模式.   
2.手機完成配對.   
3.按鍵拍照.   

## **🔹 7.RFID 多 UID 功能說明**    
###  **7-1 一般模式**   
說明:  
> 一般模式用於日常門禁使用，可切換不同UID身份。

操作流程:   

|   操作   |     功能     |
| :------: | :----------: |
| 短按一次 |   切換 UID   |
| LED 變色 | 代表身份切換 |

例如:   

|      LED      |  UID  |
| :-----------: | :---: |
|     紅燈      | UID 1 |
|     綠燈      | UID 2 |
| 黃(紅 + 綠)燈 | UID3  |

<div style="page-break-after: always;"></div>

### **7-2 Android 拷貝 UID 操作步驟**

1. 打開`NFC Tools` App.

2. 點選`READ` -> 將欲複製的卡片靠近手機 NFC 感應區.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524022401127.jpg" alt="1" align="left"  style="zoom: 33%;" />
   
<div style="page-break-after: always;"></div>


3. 讀取到卡片資訊後，點選`Serial number`, 如下圖 1 所指處. 點選`Copy to clipboard`, 如下圖 2 所指處.   

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524023714353.jpg" alt="2" align="left" style="zoom: 33%;" />

<div style="page-break-after: always;"></div>

4. 點選 `WRITE`, 如下圖 1 所指處. 點選 `Add a record`, 如下圖 2 所指處. 

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524031106061.jpg" alt="3" align="left" style="zoom: 33%;"/>

<div style="page-break-after: always;"></div>

5. 點選 `Text`, 如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524032110827.jpg" alt="4" align="left" style="zoom: 33%;"/>

<div style="page-break-after: always;"></div>

6. 長按 `Hello`, 如下圖 1 所指處. 點選`貼上`, 如下圖 2 所指處. 點選`OK`, 如下圖 3 所指處.

   <img 
   src="https://raw.githubusercontent.com/letter57/imgs/main/5.jpg" alt="5" align="left" style="zoom:33%;"/>

<div style="page-break-after: always;"></div>

7. 如果只有一組的話，建議還是建立三組 `Add a record`中的 `Text`.方便後續的修改.重複`步驟 4 ~ 步驟 6`.

8. 如果有三組的話，則重複`步驟 2 ~ 步驟 6`.

9. 三組 UID 建立完成，如下圖所示.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524033144190.jpg"  alt="6" align="left" style="zoom:33%;"/>

   <div style="page-break-after: always;"></div>

10. 點選 `Write / 54 Bytes`, 如下圖 1 所指處.   

    > `54 Bytes`會依據不同的卡片( UID 長度不同)得到不同的數值.

    <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524083215609.jpg" alt="7" align="left" style="zoom:33%;"/>

    <div style="page-break-after: always;"></div>

11. 將手機靠近本產品，寫入 UID.   

    <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524101834392.jpg" alt="8" align="left" style="zoom:33%;"/>

    <div style="page-break-after: always;"></div>

12. 確認是否有寫入成功, 如下圖所示.   

    <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260524102006739.jpg" alt="9" align="left" style="zoom:33%;"/>
    
    <div style="page-break-after: always;"></div>

### **7-3 IOS 拷貝 UID 操作步驟**

1. 打開 `NFC Tools` App.

2. 點選 `READ` ，如下圖1所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260528053629175.png" alt="1" align="left" style="zoom: 67%;" />

    <div style="page-break-after: always;"></div>

3. 將欲複製的卡片靠近手機 NFC 感應區.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260528053758192.PNG" alt="2" align="left" style="zoom: 25%;" />
   
   <div style="page-break-after: always;"></div>

4. 讀取到卡片資訊後，點選 `Serial number`, 如下圖 1 所指處. 點選 `Copy to clipboard`, 如下圖 2 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260528054356607.png" alt="2" align="left" style="zoom: 70%;" />
   
   <div style="page-break-after: always;"></div>

5. 點選 `WRITE`, 如下圖 1 所指處. 

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260529202241249.png" alt="3" align="left" style="zoom:70%;" />
   
   <div style="page-break-after: always;"></div>

6. 點選 `Add a record`, 如下圖 1 所指處. 

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260529203318947.png" alt="4" align="left" style="zoom:70%;" />
   
   <div style="page-break-after: always;"></div>

7. 點選 `Text`, 如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260529203742360.png"  alt="5" align="left" style="zoom:70%;" />
   
   <div style="page-break-after: always;"></div>

8. 長按 `Hello`, 如下圖 1 所指處. 點選 `Paste`, 如下圖 2 所指處. 點選`勾勾`, 如下圖 3 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260529204753289.png"  alt="6" align="left" style="zoom: 67%;" />
   
   <div style="page-break-after: always;"></div>

9. 如果只有一組的話，建議還是建立三組 `Add a record`中的 `Text`.方便後續的修改.重複`步驟 6 ~ 步驟 8`.

10. 如果有三組的話，則重複`步驟 2 ~ 步驟 8.

11. 三組 UID 建立完成，如下圖所示.

    <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260531140607733.png" alt="7" align="left" style="zoom:67%;" />
    
    <div style="page-break-after: always;"></div>

12. 點選 `Write / 81 Bytes`, 如下圖 1 所指處.   

    > `81 Bytes`會依據不同的卡片(UID 長度不同)得到不同的數值.

    <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260531141815434.png" alt="8" align="left" style="zoom:67%;"/>
    
    <div style="page-break-after: always;"></div>

13. 將手機靠近本產品，寫入 UID. 

    <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260531142359631.png" alt="9" align="left" style="zoom:67%; "/>
    
    <div style="page-break-after: always;"></div>

## **🔹 8.HID 一鍵拍照**
### **8-1 Android 配對模式**

**進入配對模式**

1. 長按 4 秒

2. 橘色 LED 閃爍 3 次(HID)

3. 點選手機的**設定**，如下圖 1 所指處. 點選**藍牙**，如下圖 2 所指處

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260618210024756.png" alt="1" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

4. 在**可用裝置**，如下圖 1 所指處.找到 `WFEGO_RFID_HID`, 如下圖 2 所指處.

   > 點選**WFEGO_RFID_HID**

     

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260618211233650.png" alt="2" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

5. 點選**配對**，如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260619165152061.png" alt="3" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

6. 點選**多 UID 切換卡**的按鍵，如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260618212349158.png" alt="4" align="left" style="zoom: 50%;"/>
   
   <div style="page-break-after: always;"></div>

7. **配對成功**，顯示**已連線**如下圖 1、2 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260618212953242.png" alt="4" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>


### **8-2  IOS 配對模式**

   **進入配對模式**

1. 長按 4 秒

2. 橘色 LED 閃爍 3 次(HID)

3. 點選手機的**設定**，如下圖 1 所指處. 點選**藍牙**，如下圖 2 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260619163534631.png" alt="5" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

4. 在**其他裝置**，如下圖 1 所指處.找到 `WFEGO_RFID_HID`, 如下圖 2 所指處.

   > 點選**WFEGO_RFID_HID**

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260619164137299.png" alt="6" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

5. 點選**配對**，如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260619164524086.png" alt="7" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

6. 點選**多 UID 切換卡**的按鍵，如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260618212349158.png" alt="4" align="left" style="zoom: 50%;"/>
   
   <div style="page-break-after: always;"></div>

7. **配對成功**，顯示**已連線**，如下圖 1 所指處.

   <img src="https://raw.githubusercontent.com/letter57/imgs/main/20260619164825500.png" alt="8" align="left" style="zoom:67%;" />
   
   <div style="page-break-after: always;"></div>

### **8-3  拍照使用方式**

簡單明確：

1. 開啟手機相機.
2. 確認藍牙已連線.
3. 按壓`多 UID 切換卡`上的`按鍵`拍照.

### **8-4  清除綁定**

**清除配對紀錄**

1. 長按`多 UID 切換卡`上的按鍵 8 秒(看到紅色 LED 閃爍再放開).
2. 紅色 LED 閃爍 2 次.
3. 手機要點選`忘記此裝置設定` / `解除配對`.

## **🔹 9. LED 狀態總表**

|   模式    |    LED 顯示    |     狀態     |
| :-------: | :------------: | :----------: |
| RFID 模式 |      紅燈      |    UID 1     |
| RFID 模式 |      綠燈      |    UID 2     |
| RFID 模式 |    橘(黃)燈    |    UID 3     |
| RFID 模式 | 紅燈 閃爍 5 次 |  電池低電壓  |
| RFID 模式 | 綠燈 閃爍 5 次 |  電池低電壓  |
| RFID 模式 | 橘燈 閃爍 5 次 |  電池低電壓  |
| HID 模式  |      綠燈      |     拍照     |
|           |                |              |
|           | 橘燈 閃爍 3 次 | HID 一鍵拍照 |
|           | 橘燈 閃爍 4 次 |  RFID 模式   |
|           | 紅燈 閃爍 2 次 |   清除綁定   |

<div style="page-break-after: always;"></div>

## **🔹 10. 按鍵操作總表**

|   模式    |   操作    |         功能         |
| :-------: | :-------: | :------------------: |
| RFID 模式 |   短按    |       切換 UID       |
|           | 長按 4 秒 | 切換模式(RFID / HID) |
|           | 長按 8 秒 |       清除綁定       |
| HID 模式  |   短按    |         拍照         |

## **🔹 11. 注意事項**

- RFID感應距離依讀卡機而異.
- 避免高溫與浸水.
- 長時間不使用請關閉/移除電池

## **🔹 12. 常見問題 (FAQ)**

Q：手機找不到 WFEGO_RFID_HID？

A：確認`複製卡`處於 `HID 模式`.

A：手機藍牙重啟.

A：複製卡 清除綁定.