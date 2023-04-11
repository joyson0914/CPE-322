 *I pledge my Honor that I have abided by the Stevens Honor System- Joy Son*

![image](https://user-images.githubusercontent.com/98338109/231041600-4a0e258b-8866-4a76-a03f-5be395fcf67d.png)


# LAB 9

## Install pyang and PlantUML

$ sudo pip3 install pyang plantuml
![image](https://user-images.githubusercontent.com/98338109/231041976-332b40b7-2597-4462-84c2-7843b496f8cd.png)

$ mkdir ~/demo
$ cp ~/iot/lesson9/intrusiondetection.yang ~/demo
$ cd ~/demo

![image](https://user-images.githubusercontent.com/98338109/231042107-df790691-373a-4941-8ae1-c5efac93983c.png)

$ cat intrusiondetection.yang

![image](https://user-images.githubusercontent.com/98338109/231042208-faa4b0e2-7588-423e-8ad5-dc1e4fa91108.png)
![image](https://user-images.githubusercontent.com/98338109/231042246-ddf03771-a1e0-49a5-aad7-d36c7356f6e1.png)

![image](https://user-images.githubusercontent.com/98338109/231042266-3ee026ea-d2d1-4e7d-a673-0e3b87322d54.png)

$ pyang -f yin -o intrusiondetection.yin intrusiondetection.yang

![image](https://user-images.githubusercontent.com/98338109/231042463-263fede2-0560-4e2b-849e-ea80b2c876bf.png)

$ cat intrusiondetection.yin

![image](https://user-images.githubusercontent.com/98338109/231042553-ebe034e0-ce32-46bd-aae9-313c023a013d.png)
![image](https://user-images.githubusercontent.com/98338109/231042631-6bfcd47c-ab44-438f-b202-4abbb8251997.png)
![image](https://user-images.githubusercontent.com/98338109/231042667-65a229f3-0388-4063-b778-b516ed44eab2.png)

$ pyang -f uml -o intrusiondetection.uml intrusiondetection.yang --uml-no=stereotypes,annotation,typedef

![image](https://user-images.githubusercontent.com/98338109/231042717-f003e1f8-aa40-4a01-84f5-ee890012076b.png)

$ cat intrusiondetection.uml

![image](https://user-images.githubusercontent.com/98338109/231042785-58928b18-0988-49f3-acfb-3c6acf1051cc.png)

$ python3 -m plantuml intrusiondetection.uml

![image](https://user-images.githubusercontent.com/98338109/231042909-05575a5e-ba00-4f3d-9a96-1c8569f5dc1e.png)
