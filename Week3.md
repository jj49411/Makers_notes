# Week 3

[Weekly Goals](#weekly-goals) | [Daily Goals](#daily-goals) | [Weekly Challenge](#weekly-challenge) | [Weekend Challenge](#weekend-challenge) | [Workshops](#workshops)



## Weekly Goals

1. Build a simple web app
2. Follow an effective debugging process for web applications
3. Explain the basics of how the web works (e.g. request/response, HTTP, HTML, CSS)
4. Explain the MVC pattern
 

## Daily Goals
### Day 1
- GOAL: Learn web basics- request/response, HTTP, HTML, CSS. Review others' code
- REFLECTION: Grabbed the ideas of request/response which was fun! 
> We went through steps of basic HTTP and built a Sinatra application as a server. It was a great pairing experience, reading the instuction to each other.
```
Feedback on my weekend challenge: 
1) "testing the behaviour rather than the state"
2) use `puts` for normal output
3) better to have a method on the Menu class that allows you to get the dish rather than exposing the menu attribute and allowing people to change the menu whenever they like.
4) `allow(menu).to receive(:menu).and_return({ "sausage" => 4 }) ` so it can call the menu on the double menu
```

### Day 2
- GOAL: Work on practical-1, drafting the blog post, know more about HTTP, request/response
- REFLECTION: Had better understanding on the HTTP request/response and how to apply the HTTP cycle
> We set up the test infrastructure, using Capybara(the extension of Rspec) to test our first feature for the route'/names'. Noticing the minor difference in symbols can make a big difference. Nice teamwork of building the server/test model!<br>During the process modelling workshop, we use "Ping-pun diagram" to sum up the web routes. It was great fun and I had a better understanding on the relationship between client/server. 

### Day 3
- GOAL: Improve my knowledge of Servers through the practical
- REFLECTION: Learned some tips for improving my empathetic skills in "Empathy workshop". Practised how to use the network IP address to connect with other server, and as a server, created a new class and make a notes app to control over the network.
> During the pairing, we went throgh some Sinatra/Capybara settings to have a better understanding, looking into get/post requests.

### Day 4
- GOAL: MVC pattern, debugging process for web application
- REFLECTION: Successfully debugged a web page in the workshop, had better understanding on the debugging process. Had a look at MVC pattern, still not quite sure how to apply.
> We used some application logic stored in a model layer(./lib) to seperate the concerns. Nice teamwork! $global variable can crash the whole test!

### Day 5
- GOAL: Testing me current understanding of the web building concepts 
- REFLECTION:
>


## Weekly Challenge
- **Battle Web App**:
Repo [here](https://github.com/jj49411/battle-thu)

- **Birthday Application**:
Repo [here](https://github.com/jj49411/birthday_app)

## Weekend Challenge
- **Rock, Paper, Scissors Application**:
 Repo [here](https://github.com/jj49411/rps-challenge)


## Workshops

### Process Modelling Workshop

1. Essential in README File
 -	How does it do?
 -	How the install it/run it? 
 - How to teet it?
 
 2. 
 
### Debugging Workshop

1. Tightening the loop (read error messages)
2. Get visibility (using p)

