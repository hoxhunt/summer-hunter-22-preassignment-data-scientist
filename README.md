## # <img src="./assets/pixel-duckyduck.gif" width="26" height="26" />  Hoxhunt Summer Hunter Program Pre-assignment - Data Scientist # <img src="./assets/pixel-popsicle.gif" width="26" height="26" /> 

The dictator of Snakeworld Ssamantha Snek <img src="./assets/pixel-snek.gif" width="20" height="20" />  has received all the accounts and passwords for the inhabitants of Snakeworld. Instead of responsibly removing the leaked data, she'd like to use this opportunity for punishing snakes with bad password hygiene. Ssamantha knows that it's dangerous to use the same password in several services - if one service is breached an attacker can now access all services with a shared password. 

Ssamantha would like you to find the number of users who have reused any password in 3 or more services. Ssamantha tells you that she will remove all data and secure the breach if you help her, so you reluctantly agree. 

Your puzzle input data can be found in the `data.csv` file, where it is in the format of: `service,email,password`. Your job is to find the number of users who have used any password more than twice. 

In the following example: 

```
aol,juliuss@snek.com,123password
yahoo,juliuss@snek.com,verystrongpasswordtoobaditsyahoo
netflix,juliuss@snek.com,123password
google,juliuss@snek.com,123password
aol,juliuss@snek.com,catfish
google,markuss@snek.com,catfish
yahoo,markuss@snek.com,catfish
```

Juliuss has reused the password `123password` in 3 services, so you should count him. Markuss, however has only reused the password `catfish` in two services, so you don't need to count him. The answer here would therefore be 1. 

We are looking for clean and readable code, so don't return a one-liner regex for this ;). We'll grade your assignment with the following model: 

- Code quality (simple, readable, easy to test) 3p
- Answer is correct 1p
- Code is returned correctly 1p 

Use the given `pre_assignment_data_scientist.py` template to implement your solution. We don't expect you to use a long time on this exercise. If we decide to move forward with you, there will be a more thorough take-home assignment to complete before the interview. 

You may use any external libraries you wish.

Return your solution as an __unlisted and Python syntax highlighted__ [pastebin](https://pastebin.com) link, and reply the link to the hiring manager. 

Good luck! <img src="./assets/pixel-porcuboi.gif" width="26" height="26" /> 

P.S. Never use the same password in more than two services. We recommend using two-factor authentification when possible, and a password manager with generated passwords for your services. If you are in a real life situation like this, report Ssamantha to the authorities and delete the credentials. 
