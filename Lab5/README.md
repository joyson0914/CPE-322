*I pledge my Honor that I have abided by the Stevens Honor System- Joy Son*

![image](https://user-images.githubusercontent.com/98338109/232512103-f7701a51-025b-4485-b59c-02ed19ae2b9e.png)

# LAB 5

## Install Paho-MQTT

$ sudo apt update

![image](https://user-images.githubusercontent.com/98338109/232514224-b5d32733-a85d-40e8-8bf4-b3700edf4286.png)
![image](https://user-images.githubusercontent.com/98338109/232514442-6f812abc-4d40-4c69-b147-d9aa91fcc57e.png)

$ sudo apt install mosquitto mosquitto-clients

![image](https://user-images.githubusercontent.com/98338109/232514065-9fdd0ad6-811f-478c-9eff-655a19cd53aa.png)

$ mosquitto_sub -h localhost -v -t "\$SYS/#"
