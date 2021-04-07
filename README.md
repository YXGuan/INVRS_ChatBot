# INVRS_ChatBot
https://www.invrs.com/
code available in the master branch

### Update01            6th.Apr
![image](https://user-images.githubusercontent.com/55643200/113796250-cd0d2000-971c-11eb-9688-a10f91911d04.png)

- IDE: Eclipese
- Language: Java,  [AIML 2.0](https://howtodoinjava.com/ai/java-aiml-chatbot-example/)
- Estimate: 1 week to build Java-back-ended bot, Another one week to integrate the bot with the existing website
- Reference: https://www.youtube.com/watch?v=XVxYK5AU8H0
- [X] The user will be able to converse normally with the bot.
- [X] Connected Github and Eclipese, pushed and commited to Master branch 





### Update02            7th.Apr  
quick summery: when user type in any keyword include stock split, the robot will answer the definition of it. When user input is stock exchange, the bot will ask user which country, the answer should be either us/US or canada/Canada (case insensitive)

![image](https://user-images.githubusercontent.com/55643200/113903896-772d8c00-979f-11eb-8de2-dd65433cd16f.png)
![image](https://user-images.githubusercontent.com/55643200/113905500-359de080-97a1-11eb-8bbf-ee9856d1c978.png)


| Test        | Pass or not     | comment
| :---        |          :---: |  ---: |
| what is stock split?      | Pass   | |
| what is stock split ?   | Pass      ||
| what is stock split | Pass ||
| stock split | Pass ||
| tell me litttle bit more about stock splitt| not Pass| (as intended)||
| stock exchange, US | Pass |  |
| stock exchange, USA | fail | the bot can not tell the difference between US, usa and the states |
| where's stock exchange ?, US | Pass |  |
| stock exchange, the country is us. | fail | user's second answer can only be us or canada |


- tool: https://home.pandorabots.com/dash/edit/invrs   --> focus on  AIML today
- reference: https://www.youtube.com/watch?v=6sRfXN6asyI&list=PLjBRL4AgNs3EXFdRPvj1cuLsOOIq8vfgm&index=4 7 episode AIML tutorial on YT
- issue: see issue section
- [X] The bot will let the user ask for a list of major US exchanges and provide the list.
- [X] The bot will let the user ask what a "stock split" is and provide a definition.






### future
- [ ] build an interface app inside Eclipse
- [ ] modify the AIML




