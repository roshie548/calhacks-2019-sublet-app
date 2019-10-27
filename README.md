# Subletting Made Easy - CalHacks 2019
DocuSign API 2nd Place Winner

## Inspiration
During the past summer, we experienced the struggles of finding subletters for our apartment. Ads were posted in various locations, ranging from Facebook to WeChat. Our feeds were filled with other people looking for people to sublet as well. As a result, we decided to create Subletting Made Easy. We envision a platform where the process for students looking for a place to stay as well as students looking to rent their apartment out is as simple as possible.

## What it does
Our application provides an easy-to-use interface for both students looking for subletters, and students seeking sublets to find the right people/apartments.

## Tools Used:
- Android Studio
- Google Firebase
  - User login/authentication
  - Backend listings functionality
- DocuSign Click API
  - User agreements/signatures
- Heroku
  - Server to host the Click API connection point

## Challenges we ran into
Aside from building a clean UI and adding correct functionality, we wanted to create an extremely secure platform for each user on our app. Integrating multiple authentication tools from the Firebase and Docusign API caused various roadblocks in our application development. Additionally, despite working earlier in the morning, we ran into an Authentication Error when trying to access the HTTP Get REST API call within Click API (an expired token?), thus inhibiting our ability to verify the registration status of users.

## What we learned
We learned a lot about the process of building an application from scratch, from front-end/UI design to back-end/database integration.

## What's next
We built a functional MVP during this hackathon, but we want to expand our app to include more features such as adding secure payments and more methods to search and filter results. There's tons of possibilities for what we can add for the future to help students around the globe find sublets and subleters.
