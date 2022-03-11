===========
### XML
===========
1. Создать внешний репозиторий c названием XML.  
**`Зайти на сайт github.com, создать новый репозиторий XML, нажать Code и скопировать ссылку на репозиторий`**

2. Клонировать репозиторий XML на локальный компьютер.  
**`На локальном компьютере зайти в папку, где будет размещен репозиторий, запустить Gitbash и ввести команду git clone https://github.com/AlexKantrov/XML.git`**

3. Внутри локального XML создать файл “new.xml”.  
**`cd XML/ (перейти в папку созданного репозитория на локальном компьютере) и ввести команду touch new.xml`**

4. Добавить файл под гит.  
**`git add new.xml или git add . (добавляет все существующие файлы)`**

5. Закоммитить файл.  
**`git commit -m "add new.xml"`**

6. Отправить файл на внешний GitHub репозиторий.  
**`git push`**

7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных,
 будущая желаемая зарплата). Всё написать в формате XML.  
 **`vim new.xml`**
 ```
  <info>
	  <name>Alexey</name>
	  <surename>Kantrov</surename>
	  <age>39</age>
	  <pet>1</pet>
	  <expectedsalary>1500</expectedsalary>
  </info>  
  ```
8. Отправить изменения на внешний репозиторий.  
**`git add new.xml => git commit -m "modified new.xml => git push`**

9. Создать файл preferences.xml  
**`touch preferences.xml`**

10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда,
 любимое время года, сторона которую хотели бы посетить) в формате XML.  
**`vim preferences.xml`**
```
  <mypref>
    <favoritemovie>Fight Club</favoritemovie>
    <favoriteserial>Breaking bad</favoriteserial>
    <favoritefood>Pizza</favoritefood>
    <favoriteseason>spring</favoriteseason>
    <countryiwouldliketovisit>Australia</countryiwouldliketovisit>
  </mypref>
```
11. Создать файл sklls.xml добавить информацию о скиллах, которые будут изучены на курсе в формате XML  
**`touch skills.xml => vim skills.xml или cat > skills.xml`**
```
<?xml version="1.0" encoding="UTF-8"?>
<skills>
	<a>theory</a>
	<b>bagreport</b>
	<c>client-server</c>
	<d>http</d>
	<e>respondes_code</e>
	<f>structure_selects</f>
	<g>json</g>
	<h>xml</h>
	<h>python</h>
	<i>other_soft</i>
</skills>>
```
12. Сделать коммит в одну строку.  
**`git add . && git commit -m "add new xml file"`**

13. Отправить сразу 2 файла на внешний репозиторий.  
**`git push`**

14. На веб интерфейсе создать файл bug_report.xml.  
**`В репозитории XML (сайт github.com) нажимаем на кнопку "add file" и нажимаем "create new file" с названием bug_report.xml`**

15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
**`В появившемся окне нажимаем "commit new file"`**

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
**`На вебинтерфейсе открыть файл путем редактирования и ввести текст`**

17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
**`Сохранить изменения (нажать на кнопку Commit changes на вебинтерфейсе)`**

18. Синхронизировать внешний и локальный репозиторий XML  
**`git pull`**
