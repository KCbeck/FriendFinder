# Friend Finder - Node and Express Servers

### Overview

In this activity, we designed an app that is nearly the same as hot restaurant (#15) in express apps. we used path and express to handle the routing. WE sent the info to Heroku when done.



### Before You Begin

Our files were done exactly as trillogy said to do them the folder FriendFinder
 ```
  FriendFinder
    - .gitignore
    - app
      - data
        - friends.js
      - public
        - home.html
        - survey.html
      - routing
        - apiRoutes.js
        - htmlRoutes.js
    - node_modules
    - package.json
    - server.js
  ```

### Commits

We made multiple commits and constantly updated the github repositofy. 


### Instructions

I coded a survey that was effectively 10 of the below in a set Var.

```json
{
  "name":"Ahmed",
  "photo":"https://media.licdn.com/mpr/mpr/shrinknp_400_400/p/6/005/064/1bd/3435aa3.jpg",
  "scores":[
      5,
      1,
      4,
      4,
      5,
      1,
      2,
      5,
      4,
      1
    ]
}

2.My server file I did 
npm install
npm express
npm path
After some trouble shooting I got a App listening on PORT: 8080



3. Your `htmlRoutes.js` file should include two routes:  I copied the html from the original website using inspect then edited it to match me. 



4. Your `apiRoutes.js` file should contain two routes:

   the apiRoutes has two routes and has a res and a 

5. You should save your application's data inside of `app/data/friends.js` as an array of objects. Each of these objects should roughly follow the format below.

```json
{
  "name":"Ahmed",
  "photo":"https://media.licdn.com/mpr/mpr/shrinknp_400_400/p/6/005/064/1bd/3435aa3.jpg",
  "scores":[
      5,
      1,
      4,
      4,
      5,
      1,
      2,
      5,
      4,
      1
    ]
}
```

6. I have pseudo coded but am now working on doing a total 


Determine the user's most compatible friend using the following as a guide:

   * Convert each user's results into a simple array of numbers (ex: `[5, 1, 4, 4, 5, 1, 2, 5, 4, 1]`).
   * With that done, compare the difference between current user's scores against those from other users, question by question. Add up the differences to calculate the `totalDifference`.
     * Example:
       * User 1: `[5, 1, 4, 4, 5, 1, 2, 5, 4, 1]`
       * User 2: `[3, 2, 6, 4, 5, 1, 2, 5, 4, 1]`
       * Total Difference: **2 + 1 + 2 =** **_5_**
   * Remember to use the absolute value of the differences. Put another way: no negative solutions! Your app should calculate both `5-3` and `3-5` as `2`, and so on.
   * The closest match will be the user with the least amount of difference.

7. Once you've found the current user's most compatible friend, display the result as a modal pop-up.
   * The modal should display both the name and picture of the closest match.

### Reminder: Submission on BCS

Finally I submitted it to the bcs
