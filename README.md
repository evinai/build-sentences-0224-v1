## UD-Tim Flask Project 1 database as a service ref temp 0224-v2
['Tutorial']('https://www.udemy.com/course/python-rest-apis-with-flask-docker-mongodb-and-aws-devops/learn/lecture/10730604#overview')



| Rosource | Address | Protocol | Param | Response + Status Code |
| -------- | ------- | -------- | ----- | ---------------------- |
| Register User | /register | POST | username: str, pw: str | 200 ok |
| Store Sentence | /store | POST | username, pw, sentence | 200 ok, 301 out of tokens, 302 invalid username pw |
| Retrieve Sentence | /get | GET | username, pw | 200 ok, 301 out of tokens, 302 invalid username pw |