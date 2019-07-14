Sapphire UI application built on top of:

Angular 6.0
Nebular 
ngx-admin

1. Before pushing changes to git, make sure the app builds correctly using command:
  ng build --prod --build-optimizer

2. E2E
   a. Protractor

   b. Cucumber

   c.TestCafe
   npm i testcafe testcafe-angular-selectors
   npm i gherkin-testcafe cucumber

2. cuke:
   npm install --save-dev protractor-cucumber-framework
   npm install selenium-webdriver

3. start webdriver:
   ./node_modules/protractor/bin/webdriver-manager start



Test coverage - Sonar:
======================


To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

1. npm install -D sonarqube-scanner
1. ng test --code-coverage
2. sonar-scanner

Browse to: http://10.201.116.0:9000




Docker:


=======
List images: 
  docker images

Build sapphire-ui image:
  docker build -t sapphire-ui .



Minishift:
==========

start:  
  minishift start
  eval $(minishift oc-env) 
  eval $(minishift docker-env) 

console: https://192.168.99.101:8443/console  (system/admin)

=======

