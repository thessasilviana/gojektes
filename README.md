What is this? : a few steps to shopping through the product detail page (PDP)

Description : relating to the questions given, the following method or this is a solution to shop on the amazon web with the automation test. 

Prerequisites : 
1. You can use any programming language (preferably Java). Any open source software may be used
and included, but no proprietary software or code should be used in the project, including any
(already) in-house written code.
2. You can either automate these in Web or Mobile browser using a any Test Automation framework
of your choice or even unit tests. (preferably Page Object Modal or BDD framework using
Cucumber).
3. Use Selenium/Appium with TestNG/Junit.
4. Please ensure you create a local git repository and write frequent commits to give us an idea of how
your solution evolved and give us a tarball or standard zip of your source code.
5. You can use Maven/Gradle project (not mandatory).
6. Please ensure you write modular and clean code with good naming conventions followed.
7. Please create a dummy Google and amazon account to automate this and sharethe password
as part of the solution. for example, email : thessabudimulia@gmail.com and password : 123456


Installing :
1. Selenium with TestNG/Junit - Selenium IDE - https://www.seleniumhq.org/selenium-ide/
2. Appium with TestNG/Junit
3. Katalon studio

About this extension :
Selenium IDE script is supported and can be loaded into Katalon Automation Recorded and export to multiple languages and formats.

Requirements :
Please investigate http://www.amazon.com/ website and write a UI automation framework covering
below scenarios. Must have [Required]:
1. Perform a simple login and logout flow on the site.
2. Select Departments section > Electronics > Headphones > Select first available headphone and Add
to cart.
3. Search for Macbook pro from Search bar and select 2nd available product and add to cart with
Quantity as 2.
4. Select cart from home and remove the earlier added headphones.
5. Reduce the quantity of the macbook pro product to 1 and proceed to checkout.
6. Data drive/parameterize to search for multiple different products via search bar.
7. Implement a reporting framework of your choice to display the test results.

Running the tests 
Pre condition :
1. For the login and logout scenario, user already registered account in the amazon website. Then, you can get this file for running these test case with download or export A-LoginLogout filename : https://github.com/thessasilviana/gojektest/blob/master/A-LoginLogout.java
2. Before login, you can get choose and order headphones with product detail page step on this B-headphones.java filename https://github.com/thessasilviana/gojektest/blob/master/B-headphones.java
3. And also you can order and add to cart macbook pro quantity as 2 before login with https://github.com/thessasilviana/gojektest/blob/master/C-macbookpro2.java
4. For the next, you can view all products after you added to cart and remove the earlier added headphones. on this https://github.com/thessasilviana/gojektest/blob/master/D-cart.java file
5. Reduce the quantity of the macbook pro product to 1 and proceed to checkout with https://github.com/thessasilviana/gojektest/blob/master/E-checkout.java
