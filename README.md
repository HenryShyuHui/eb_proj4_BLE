# eb_proj4_BLE

1. 創立一個Mbed empty project
2. 下載[https://github.com/ARMmbed/mbed-os-example-ble]，並將 "BLE_GattServer_AddService" 複製到empty project
3. 把其中的main.cpp換成此資料夾的main.cpp
4. 將HeartRateService_modified.h 放到 BLE_GattServer_AddService/mbed-os/connectivity/FEATURE_BLE/include/ble/services/HeartRateService_modified.h
5. 執行STM32，main.cpp將server命名為Henry(可更改)，並且廣播傳送三軸磁力計的訊號
6. 執行ble_scan_connect.py在rpi上，並且執行，可以在rpi中依照stm32的命名進行搜尋的修改，可以較快找到要連接的device的編號，確認無誤之後直接輸入及可


## 執行結果

![image](https://github.com/HenryShyuHui/eb_proj4_BLE/assets/120787184/4ce394b8-7cec-4c68-bb46-30ebfd78e812)
