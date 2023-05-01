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

$ sudo pip3 install -U paho-mqtt
![image](https://user-images.githubusercontent.com/98338109/234910187-880ee85c-ca6b-45c6-8c47-57aaf4617f35.png)

$ git clone https://github.com/eclipse/paho.mqtt.python.git

![image](https://user-images.githubusercontent.com/98338109/234910404-40bd1d94-ea55-4deb-9e49-bb8b3fcebcc7.png)

$ cd ~/iot/lesson5

![image](https://user-images.githubusercontent.com/98338109/234910472-208e8e05-f7f0-42f0-9d5c-1e9af78b0abf.png)

![image](https://user-images.githubusercontent.com/98338109/235537467-3d384ae9-c202-4ae7-ada9-b1317c1739e2.png)



$ python3 client.py

![image](https://user-images.githubusercontent.com/98338109/234910955-ce3c9ac1-259a-4358-830e-20d6e22bd9c5.png)

$ python3 subcpu.py  $ python3 pubcpu.py

![image](https://user-images.githubusercontent.com/98338109/235537850-c93eba2d-710a-4f38-ad4f-dac65f63d0ca.png)




