*I pledge my Honor that I have abided by the Stevens Honor System- Joy Son*

![image](https://user-images.githubusercontent.com/98338109/231038603-704b678e-9498-4b3e-9287-1f197c6b1019.png)

# LAB 4

## 1. Install Django and Django REST framework on Raspberry Pi

$ pip3 -V

![image](https://user-images.githubusercontent.com/98338109/231039105-1d11dde0-4bdf-46e6-9742-a46e230879a5.png)

$ pip3 list

![image](https://user-images.githubusercontent.com/98338109/231039189-b64a28bd-fb58-4c7e-852a-b02d8bdccced.png)
![image](https://user-images.githubusercontent.com/98338109/231039244-8b1322da-705e-4151-9550-bcb6b65dca70.png)

$ sudo pip3 install -U setuptools

![image](https://user-images.githubusercontent.com/98338109/231039485-b4b83170-ebbd-4960-9811-a954bf0eac25.png)

$ sudo pip3 install -U django

![image](https://user-images.githubusercontent.com/98338109/231039604-686dce5d-ba31-49fa-8722-be241f6c9c62.png)

$ sudo pip3 install -U djangorestframework

![image](https://user-images.githubusercontent.com/98338109/231039670-14d5a672-4e94-4221-b447-573a1d2dfab5.png)

$ sudo pip3 install -U django-filter

![image](https://user-images.githubusercontent.com/98338109/231039719-0d25a755-a833-42d0-b0ae-7413f64e87d7.png)

$ sudo pip3 install -U markdown

![image](https://user-images.githubusercontent.com/98338109/231039764-cf1c47c7-c27b-4d8f-a862-06951ae332a9.png)

$ sudo pip3 install -U requests

![image](https://user-images.githubusercontent.com/98338109/231039799-8b313159-df75-4525-b8a8-9cc416615fb9.png)


## 2. Django project stevens

- Start project
 
![image](https://user-images.githubusercontent.com/98338109/231040208-2c8fa9ac-e67c-476c-b07b-def92298afd5.png)

- Start app

![image](https://user-images.githubusercontent.com/98338109/231040419-31f914ec-0135-430e-a13a-63fa39981db7.png)

- Edit settings.py in ~/stevens/stevens

![image](https://user-images.githubusercontent.com/98338109/235728106-b18ba6ed-000a-4aba-a529-7c502024606c.png)

- Copy admin.py, models.py, and views.py to ~/stevens/myapp

![image](https://user-images.githubusercontent.com/98338109/235728279-27b7f5f9-5c0f-4419-8318-1b58caf706fe.png)

- Copy index.html

![image](https://user-images.githubusercontent.com/98338109/235728661-395b7ec4-6d71-4e54-a439-e77cda157309.png)

- Copy static files

![image](https://user-images.githubusercontent.com/98338109/235729729-c58c0f9d-1094-4f6f-824c-31a101d7fbd0.png)

- Migrate 

$ python3 manage.py makemigrations myapp

![image](https://user-images.githubusercontent.com/98338109/235730302-5522d567-058e-4759-b803-ac406b6031cb.png)

$ python3 manage.py migrate

![image](https://user-images.githubusercontent.com/98338109/235730435-bf62c2e6-0566-4ef4-8266-d08d788a59fd.png)

$ python3 manage.py createsuperuser

![image](https://user-images.githubusercontent.com/98338109/235730379-389db1f4-7ee6-4f54-b9e8-13b057f7074d.png)
 
- Run Django Server
$ python3 manage.py runserver

![image](https://user-images.githubusercontent.com/98338109/235730986-a8cdde17-b633-4872-8dde-5d21b9fe3464.png)

![image](https://user-images.githubusercontent.com/98338109/235730774-9b8776f2-d5f2-43db-9893-86dfab274c43.png)

![image](https://user-images.githubusercontent.com/98338109/235730911-8ba57ad4-c455-4ed7-80fb-de89d0657775.png)

## 3. Django project mycpu

- Start project

![image](https://user-images.githubusercontent.com/98338109/235816230-36893ef1-b4d9-4dd2-bfc9-84fb30d06f68.png)

- Edit settings.py in ~/mycpu/mycpu

![image](https://user-images.githubusercontent.com/98338109/235816473-9d26fef6-797a-452f-93f9-64ebc36b0733.png)
![image](https://user-images.githubusercontent.com/98338109/235818120-b141c91a-b7c2-4fb0-b92b-70ae0edc869c.png)

- Copy urls.py to ~/mycpu/mycpu

![image](https://user-images.githubusercontent.com/98338109/235816557-2504454e-393a-46c0-afdc-b2813df02dbc.png)

- Copy admin.py, models.py, and views.py to ~/stevens/myapp

![image](https://user-images.githubusercontent.com/98338109/235816606-8a03bf85-ac6b-430d-aa8c-2076b78def92.png)

- Copy index.html

![image](https://user-images.githubusercontent.com/98338109/235816862-7d715322-83a7-4854-858a-92954fbdfe0e.png)

- Copy static files

![image](https://user-images.githubusercontent.com/98338109/235817026-08d75b04-e957-4bdc-8c5a-5ca334e0f234.png)

- Copy controller.py to ~/mycpu

![image](https://user-images.githubusercontent.com/98338109/235817124-c2fcadf2-eed8-4986-ad27-43674df528e3.png)

- Migrate

![image](https://user-images.githubusercontent.com/98338109/235818239-5ddea5a7-d342-4575-9a82-86a13951afcb.png)
![image](https://user-images.githubusercontent.com/98338109/235818364-6cc4a8a7-c722-41e7-861e-5e1729c16f46.png)

- Run Django server

![image](https://user-images.githubusercontent.com/98338109/235818878-b42621c0-3466-4e7f-aa01-84b8885e5c92.png)


![image](https://user-images.githubusercontent.com/98338109/235818499-48dd74f4-f5ab-4f93-8005-0e695579048b.png)

![image](https://user-images.githubusercontent.com/98338109/235818648-5a122c6e-d696-4a30-9c0c-8e017d647d1d.png)
![image](https://user-images.githubusercontent.com/98338109/235818658-6cf9f734-2cb4-47f6-a7c2-dd90f879b9fe.png)
![image](https://user-images.githubusercontent.com/98338109/235818668-52a321b6-8cce-43eb-bf21-b481566ae6fb.png)


![image](https://user-images.githubusercontent.com/98338109/235818813-85090461-bcc8-48fd-9822-291032e0f3a6.png)





