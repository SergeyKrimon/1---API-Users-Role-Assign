# Corporate.Axia.Users

Build MOCK
sudo docker build -t wiremock-axiausers .

RUN MOCK

sudo docker run -it --rm -p 8080:8080 wiremock-axiausers

RUN MOCK ONE LINE

sudo docker build -t wiremock-axiausers . ; sudo docker run -it --rm -p 8080:8080 wiremock-axiausers