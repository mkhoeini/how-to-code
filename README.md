how-to-code
===========

1. [Think about what you want to code][1]
2. [Create the github repository][2]
  1. [Choose a fitting name][2.1]
  2. [Choose private/public][2.2]
  3. [Choose a license][2.3]
3. [Write down a README][3]
4. [Open up a Trello board for your project][4]
5. [Write tests for a feature][5]
  1. [Choose a task from your todos deck and move it to doing deck][5.1]
  2. [Write tests][5.2]
6. [Try to pass the tests][6]
7. Profit!


[1]: #1-think-about-what-you-want-to-code
1. Think about what you want to code
---

These days it becomes increasingly easier to just start to code. People just get a stroke of an idea and then they open their code editor, search github, npm, pipy for relevant peases of code and start to implement it. But it is not a good way. You should dedicate some time to think about what you finaly want to achive, How the API will look like in the end, etc. even before you start to code.

[2]: #2-create-the-github-repository
2. Create the github repository
---

Nowadays, having a version controlled repository on a universally accessible hosting solution like github or bitbucket is almost mandatory from day zero. If you don't have a strong requirment to use something else, just go for the github.

[2.1]: #21-choose-a-fitting-name
##### 2.1. Choose a fitting name
For the worse or better, the name of your repository actually affects its future. So don't just choose whatever.

[2.2]: #22-choose-privatepublic
##### 2.2. Choose private/public
Unless you strictly can't have the code in the public, for example it belongs to an entity which doesn't allow you to publish the codes, choose public. Don't be afraid that your code gets reviewed. Also if you don't want any outside contribution you can just write it down in your readme. Don't make it private just because it is a personal project.

[2.3]: #23-choose-a-license
##### 2.3. Choose a license
Open source is a virtue. If you're in doubt just go for the MIT license. If you can't decide, leave it but don't forget it. License actually matters.

[3]: #3-write-down-a-readme
3. Write down a README
---

http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
https://oncletom.io/talks/2014/okfestival/

README is the authoritative documentation to your code. The first thing anybody will see from your code is the README. And they will judge your code initialy by its README. But the README is not just for everybody else. By writing down your ideas before hand, you enable yourself to spot the faults in your own ideas.

[4]: #4-open-up-a-trello-board-for-your-project
4. Open up a [Trello](https://trello.com/) board for your project
---

Trello greatly helps you in managing your tasks, remembering your ideas, properly plan for the future, and all in all shape and advance your code in the right direction. Breakup your ideas into features. Then for each feature add a task to todos. If your tasks are too general, don't worry. You can just break them apart later on. However, note that your Trello tesks don't contain implementation details.

[5]: #5-write-tests-for-a-feature
5. Write tests for a feature
---

[5.1]: #51-choose-a-task-from-your-todos-deck-and-move-it-to-doing-deck
##### 5.1. Choose a task from your todos deck and move it to doing deck

[5.2]: #52-write-tests
##### 5.2. Write tests
Think about that when would you consider this feature as done. See if you could describe the feature as a set of tests in a sane way.

[6]: #6-try-to-pass-the-tests
##### 6. Try to pass the tests
Write just enough code to pass the tests. Then go back to step 5.
