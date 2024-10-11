# XML
#### 21. Создать внешний репозиторий c названием XML.
- перейти по ссылке https://github.com/Liudmila-Papko?tab=repositories
- нажать кнопку New
- ввести Repository name (XML)
- выбрать Public
- выбрать Add a README file
- нажать Create repository
- скопировать HTTPS
#### 22. Клонировать репозиторий XML на локальный компьютер.
```
git clone https://github.com/Liudmila-Papko/XML.git
```
#### 23. Внутри локального XML создать файл “new.xml”.
```
touch new.xml
```
#### 24. Добавить файл под гит.
```
git add new.xml
```
#### 25. Закоммитить файл.
```
git commit -m "add new file"
```
#### 26. Отправить файл на внешний GitHub репозиторий.
```
git push
```
#### 27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```
vim new.xml
INSERT (i)
<?xml version="1.0" encoding="UTF-8"?>
<xml>
<field name="Name">Liudmila</field>
<field name="Surname">Papko</field>
<field name="Age">37</field>
<field name="Pets">0</field>
<field name="Future salary">100000</field>
</xml>
ESC :wq
```
#### 28. Отправить изменения на внешний репозиторий.
```
git commit -am "add file About me"
```
#### 29. Создать файл preferences.xml
```
touch preferences.xml
``` 
#### 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
```
vim preferences.xml
INSERT (i)
<?xml version="1.0" encoding="UTF-8"?>
<xml>
	<field name="Film">August Rush</field>
	<field name="Serial">Sherlock</field>
	<field name="Food">Pancakes</field>
	<field name="Season">Summer</field>
	<field name="Country">Great Britain</field>
</xml>
ESC :wq
```
#### 31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
```
vim skills.xml
INSERT (i)
<?xml version="1.0" encoding="UTF-8"?>
<xml>
	<field name="skill1">Teory of testing</field>
	<field name="skill2">Terminal</field>
	<field name="skill3">GitHub</field>
	<field name="skill4">DevTools</field>
	<field name="skill5">Fiddler</field>
	<field name="skill6">Postman</field>
	<field name="skill7">SQL</field>
	<field name="skill8">Charles</field>
	<field name="skill9">ADB</field>
	<field name="skill10">Android studio</field>
	<field name="skill11">JMeter</field>
	<field name="skill12">JS</field>
	<field name="skill13">Swagger</field>
	<field name="skill14">Wegservises</field>
</xml>
ESC :wq
```
#### 32. Сделать коммит в одну строку.
```
git add preferences.xml skills.xml | git commit -m "Add Preferences and skills"
````
#### 33. Отправить сразу 2 файла на внешний репозиторий.
```
git push
```
#### 34. На веб интерфейсе создать файл bug_report.xml.
- перейти по ссылке https://github.com/Liudmila-Papko/XML
- нажать Add file
- выбрать из выпадающего списка + Сreate new file
- ввести название файла bug_report.xml
##### 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- нажать Commit changes
- изменить Commit message (необязательно) 
- добавить Extended description (необязательно)
- нажать Commit changes
#### 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
- нажать на файл bug_report.xml
- нажать на иконку редактирования
- ввести текст
```
<?xml version="1.0" encoding="UTF-8"?>
<xml>
 <BugReport>
	<ID>1</ID>
	<DateReported>2024-10-10</DateReported>
	<Priority>Critical</Priority>
	<Environment>Win 11 Chrome 129</Environment>
	<Title>"Button [Login] on the search page is automatically refresh the page</Title>
	<StepsToReproduce>
         <Step>1. Navigate to Capital.com</Step>
         <Step>2. Click on the button [Search] and press Enter</Step>
         <Step>3. Click on the button [Login]</Step>
        </StepsToReproduce>
 	<ExpectedResult>Login form is opened.</ExpectedResult>
	<ActualResult>The page is refreshing</ActualResult>
	<Attachment>Link</Attachment>
	<Author>Name</Author>
	<Status>Opened</Status>
	<Bugcomments>null</Bugcomments>
 </BugReport>
</xml>
```
#### 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
- нажать Commit changes
- изменить Commit message (необязательно) 
- добавить Extended description (необязательно)
- нажать Commit changes
#### 38. Синхронизировать внешний и локальный репозиторий XML
```
git pull
```
