# IoT25-HW05

- - -

## Connection and Data Exchange Process between Server and Client:

1. The server creates a BLE service (SERVICE_UUID) and two characteristics (TEMP_UUID, HUMIDITY_UUID) and transmits data via Notify.
2. The client scans for the server's BLE name (ESP32_DHT) and connects once detected.
3. The client enables the Notify feature for both characteristics and begins receiving data.
4. The server reads temperature and humidity data from the DHT11 sensor every 5 seconds and sends it to the client via Notify.
5. The client displays the received data on the OLED in real time.

- - -

## Demo Video


https://github.com/user-attachments/assets/2479bd13-e1d0-42dc-b78b-9ea814f1b192


- - -

## Screenshot
1. Server
<img width="896" alt="IoT25-HW05-server" src="https://github.com/user-attachments/assets/5a06a878-e169-478d-affd-36596d7213e7" />

2. Client
<img width="917" alt="IoT25-HW05-client" src="https://github.com/user-attachments/assets/867d9078-3507-402a-8c85-5ef3319e0e79" />

3. nRF connection
![IoT25-HW05-1](https://github.com/user-attachments/assets/d84a37d7-6a2d-4bd9-b768-1099413eea8d)
![IoT25-HW05-2](https://github.com/user-attachments/assets/4437e311-cfee-4b6b-8c8b-ef3df6348597)
