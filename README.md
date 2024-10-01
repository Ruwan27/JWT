This for login curl request 


curl --location 'http://localhost:8080/signin' \
--header 'Content-Type: application/json' \
--header 'Cookie: JSESSIONID=D691DE4D403EDCBE8896F40CFA1709F5' \
--data '{
    
    "username":"user1",
    "password":"password1"
}'

confirm hello contrller using below request 

curl --location 'http://localhost:8080/hello' \
--header 'Content-Type: application/json' \
--header 'Authorization: Bearer eyJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1c2VyMSIsImlhdCI6MTcyNzc1NTczNiwiZXhwIjoxNzI3NzU4NzM2fQ.JcW9V2SM-i7K57kRTmaRuetYFgt6oMdmEjWN9hQ6EC8' \
--header 'Cookie: JSESSIONID=D691DE4D403EDCBE8896F40CFA1709F5' \
--data ''
