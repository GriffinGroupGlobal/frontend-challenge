# Griffin Group Global Front End Development Challenge

Hi! Thank you for your interest in [Griffin Group Global][g3website]. Our evaluation process begins with an open-ended coding challenge that we will discuss during your interview. There is not one correct way to approach this challenge. Rather, we would like to see your approach and your creativity in solving the problem.

We appreciate that any coding challenge represents an investment of your time. We hope you see the value in having a code sample that is relatable to both of us for the interview. Should you be unsuccessful, you should feel free to use the code you developed for this challenge in any way that you would like.

If you are successful, then we will set up an in-person interview and use this code as the starting point in our conversation.

# The Challenge
Griffin Group Global creates REST-based microservices that are presented in a variety of ways. We use iOS native Swift, Android-based Java and JavaScript-based frameworks such as React for creating responsive web-based presentations.

The challenge is to create a front-end presentation for the [Star Wars API][swapi]. The idea is for you to have fun and be creative with your presentations. The Star Wars API has a standard RESTful interface for types of data pertaining to the Star Wars universe. These include:
- [Planets](https://swapi.co/api/planets/)
- [Spaceships](https://swapi.co/api/starships/)
- [Vehicles](https://swapi.co/api/vehicles/)
- [People](https://swapi.co/api/people/)
- [Films](https://swapi.co/api/films/)
- [Species](https://swapi.co/api/species/)

Ideally, this would take a mid-level developer up to two hours to complete the minimum requirements.

## Minimum Challenge Requirements
We would like your submission to offer a minimum capability. The criteria are:
- Provide a presentation that provides a list of the Star Wars people displaying their name.
  - The list is paginated. Next and Previous buttons shall be implemented to update the displayed names.
- Either a mobile application or a browser-based presentation shall be created. 

## Where to concentrate your effort
In a UX/UI presentation, there are many areas that could be addressed. Working software is always top priority, however, so meet the minimum requirements. Should you want to go above and beyond the minimum requirements, please feel free to add to your submittal either via code or via documentation in [common mark][commonmark] compliant documentation.

- Providing more information about the Star Wars universe by following some of the extra links in the JSON data model
- If implementing in swift, some items to consider that we would like to see
  - Use TableView and or CollectionView
  - implement delegate methods of one of the above classes
  - implement a custom user interaction
- Error handling
- Debug statements
- [TDD]
- Encrypted communications
- Caching
- UX, reducing the amount of input from the user
- Responsive presentation, determining the screen size and autoscaling the display

# Prerequisites
- A basic understanding of source code control, [git][git-scm] is required.
- You must make your code available via a [GitHub][github] account.
- All JavaScript shall be written using [ES6][ES6] standards.

# Getting Started
1. Fork this [repository][repository].
1. Clone the fork to your personal machine.
1. Start coding.
1. Commit changes to your fork as you see fit.

# Submission

When you are comfortable with your results, please email your fork to
[g3-dev@griffingroupglobal.com](mailto:g3-dev@griffingroupglobal.com). Please keep your emails short and to the point.

Any specific notes or further information you would like to add about your submittal, should be included in the GitHub project, as additional [Common Mark][commonmark] notes.

Do not feel as though you must create a public fork of this repository. You are free to create a throwaway GitHub account or private fork. In those cases, please let us know so that we may send you the GitHub IDs to add to the repository.

# Evaluations

We realize there are many items to look at when creating a user interface. Please do not feel like like you have to do everything. Please feel free to use any front-end language you wish. Use your strengths to your advantage. If you gravitate more towards design, provide a more visually appealing interface. If you gravitate more towards data consumption, provide more capability by using the API routes. Give us a heads up by documenting your code to let us know where and why you concentrated on certain items.

As you develop your solution, you may have ideas on other avenues to pursue. Please feel free to include them inline as documented source or as additional [Common Mark][commonmark] compliant notes in your fork.

We look for creativity, originality, and a good user experience in your application if that's an area you focused on.

We look for readability, good architectural decisions, modularity, and a solid approach to testing in your code.

# License
This project is [MIT licensed][mitlicense].

[g3website]:https://www.griffingroupglobal.com
[git-scm]:https://git-scm.com/
[github]:https://github.com/
[nodejs]:https://nodejs.org/en/
[TDD]:https://en.wikipedia.org/wiki/Test-driven_development
[ES6]:http://www.ecma-international.org/ecma-262/6.0/
[eslint]:https://eslint.org/
[airbnb-eslint]:https://www.npmjs.com/package/eslint-config-airbnb
[mocha]:https://mochajs.org/
[repository]:https://github.com/GriffinGroupGlobal/frontend-challenge
[mitlicense]:https://en.wikipedia.org/wiki/MIT_License
[commonmark]:https://spec.commonmark.org/
[swapi]:https://swapi.co/