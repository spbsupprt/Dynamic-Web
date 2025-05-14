# Dynamic-Web

Что нужно сделать?

Варианты стенда:

- nginx + php-fpm (laravel/wordpress) + python (flask/django) + js(react/angular);

- nginx + java (tomcat/jetty/netty) + go + ruby;

- можно свои комбинации.

Реализации на выбор:

- на хостовой системе через конфиги в /etc;

- деплой через docker-compose.

---

Дано:

![image](https://github.com/user-attachments/assets/4fa46951-3612-42f8-a871-5eb1e30673be)


Применяем плейбук https://github.com/spbsupprt/Dynamic-Web/blob/main/web.yml

![image](https://github.com/user-attachments/assets/c516f620-b034-404c-9147-94299c03fbb0)


Делаем проверки:

### docker ps -a

![image](https://github.com/user-attachments/assets/c6a6d9a8-42b6-4212-854c-e88f02bcab8b)


### Django на http://localhost:8081

![image](https://github.com/user-attachments/assets/4193000a-f59e-40fb-b465-5755e3d31ac9)


### Node.js на http://localhost:8082

![image](https://github.com/user-attachments/assets/b16f13e5-80d8-41d5-b8cf-08f1d3bdbf91)


### WordPress на http://localhost:8083

![image](https://github.com/user-attachments/assets/d79c56ad-a1ad-4526-aec0-26f513cf591e)
