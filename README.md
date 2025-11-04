# studious-tribble
lab3-
lab03-bookstore/
│
├─ docker-compose.yml
├─ database/
│   └─ init.sql
├─ backend/
│   ├─ Dockerfile
│   ├─ app.py
│   └─ requirements.txt
├─ console_app/
│   └─ client.py
└─ README.md                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         
PS C:\Users\VLAD> python console_app/client.py
C:\Users\VLAD\AppData\Local\Programs\Python\Python313\python.exe: can't open file 'C:\\Users\\VLAD\\console_app\\client.py': [Errno 2] No such file or directory 
PS C:\Users\VLAD> docker exec -it <ім'я_контейнера_postgres> psql -U postgres -d bookstore
>> SELECT * FROM books;
>> books = client.get_books()
>> for book in books:
>>     print(book)
>> title = "Нова книга"
