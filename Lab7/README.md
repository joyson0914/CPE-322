 *I pledge my Honor that I have abided by the Stevens Honor System- Joy Son*

![image](https://user-images.githubusercontent.com/98338109/235005740-2f2de4c3-e717-4b64-aa6b-4774d6d887a8.png)

# LAB 7

## 1. ThingSpeak
- Sign up and log in ThingSpeak
- Create new channel cpu_loop with field1 cpu_pc and field2 mem_avail_mb

$ pip install -U psutil

![image](https://user-images.githubusercontent.com/98338109/235006691-6bfa9429-4b3e-4327-a456-836733ec664f.png)

$ cd ~/demo
$ cp ~/iot/lesson7/thingspeak_cpu_loop.py .
$ cp ~/iot/lesson7/thingspeak_feed.py .

![image](https://user-images.githubusercontent.com/98338109/235006790-0ec338b0-690f-46e5-a52d-b031206f9b88.png)

$ python3 thingspeak_feed.py

![image](https://user-images.githubusercontent.com/98338109/235008640-b0fb8dc8-77f3-4a92-b793-4a112e8f2819.png)
![image](https://user-images.githubusercontent.com/98338109/235010846-f2ffd1af-b982-4248-a761-23ea7f524fb1.png)


## 2. Google Sheets
- Sign up and log in the Google Cloud Platform Identity and Access Management (IAM)
- Click "Create" and enter the project name, e.g., rpidata
    ≡ > APIs & Services > + Enable APIs & Services > Enable both Drive API and Sheets API
    Credential > Create Credentials > Create service account key > Service account > rpidata > JSON key type > Create > download rpidata-xxxxxxxxxxxx.json

![image](https://user-images.githubusercontent.com/98338109/235013191-a9bd89f7-2261-4302-b461-501ee5ccc508.png)
![image](https://user-images.githubusercontent.com/98338109/235013136-3f131498-d332-47fc-b1d1-ec6c931d7b75.png)
![image](https://user-images.githubusercontent.com/98338109/235539816-5412d729-f279-4ba3-9c8e-e370cfe7051b.png)

$ sudo pip3 install -U gspread oauth2client

![image](https://user-images.githubusercontent.com/98338109/235015583-2ef8d394-cfbd-4efe-9158-b968605b2f98.png)

$ cd demo
$ cp ~/iot/lesson3/system_info.py .
$ cp ~/iot/lesson7/cpu_spreadsheet.py .

![image](https://user-images.githubusercontent.com/98338109/235015663-6b1cf959-3eff-4786-8564-bf1cf153ec0b.png)
![image](https://user-images.githubusercontent.com/98338109/235059404-1825630e-2291-4c85-a636-bf54bd2c7fbb.png)

Edit cpu_spreadsheet.py

![image](https://user-images.githubusercontent.com/98338109/235540942-f69979be-f099-4a1d-a8a5-378edcb2373b.png)

Create google sheet and share

![image](https://user-images.githubusercontent.com/98338109/235541038-d6be6074-b9c1-42e6-8a7e-4fc940be9b82.png)

$ python3 cpu_spreadsheet.py

![image](https://user-images.githubusercontent.com/98338109/235541078-ba52936a-2c75-43f2-998e-c95205d64e13.png)
![image](https://user-images.githubusercontent.com/98338109/235541581-ff037db7-26d7-4143-9667-726ec8a4d9c2.png)


