# TEST MAPPING WORKSHOP

This repo was created as part of the [Test automation Mapping Workshop at Automatyzcja Testów W Praktyce Conference](https://atwpraktyce.pl/)

Note that this repo is not a complete solution, but rather a starting point for the workshop. 
Full of delibratly broken code.



During Workshop
You will work in groups of 3-5 people. 
Together by exploratory test and code audit you will try to undestand how appliaction works.

Then you will reorginze test and map them to actual business requirements.


## For the workshop you will need:
1. Instaled node and npm
2. Ide of your choice that is supporing JavaScript
3. Zoom for communication
4. Access to slack (send in mail)
5. Access to fork of this repo (send in mail)
6. Access to currents.dev (send in mail)


## Workshop Author:

Maciej Wyrodek
* Blog: https://wyrodek.pl
* Youtube: https://www.youtube.com/@ITeaMorning
* Twitter: https://twitter.com/maciejwyrodek
* Linkedin: https://www.linkedin.com/in/wyrodek/
* Facebook:https://www.facebook.com/MaciejWyrodek.ITea/


## How to run tests

first you need to install all dependencies
```npm install```

then you can run tests
```npm test``` this will run all tests in headless mode

or you can run tests in browser
```npm run cy:open``` this will open cypress interface where you can run tests in browser

running test with currents
```npm currents:local``` this will run test localy but will raport results to currents.dev 
**Important** you will need to change ci-build-id run-team-test3 in package.json to after each run

##Guidelines---eleganccy enkoderzy##
*zasady*
-Testy grupujemy według obszaru testowania--nadrzędny folder. W konkretnym obszarze będą rozpisane następujące po sobie akcje testów
-nazewnictwo plików - według obszaru np. cart-view.cy.js
-nazewnictwo testów- cart-view-emptylist (description- cart-view; it-empty list)

