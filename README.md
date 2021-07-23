# ps1_avy

## Our Problem Statement : Website Search

## Team Name - AVY

| Team member         | Graduating year | College Name |
| ------------------- | :-------------: | -----------: |
| Abhishek Kumar      |      2022       |  IIIT Ranchi |
| Baki Yaswanth Reddy |      2022       |  IIIT Ranchi |
| Vimal Kumar         |      2022       |  IIIT Ranchi |

## About Our Self :

- We have participated in DigitalOcean (Dev.to) hackathon, Smart india hackathon and Flipkart Grid-2.O
- DigitalOcean : We have created a customer based service in which we have analysed the customer data and represented that data into simplified representation like graphs , charts. And also we have created a portfolio website.
- Smart India hackathon : We have created reCAPTCHA based system for blind people in which a robot voice uses a six character Alphanumeric text and the user has to spell those alpha-numeric text and then we compared it with system whether this is a robot voice or human voice.
- Flipkart Grid 2.O : We have taken part in the Robotics challenge in which we worked on Intelligent Picking autonomous robot. We were Semi-Finalist in this competition.

## Overview of our solution :

We have divided our solution into three sections :

1. _Web scraping:_ We have to explore all the pages contained in a website through site-map and extract data like (All H1 tag content , page url , most used words) from the web-pages using web scraping, then we have to saved that data in MongoDB.

![Scrapping](/assets/scrapping.png)

2. _Back-end :_ We will create a Restful Api (server), in which the server will retrieve user input as a string (The word that has been searched) from the front-end and then the server will search that keywords in mongoDB and then it will send the JSON data to the client (frontend).

![Back-end](/assets/backend.png)]

3. _Front-end :_ We will create a web app based on ReactJs, in which we will request user input and send that input keyword to server through Rest Api, and then server will send that relevant data, then we will showcase that data to user in a nice, clean, user friendly and responsive interface. So that the user will be satisfied from the result.

![Front-end](/assets/frontend.png)

## Process Flow :

![Process Flow](/assets/process-flow.png)
![Process Flow](/assets/process-flow-2.png)

## Tech Stack :

- Web Scraping : BeautifulSoup
- Backend : NodeJs, Express
- Frontend : ReactJs
- Cloud Service Providers : Netlify, Heroku
- Database : MongoDB
- Design : Figma

## So, how is our solution different?

- We will store the number of click on that page for ranking.
- We will show any search result in three parts that contains Blog, Products, And other pages.
- We are using Beautifulsoup to scrape the required data from the webpage which is one of the most popular Python libraries which helps in parsing HTML or XML documents into a tree structure to find and extract data. So it is easy to work with website data.
- We are using netlify for our project. Netlify makes our live website available to users without delay through a customizable domain and offers a free-of-cost SSL.
- Our UI/UX will be user friendly and also be unique and one of its kind.

## Future Possible Enhancements :

- We will try to create a system in which we will try to auto complete customer input and show them the most relevant search option. So that customer experience will be faster.
- We will save the most search keywords and recommend those keywords to the user so that they can select them and there is no need to type the keywords by themselves and save their time.
- We will be directly interacting with customer and we will be collecting the most asked customer queries and try to improve our searching system to provide most relevant solution to them instantly by saving those solutions of most asked queries.

## Risks/ Challenges / Dependencies :

- We will face challenges in Web Scraping Automation.
- To list the Web pages of Bajaj Website for Web scraping through sitemap.
- There will be risk in seeking permission from Bajaj website for web scraping.
- To rank the web pages according to data like SEO.
- To Classify the index of different web pages like blog page, insurance page, product page, tools etc.

## Thank You!
