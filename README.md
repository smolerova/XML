## XML
 21. Создать внешний репозиторий c названием XML.
  22. Клонировать репозиторий XML на локальный компьютер.
`git clone https://github.com/smolerova/XML.git`
 23. Внутри локального XML создать файл “new.xml”.
`touch "new.xml"`
 24. Добавить файл под гит.
 `git add new.xml`
 25. Закоммитить файл.
`git commit -m "add new file"`
 26. Отправить файл на внешний GitHub репозиторий.
`git push`
 27. Отредактировать содержимое файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
```XML
<?xml version="1.0" encoding="UTF-8"?>
<person>
   <name>Natallia</name>
   <lastName>Smolearova</lastName>
   <middleName>Vasilevna</middleName>
   <age>32</age>
   <pet>1</pet>
   <salary>500</salary>
</person>
```
 28. Отправить изменения на внешний репозиторий.
`git add new.xml`
`git commit -m "fill data in new.xml"`
`git push`
 29. Создать файл preferences.xml 
 `touch preferences.xml`
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

```XML
<?xml version="1.0" encoding="UTF-8"?>
<preferences>
	<favourites>
		<favoriteMovie>The Shawshank Redemption</favoriteMovie>
		<favoriteSeries>Criminal Minds</favoriteSeries>
		<favoriteFood>Grilled Meat</favoriteFood>
		<favoriteSeason>Summer</favoriteSeason>
	</favourites>
	<wishList>
		<Country>Portugal</Country>
	</wishList>
</preferences>
```

 31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
`touch skills.xml`
```XML
<?xml version="1.0" encoding="UTF-8"?>
<skills>
	<skill>Bash</skill>
	<skill>Git</skill>
	<skill>Postman</skill>
	<skill>DevTools</skill>
	<skill>VPN</skill>
	<skill>Mobile Testing</skill>
	<skill>Charles</skill>
	<skill>SQL</skill>
</skills>
```
 32. Сделать коммит в одну строку. 
`
git add .
git commit -m "edit 2 files"
`
 33. Отправить сразу 2 файла на внешний репозиторий.
`git push`
 34. На веб интерфейсе создать файл bug_report.xml.
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
```XML
<?xml version="1.0" encoding="UTF-8"?>
<BugReport>
  <ID>12</ID>
  <Summary>The Familyapplication allows the input of letters in the field Birth Day</Summary>
  <Severity>Major</Severity>
  <StepsToReproduce>
     <Step>Start the Family application</Step>
     <Step>Click on Husband tab</Step>
     <Step>Click on New button</Step>
     <Step>Try to input letters in the field Birth Day</Step>
  </StepsToReproduce>
  <ExpectedResult>Letters are not entered in the field Birth Day</ExpectedResult>
  <ActualResult>The field Birth Day allows input of letters</ActualResult>
</BugReport> 
```
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 38. Синхронизировать внешний и локальный репозиторий XML
```
git fetch
git pull
```
