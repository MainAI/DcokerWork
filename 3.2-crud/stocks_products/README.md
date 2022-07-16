* sudo docker build -t tagtest .
* sudo docker run -d -e DJANGO_SETTINGS_MODULE=stocks_products.settings -p 8080:8000 tagtest

Example check api working:  
GET http://localhost:8080/api/v1/

WSL2 vm check IP: 
ip a | grep inet  
Use IP instead of localhost 
