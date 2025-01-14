# Request Response Cycle, APIs, and Postman Lab

You will be working with a free API of your choice for this lab.

## Getting Started

1. Choose an API with no auth and no CORS from the following list. It _should not_ be one that you've already seen or worked on in class.
   - [Public APIs](https://github.com/public-apis/public-apis)
1. Choose an API not covered in your readings, class, or other assignments. The API should be new to you.
1. Write your answers in this README.md file. Do not delete the questions. Write your answers after the `>`. If you need to write more than one paragraph, add more `>`.
1. Take the time to read back the work, and edit what you've written so that your answers are clear and anyone reading it can easily understand what you've written.

## Instructions

Do your best to answer the questions with specific details. Writing about code clearly and thoroughly is a critical skill to practice.

- Which one did you choose? Provide the name and base URL.

> https://github.com/wh-iterabb-it/meowfacts
> I chose meowfacts

- What is the purpose of this API? Describe what data the API provides and why someone might want to use it.

> The purpose of this API is to provide a random cat fact on request

- What is the URL of the documentation?

> https://github.com/wh-iterabb-it/meowfacts/blob/main/README.md

### Response

For the following questions, choose a single endpoint to request within Postman.

- What is the full URL of the endpoint?

> https://meowfacts.herokuapp.com

- What response do you receive when you make a request to that endpoint? Be sure to wrap your answer in the correct formatting for JSON.

```json
{
    "data": [
        "Cats sleep 70% of their lives."
    ]
}

```

- What status code did you get back from your request? Why did you receive this status code?

> 200
> I received this code because the API worked fine and the HTTP request was successful

- Click on the **response** headers in Postman. What are the `Content-Type` and `Content-Length` (provide exact values)?

> `Content-Type`: (application/json; charset=utf-8)

> `Content-Length`: (319)

- Summarize the most salient parts of the data you are getting back. How would you describe what is included within the response?

> The data we received includes an object with one array titled "data." The data includes random facts about cats generated by the API

- Identify at least two ways to use the data within a web application.

> I could imagine integrating this API into an app that displays random cat facts while fetching your data, or to be used in a cat themed website that displays a new fact everytime you reload the page. I can't think of many other uses for it unfortunately. It's just nice to have.

### Documentation

The following questions relate to the documentation of the API.

- What did you like about the documentation? Cite specific examples.

> The documentation was clear, concise, and had all of the data that I needed to use it correctly. For example, it didn't just give me the instructions in plain english, it also gave me code snippets of what to expect per instruction. Not to mention all of the instructions were organized and seperated by h2 text.

- What did you find challenging about the documentation? Cite specific examples.

> I found the documentation not challenging at all. In fact it was a breath of fresh air since the other 3 APIs I tried either had irrelivant documentaion or none at all. I think I was just unlucky.

- Did the quality of the documentation impact your decision to use it?

> Yes because I was expecting to read the documentation and still not know how to use it, but I had a good grasp of what to do after reading.

- Did you switch which API you chose initially because of its documentation, or did you stick with the one you selected and work your way through it?

> Yes I ended up switching which API I chose initially because I just couldn't find the URL endpoint. I initially chose lordicon.com to use as an API because I thought I could use it to generate random icons on request, but there was no endpoint provided, so I figured it wasn't meant for me.

### Definitions

The following questions require you to define some concepts and terms. Provide detailed explanations.

- In your own words, summarize the request-response cycle.

> The request-response cycle is a way for the client, server, and database to all communicate with each other to keep the site running smoothly and to give the client what they want. 

- In your own words, describe what an API is.

> An API is kind of like a modular piece of a machine thats pre-built and can be selected,installed, or replaced depending on the needs of the programmer. For example let's say that you have an AI that you wan't to train by feeding it data. Naturally after working so hard to make an AI, you wouldn't want to spend hundreds of hours finding the right data to give to it. The solution find an API that can do it for you. Just have the AI pull data from the API you picked instead of combing the net by hand.

- In your own words, describe the purpose of Postman.

> Postman is an application that allows developers to test, create, and use APIs.
