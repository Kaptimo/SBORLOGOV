# SBORLOGOV

![image](https://github.com/user-attachments/assets/a49add6f-19f1-45cc-9d1b-008fae5b6c47)
Создали сетевую связанность между машинами

![image](https://github.com/user-attachments/assets/e119e78d-5168-41ca-98ed-d7bb4d6583ac)
установили rsyslog

![image](https://github.com/user-attachments/assets/88c3359c-ec7b-4e30-8c0d-c62d6ee2c458)
открыли порт для получения логов (используем TCP)


![image](https://github.com/user-attachments/assets/422065db-ce92-45a7-a7c9-aacec6a0c7a4)

на второй машине сделали всё тоже самое кроме открытия порта для получения логов,так как отсюда мы будем их отправлять,создали файл где прописали куда именно будет производиться отправка 



![image](https://github.com/user-attachments/assets/ee829ab7-52e1-4604-9154-ae6bb570cd5e)
проверка успешности отправки из 2-ой машины в 1-ую


![image](https://github.com/user-attachments/assets/dd393b9c-0a0b-439f-b383-68905092891e)
установили докер с локи и промтэйлом

![image](https://github.com/user-attachments/assets/0112572c-2937-4f33-ac05-9902afc2ad8d)
запустили его 

![image](https://github.com/user-attachments/assets/a04cfd31-be65-41f7-97b9-736bcefcaf32)
проверили 

![image](https://github.com/user-attachments/assets/7646d888-6891-4d46-a340-8474d096bdd3)
зашли в графану 

![image](https://github.com/user-attachments/assets/996f2ee6-6446-4fea-a6d2-6db60e0dd385)
установили promtail

![image](https://github.com/user-attachments/assets/91a0df18-0510-4944-aa94-0ee4e9f91e09)
![image](https://github.com/user-attachments/assets/84aecaf9-1842-4145-9fb9-5d4cbc42eee4)
поменяли конфиг у promtail

![image](https://github.com/user-attachments/assets/6de5a9e0-e3b8-4496-8a8b-e183172f0c27)
сделали конфиг для отправки из rsyslog в promtail

![image](https://github.com/user-attachments/assets/74f740c4-815b-44dd-a5ef-8be57241f9db)
установили data source в виде локи к которому подсоединен promtail 

![image](https://github.com/user-attachments/assets/99db310e-a67a-4c98-b311-165c6b68bec4)
открыли контейнер куда отправляются логи
