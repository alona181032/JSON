# HW_2 : JSON

1. Создать внешний репозиторий c названием JSON;

2. Клонировать репозиторий JSON на локальный компьютер - `git clone URL`;
 
3. Внутри локального JSON создать файл “new.json” - `touch new.json`;
 
4. Добавить файл под гит - `git add .`; 
 
5. Закоммитить файл - `git commit -m "new file"`;
 
6. Отправить файл на внешний GitHub репозиторий `git push`;
 
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, 
    количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON:

```
{
	"info":
	{
		"about_me":
			{
			"person_name": "Alona",
      "person_last_name": "Bohdanets",
      "person_age": "32",
      "pets" : "4"
			},

		"work":
			{
				"position" : "QA Engineer",
				"salary" : 1000,
				"currency" : "USD"
			}
	}
}	
```

8. Отправить изменения на внешний репозиторий - `git commit -am "updated file" / git push`;
 
9. Создать файл preferences.json - `touch preferences.json`;
 
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON:

```
{
    "preference":
        {
    "favorite_film": "Split",
    "favorite_series": "Friends",
    "favorite_food": "French_fries",
    "favorite_season": "summer",
    "favorite_contry": "Spain"
         
        }
}
```
 
11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON - `touch skils.json`:

```
{
    "skills":
  {
             "1_lesson" : "Basic theory",
             "2_lesson" : "What is client-server architecture",
             "3_lesson" : "HTTP Server request methods",
             "4_lesson" : "HTTP server response codes",
             "5_lesson" : "HTTP request and response structures",
             "6_lesson" : "What is JSON, XML. Their structure",
             "7_lesson" : "API testing via Postman (JS, API autotests)",
             "8_lesson" : "Removing and reading logs from an external server",
             "9_lesson" : "Sniffing http web traffic via Charles and Fiddler",
             "10_lesson" : "Dev Tools of web browsers (Google Chrome, FireFox)",
             "11_lesson" : "VPN. (How it works, why you need it, how to use it, tool options)",
             "12_lesson" : "Mobile testing",
             "13_lesson" : "iOS feature, android, guidelines",
             "14_lesson" : "Building iOS apps with XCode",
             "15_lesson" : "Building Android apps with Android Studio",
             "16_lesson" : "ADB (android device management)",
             "17_lesson" : "Proxy and vpn setup on iOS and Android",
             "18_lesson" : "Interception (sniffing) mobile traffic via Charles and Fiddler on iOS and Android",
             "19_lesson" : "Linux command line (terminal) (copy, create, view, move files on non-GUI servers)",
             "20_lesson" : "Basic bash scripting, automation of routine tasks on the server",
             "21_lesson" : "Access to remote servers",
             "22_lesson" : "SQL Basics (Create, Delete, Drop, Insert Into, Select, From, Where, Join)",
             "23_lesson" : "Postgres database (installation, configuration and use)",
             "24_lesson" : "Redis non-relational database (installation, configuration and use)",
             "25_lesson" : "Load testing in Jmeter",
             "26_lesson" : "Scrum development methodology"
  }
}
```

12. Отправить сразу 2 файла на внешний репозиторий - `git add . / git commit -am "new 2 files" / git push`;
 
13. На веб интерфейсе создать файл bug_report.json;
 
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе;
 
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON:

```
{
"bug report":
{
"project" : "Govar",
"version" : "1.1",
"id" : "#1",
"summary" : "Clicking the 'A to Z' filter button on the main page of the app causes random list filtering",
"step_to_reproduce":
[
"1. Open the 'Govar' app",
"2. Create 15 lists that will start respectively (A, a, D, 3, :, U, u, W, w, 5, @, Ї, ї, -, d)",
"3. On the main page of the application, click on the 'A to Z' filter button"
],
"actual_result" : "Lists are sorted randomly",
"expected_result":
[
"The lists are sorted in order: symbols, numbers, Latin letters (upper case first), Cyrillic letters (upper case first)",
"The correct order is: (-, :, @, 3, 5, A, a, D, d, U, u, Ї, ї, W, w)"
],
"severity" : "Minor",
"priority" : "Low",
"status" : "new",
"environment" : "Samsung A72, Android 12",
"author" : "Alona Bohdanets",
}
}
```
 
16. Сделать Commit changes (сохранить) изменения на веб интерфейсе;
 
27. Синхронизировать внешний и локальный репозиторий JSON - `git pull`.
