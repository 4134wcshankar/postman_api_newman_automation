



Docker: 
* Install Docker and execute below command 
* docker pull kennethreitz/httpbin
* docker images
* docker run -p 80:80 kennethreitz/httpbin

npm install -g npm
node -v
npm -v
sudo npm install -g newman
sudo npm install -g newman-reporter-html
sudo npm install -g newman-reporter-htmlextra
newman run  ALL_E2E_Test.postman_collection.json -r cli,htmlextra --reporter-html-export ./newman_reports
