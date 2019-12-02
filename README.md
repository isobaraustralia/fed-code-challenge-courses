# Isobar Front End Code Challenge

Congratulations on passing the first round interview at Isobar!  We would now love you to complete a code challenge to show us what you can do!

Please use your preferred JS framework (React, Vue, jQuery or Vanilla JS) to create a small web application.

We strongly recommend that you cap the time you spend on this challenge to 4hrs and showcase your strength and your coding standards while fulfilling the requirements for the challenge.

## The Challenge
Use the data provided to create a small web application. You can pick as many/or as few of the criteria below to build the application within the recommended time cap.

1. It should display list of all available courses
2. It should have a search field where you can search and filter available courses by typing in the search field
3. It should have a sort filter, you should be able to sort courses by date and duration
4. Hovering over a course should display an add button
5. Clicking on the add button should open a modal asking for your login credentials
6. After submitting the form with any credentials, user must get a successful login message and modal should close
7. Course should be added to a cart on the side of the screen
8. Clicking on new add button should not promote login modal if you have already logged in and it should add course to the side cart panel  
9. If a course has already been added to your cart, hovering over should display a remove button
10. Clicking on the remove button should remove course from side cart

```
[
  {
    "lessons": [
      {
        "name": "React - basics",
        "description": "This course is going to take you through basics of React.",
        "author": "James White",
        "publishDate": "12/03/2019",
        "duration": "00:03:56",
        "image": "https://cdn.auth0.com/blog/react-js/react.png"
      },
      {
        "name": "Vue - learn vue in an hour",
        "description": "This course teaches you how to build a vue application in an hour.",
        "author": "Michael Brown",
        "publishDate": "17/10/2019",
        "duration": "00:00:59",
        "image": "https://vuejs.org/images/logo.png"
      },
      {
        "name": "CSS Animations",
        "description": "Learn how to animate anything in CSS",
        "author": "Alan Smith",
        "publishDate": "04/12/2018",
          "duration": "00:02:11",
        "image": "https://cdn.pixabay.com/photo/2017/08/05/11/16/logo-2582747_960_720.png"
      },
      {
        "name": "JS - Zero to hero",
        "description": "Everything you need to know in JS",
        "author": "Sarah Parker",
        "publishDate": "12/03/2019",
          "duration": "01:01:35",
        "image": "https://cdn.pixabay.com/photo/2015/04/23/17/41/javascript-736400_960_720.png"
      }
    ]
  }
]
```

## Assessment Criteria
* Quality over quantity, we will assess your code based on the quality of the work you have produced and not based on how many of the criteria you have completed.
* Unit testing is important, test parts of the app that you think requires testing. We don't expect 100% test coverage but all major pieces of functionality should have unit tests.
* We value UI skills so give focus to showcase these. It is acceptable to use a framework for creating layout.
* Please provide a readme file and explain your approach to the challenge and your reasons for picking certain criteria over others.
* Code must be clean and well documented. If your code is self explanatory then there is no need for comments.
* While it is acceptable to use helper libraries keep in we want to assess your ability so be weary of over reliance on these. 


## Submission
Please create a repo in your preferred git provider like bitbucket, github or gitlab. Please commit regularly with meaningful commit messages so that we can understand your approach and how you solved the challenge.

**Bonus:** You can deploy your web app to heroku, netlify or other similar services.
