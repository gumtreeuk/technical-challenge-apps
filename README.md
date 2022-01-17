# technical-challenge-apps

## The task
Your task is to develop a small Android application in Java or Kotlin. We need you to build your application in your own GitHub repository. Please do not fork our repository to create your project. Once you are done, send us a link to your repository.

Feel free to spend as much time on the task as you like but bear in mind that we are assessing other candidates at the same time. Thus we recommend one week turnaround from when you received the assessment until that assessment gets to us.

## The application
The application should be based on the existing functionality of the Motors.co.uk mobile app. For scope of this assignment, we would like you to focus on:
1. The search screen 
2. Ability to search by make, model, and year
3. Display the search results on the screen

To get search results you can use Postman and this simple mock API call:

http://mcuapi.mocklab.io/search?make=[make]&model=[model]&year=[year]

For example:

http://mcuapi.mocklab.io/search?make=Nissan&model=Juke&year=2020

Will return:
```json
{
  "searchResults": [
    {
      "id": "221843",
      "name": "Nissan Juke",
      "title": "Nice car for sale",
      "make": "Nissan",
      "model": "Juke",
      "year": "2020",
      "price": "£212.00"
    },
    {
      "id": "397286",
      "name": "Nissan Juke",
      "title": "Used car in mint condition",
      "make": "Nissan",
      "model": "Juke",
      "year": "2020",
      "price": "£201.00"
    },
    {
      "id": "390251",
      "name": "Nissan Juke",
      "title": "Low mileage car for sale",
      "make": "Nissan",
      "model": "Juke",
      "year": "2020",
      "price": "£307.00"
    },
    {
      "id": "012565",
      "name": "Nissan Juke",
      "title": "Car for sale with unique specs",
      "make": "Nissan",
      "model": "Juke",
      "year": "2020",
      "price": "£389.00"
    }
  ]
}
```
***If the api is not working on your browser, please use developer tools on your Google Chrome and check the response in the network traffic tab. You should be able to see the JSON returned in there. See the [troubleshooting instructions](https://github.com/gumtreeuk/technical-challenge-apps/blob/main/troubleshooting.md) for more details.***

## Acceptance Criteria
- The user should be able to search by make, model, and year
- The user should be able to scroll through results on the screen

## General Coding Guidelines
- The API call doesn't work on the browser, you need to use PostMan to access it.
- Use the data that is available in the API response. If there's extra data you'd like to display, use dummy local data.
- Don't check in unnecessary files. Use .gitignore to exclude bin folder and other unnecessary files.
- Following best coding practices (SOLID, DRY and KISS, leverage OOP principles).
- Write clear, maintainable code.
- Leverage design patterns.
- Please do not use database, we are more interested in your Android and coding skills than your SQL skills
- Feel free to commit as often as you'd like. The more commits the better! Please commit at least once within the first hour

## Expectations
- The code should build and run on our machines without issues
- The application should have tests, and they should all pass
- It's better to complete 1 task than to start 3
- Feel free to use any libraries you feel appropriate
- We will be looking at how you approach the task (e.g. how you break it into sub-tasks) and how you structure your code to answer the questions
