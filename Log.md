<h1 align="center">#100DaysOfCode Log </h1>

<table  align="center">
  <tr>
    <td> Say Hi! 👋 : <a href="https://twitter.com/messages/compose?recipient_id=1444903302546673665&text=Hi! 👋" target="_blank"><img align="center" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/twitter/twitter-original.svg" alt="twitter"
          height="auto" width="30" /></a></td>
    <td> View Work : <a href="https://github.com/Bickeykr?tab=repositories" target="_blank">
        <img align="center" src="https://github.com/Bickeykr/Bickeykr/blob/main/github.png?raw=true" alt="Github" height="auto" width="30" />
      </a></td>
  </tr>
</table>
<hr>
<br>

<h2 align="center">

Day 1: Tuesday, July 19, 2022

</h2>
 
**Today's Progress**:  started working on a simple blog post website challenge for EJS practice, which will be a sever based website using node.js, express js and more.
Work done: Just created initial directories and files.

**Thoughts** : My internet is slow tonight I think.

**Link to tweet**
[Bickey kumar Day 1](https://twitter.com/Bickey_kr/status/1549425206883598336?s=20&t=RxOLx9pZ5MGS7oQjPeYy5g)

<hr>
<h2 align="center">
Day 2: Wednesday July, 21, 2022
</h2>   
**Today's Progress**:  Yesterday started working on a simple blog post website challenge for EJS practice, there is 21 challenges after completed all web site will be ready. I got to 12 today.

**Thoughts:** : I was feeling kinda tired, lonely, I may read mange after commiting this but it's fine We just need to keep going.

- Here is the a ss of how my app.js looks right now and as you can see I usually write comments for things of which I come across for the first time. <br> <br>
  <img  src="img\appjsSS.png"   height="500" style="float: left;" alt="app.js">

**Link to tweet:** [Bickey kumar Day 2](https://twitter.com/Bickey_kr/status/1549757379276771330?s=20&t=-r5sQ1KmBQS8IFf22oSCaw)

<hr>

<h2 align="center">
Day 3: Thursday July, 21, 2022
</h2>

**Today's Progress**: Completed 5 more challenge of the blog post website. It took me 4 hours of work to complete these 5 challenges, I think It's kinda slow but it's fine I had to google few concepts couple of times and go through documentations of it so, it's fine all that matters that I was there with it hunting for the solution.

**Thoughts:** Sometimes we feel lonely, so it's good to catch up with good old friends it really helps i did it yesterday myself we talked for 1hr40m to tell the truth he is having it rough now a days he had to stop his study due to financial problems and joined work for revenue and i tried to cheer his up. So, when ever you feel lonely try it, who knows it may work for you as well. <b>Thank you if you read this.</b>

**See the video preview of work:** [Here](https://twitter.com/Bickey_kr/status/1550136723631288321?s=20&t=BRgUbHcSkKnxYVXhTFk9tQ)

<hr>

<h2 align="center">
Day 4: Friday July, 22, 2022
</h2>

**Today's Progress**: Completed all 21 challenges and our blog website is ready. It will not be deployed since was only for practice.

- This is how it looks like now
  <br>
  <img  src=" img\Preview ofDaily Journal.png"   height="500" style="float: left;" alt="app.js">

[Here](https://twitter.com/Bickey_kr/status/1550512080117063682?s=20&t=Avs3XONo21_0qdRvWHcq7w) showed by composing 3 posts and viewed each real quick.

**Thoughts:** Life is good cheer up!
</b>

<hr>

<h2 align="center">
Day 5: Saturday July, 23, 2022
</h2>

**Today's Progress**: Moving forward to the full stack web development course I am attending, I jumped to new module which is about databases in which today we learnd about different types of databases programming language available and learned about SQL.

**Thoughts:** Jay Shree Krishna !

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1550881037168693248?s=20&t=sjdGO3RkgIOI4ELLI1j65Q)

<hr>

<h2 align="center">
Day 6: Sunday July, 24, 2022
</h2>

**Today's Progress**: Continuing learning databases and spent whole day just installing #MongoDB and still having issues.

**Thoughts:** Null

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1551238422374653952?s=20&t=gt9FXWMi2NTw-b5ARWcY5Q)

<hr>

<h2 align="center">
Day 7: Monday July, 25, 2022
</h2>

**Today's Progress**: Today Learned to perform CRUD with MongoDB.

**Thoughts:** MongoDB makes me feel i don't know anything.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1551579478459002880?s=20&t=E6y2XjPhJmAOFYamrFPuPg)

<hr>
<!-- ============================================================================================================================================================ -->
<h2 align="center">
Day 8: Tuesday July, 26, 2022
</h2>

**Today's Progress**: Taday Played with MongoDB Drivers created database and inserted documents in database using Drivers and got introduced with mongoose.

**Thoughts:** Null

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1551980437643591680?s=20&t=ghVnCNUxQaSteXYAKja23Q)

<hr>
<!-- ============================================================================================================================================================ -->
<h2 align="center">
Day 9: Wednesday July, 27, 2022
</h2>

**Today's Progress**: Learning mongoose, Today created a database connection, inserted docs basically performed CRUD MongoDB database using mongoose.

- here is a good one run the below code and check console what do I believe you are.

  <details>
  <summary><b>The code</b></summary>

  ```
  const mongoose = require("mongoose");

  main().catch((err) => console.log(err));

  async function main() {
    await mongoose.connect("mongodb://localhost:27017/youGood");

    const youSchema = new mongoose.Schema({
      discription: String,
    });

    const Person = mongoose.model("Person", youSchema);

    const you = new Person({
      discription:
        "You are the finest person i have ever encountered. @bickey_kr",
    });

    await you.save();

    Person.find(function (err, Person) {
      mongoose.connection.close();
      Person.forEach((item, i) => {
        console.log(i + ". " + item.discription);
      });
    });
  }

  }
  ```

  </details>

- If you decide to run the code make sure you have got the prerequisites ready to run the code (like installation of MongoDB and more).

**Thoughts:** I only studied for 2 hours today and I was supposed to do 5 hours but i don't regret it because when I was about to study my father called me for help in our shop. so I was there.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1552335635595157504?s=20&t=bXdft2M7SJEISlFmDINvhQ)

<hr>

<h2 align="center">
Day 10:  Thursday July, 28, 2022
</h2>

**Today's Progress**: Today got introduced with mongoose data validation and played it with few times on my fav playground vscode.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1552683217894850561?s=20&t=WNM95i-oqz18blppNKnX8Q)

<hr>

<h2 align="center">
Day 11: Friday July, 29, 2022
</h2>

**Today's Progress**: Today learning about Establishing Relationships and Embedding Documents using Mongoose.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1553034176865001473?s=20&t=WNM95i-oqz18blppNKnX8Q)

<hr>
<h2 align="center">
Day 12: Saturday July, 30, 2022
</h2>

**Today's Progress**: Today started building a simple "to do application" Which we have it own database and entered tasks will not disappear after restarting nodemon and will be putting all the learning of databases mongodb, mongoose to good use 👌

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1553405156217475073?s=20&t=WNM95i-oqz18blppNKnX8Q)

<hr>
<h2 align="center">
Day 12: Sunday July, 31, 2022
</h2>

**Today's Progress**: Today we managed to save entered task of
"todo application" in database collection using [@mongodb](https://github.com/mongodb) and mongoose and now task won't disappears when I refresh the server.

**Thoughts:** I mistakenly posted day12 two days in a row however the tweets and progress are different because these are two different days and I am doing the same here as well to keep both align.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1553786255346843653?s=20&t=175dbOmkrp0im4N7O2Ph1A)

<hr>
<h2 align="center">
Day 13: Monday August, 1, 2022
</h2>

**Today's Progress**: Almost there, the application is looking good, at the moment we can Add, Delete and Create a custom list.

Tools used to build: nodejs, express, ejs.

<img  src="img\todoApplicationWithDatabase.png"   height="500" style="float: left;" alt="app.js">

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1552683217894850561?s=20&t=WNM95i-oqz18blppNKnX8Q)

<hr>
<h2 align="center">
Day 14: Tuesday August, 2, 2022
</h2>

**Today's Progress**: Today finally completed the database work in the "Todo application" I was working on.

<img  src="img\ssOfCompletedDatabaseWorkTodoApplication.png"   height="500" style="float: left;" alt="app.js">

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1554507490082951169?s=20&t=105Lr2w0TcN5fPyMHhgrcA)

<hr>

<h2 align="center">
Day 15: Wednesday August, 3, 2022
</h2>

**Today's Progress**: Today finally completed the database work in the "Todo application" I was working on.

**Link to tweet:** Check out the tweet if you wish to see video which i posted of completed application
[Today's tweet](https://twitter.com/Bickey_kr/status/1554870430019727362?s=20&t=105Lr2w0TcN5fPyMHhgrcA)

<hr>

<h2 align="center">
Day 16: Thursday August, 4, 2022
</h2>

**Today's Progress**: learned a bit about MongoDB Atlas just enough the get a database connection for the deployed application. "basically got started with the free plan of Atlas" and deployed the "Todo Application" on Heroku.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1555241636073918464?s=20&t=tYURf11rc_9Bl7x_tn04OQ)

**Link to work:** [here](https://fierce-ocean-00362.herokuapp.com/)

<hr>

<h2 align="center">
Day 17: Friday August, 5, 2022
</h2>

**Today's Progress**: Worked with mongoose and upgraded the blog website shown [here](https://bit.ly/3BO0tPl), and gave this node application a database where all posts could be stored.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1555599133456494593?s=20&t=c4R6As1t9GjWBYbP13VCJA)

<hr>

<h2 align="center">
Day 18: Saturday August, 6, 2022
</h2>

**Today's Progress :** Got introduced to RESTful API
**Thoughts:** Today I was not really feeling like continuing for much longer than an hour of session,
Oh, I just want to eat and lay in bed and read manga all day and night currently reading the Vinland saga.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1555933598653419525?s=20&t=FEwpjvcy2cBl3mYic-SJww)

<hr>

<h2 align="center">
Day 19: Saturday August, 6, 2022
</h2>

**Today's Progress :** Got introduced to RESTful API

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1556313611215114240?s=20&t=z98kZCiFkUnyJQNUZOM3qA)
<details>
    <summary><b>media</b></summary><br>
    <img src="img\servercode.png" height="500" style="float: left;" alt="Server code">
  
  </details>

<hr><h2 align="center">
Day 20: Sunday August, 7, 2022
</h2>

**Today's Progress :**  Continuing learning RESLful APIs for which creating an API. Made use GET & POST methy.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1556688388383985664?s=20&t=Y2nZdQjUrr1V_Q0CVZXnPA)
 

<hr><h2 align="center">
Day 21: Monday August, 8, 2022
</h2>

**Today's Progress :**  After missing a day but back on track, I even tweeted about the missed day [here](https://bit.ly/3zMcH8C) and Continuing learning RESLful APIs for which creating an API. Completed POST method.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1557402504207278080?s=20&t=Y2nZdQjUrr1V_Q0CVZXnPA)
 

<hr><h2 align="center">
Day 22: Tuesday August, 9, 2022
</h2>

**Today's Progress :** Worked with 
@getpostman
 for testing RESLful APIs really excellent tool it makes work a lot easier & easy to use love it.  
but using 🖱️for everything is a pain, so I was wondering if there are keyboard shortcuts to navigate within postman for the desktop.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1557759399887716352?s=20&t=Y2nZdQjUrr1V_Q0CVZXnPA)
 

<hr><h2 align="center">
Day 23: Wednesday August, 10, 2022
</h2>

**Today's Progress :** Working on creating my own RESTful API, it is an API that allows users to interact with collections of articles.  the user can create new, view all, delete all & view one article with this API till now.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1558128410374725632?s=20&t=Y2nZdQjUrr1V_Q0CVZXnPA)
 

<hr><h2 align="center">
Day 24: Thursday August, 11, 2022
</h2>

**Today's Progress :** continue work on building RESTful API for practice and learning propose. 

**Thought:** Updating the 100DaysOfCode daily log on GitHub can be a pain, it has been 3 days last I  updated it, but today 16/08/2022 I am updating for all past 6 days.
Do you agree 🥲?

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1558486870576603136?s=20&t=Y2nZdQjUrr1V_Q0CVZXnPA)
 

<hr>
<h2 align="center">
Day 25: Friday August, 12, 2022
</h2>

**Today's Progress :** Got introduced to RESTful API

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1556313611215114240?s=20&t=z98kZCiFkUnyJQNUZOM3qA)
<details>
    <summary><b>media</b></summary><br>
    <img src="img\servercode.png" height="500" style="float: left;" alt="Server code">
  
  </details>

<hr>
<h2 align="center">
Day 26: Saturday August, 16, 2022
</h2>

**Today's Progress :** Today started learning about the "Authentication and security" of websites! 


**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1559555499783344131?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 

<hr>

<h2 align="center">
Day 27: Sunday August, 17, 2022
</h2>

**Today's Progress :** Working on a simple website where the user has to enter a username and password to access another page. This is part of learning "Authentication and security"!

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1560293993971195904?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 

<hr>
<h2 align="center">
Day 28: Monday August, 20, 2022
</h2>

**Today's Progress :** Studied for only an hour, and played with GitHub and git, remote repos, and local repos.

Hey Devs, I was wondering, 
Is it a good idea to push every project we work on GitHub?

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1561019463147061250?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 
<hr>
<h2 align="center">
Day 29: Tuesday August, 21, 2022
</h2>

**Today's Progress :** ➡️ Today: worked git and GitHub in order to push a local repo to remote! 

➡️ even though I knew git and GitHub faced multiple errors and had to Google the answer.

🌐 https://bit.ly/3pxuo76 repo I was working on still works remains!

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1561401678980456448?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 

<hr>
<h2 align="center">
Day 30: Wednesday August, 22, 2022
</h2>

**Today's Progress :**  Today: Revised git and GitHub Notes to recall what I studied and to find a command to delete a branch on the local repo.

🌐 https://bit.ly/3pxuo76 Fixed the issue with the repositary.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1562139795106648071?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 

<hr>
<h2 align="center">
Day 31: Thursday August, 23, 2022
</h2>

**Today's Progress :** I feel like I need to know more about GitHub and start contributing to the open source in various ways.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1562489471001452544?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 

<hr>
<h2 align="center">
Day 32: Saturday August, 25, 2022
</h2>

**Today's Progress :** 
Didn't write any lines of code today but learned how we can back up files! learned to use 
@googledrive
 and managed files.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1562862642481442816?s=20&t=LrfTzqm9noxqbnJxJex50Q)
 

<hr>
<h2 align="center">
Day 33: Friday August, 26, 2022
</h2>

**Today's Progress :** Paused Learning full stack web development and started learning C. 

To know why this change of events [here](https://twitter.com/Bickey_kr/status/1563120835480526848?s=20&t=LrfTzqm9noxqbnJxJex50Q)

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1563212117158686721?s=20&t=LrfTzqm9noxqbnJxJex50Q)

<hr>
<h2 align="center">
Day 34: Saturday August, 27, 2022
</h2>

**Today's Progress :** Updated this log repo and continuing learning C.  

To know why this change of events [here](https://twitter.com/Bickey_kr/status/1563120835480526848?s=20&t=LrfTzqm9noxqbnJxJex50Q)

 

<hr>
 <h2 align="center">
Day 35: Sunday August, 28, 2022
</h2>

**Today's Progress :** Completed setup for learning C programming learning time less than an hour.
**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1563934310737973249?s=20&t=HexE-Kz6zjTiJvmA_xzE7Q)
 

<hr>
 <h2 align="center">
Day 36: Tuesday August, 30, 2022
</h2>

**Today's Progress :** No coding today Agin!
**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1564665857883615232?s=20&t=lwatIia3asXI-lG0dtto1A)
 

<hr>
 <h2 align="center">
Day 36: Wednesday August, 31, 2022
</h2>

**Today's Progress :**   Continuing learning C! there is two 36 days because I didn't do any coding yesterday. 

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1565020956514365440?s=20&t=J3DnRcHsTmiReYtkqrVlfg)
 

<hr>
 <h2 align="center">
Day 37: Thursday September, 01, 2022
</h2>

**Today's Progress :** Learned about variable, datatype and constants in C.

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1562823749766115329?s=20&t=J6g1fJiMduqcYQRl1N7wQQ)
 

<hr>
 <h2 align="center">
Day 38: Saturday September, 03, 2022
</h2>

**Today's Progress :** #100DaysOfCode 
Learned how to input/output data in C. 

**Link to tweet:** [Today's tweet](https://twitter.com/Bickey_kr/status/1566116153058947072?s=20&t=oYDL78Zg8kqQxHfLSQ3Lsg)
 

<hr>

<!--
<!-- ============================================================================================================================================================

<h2 align="center">
Day ?: Thursday July, 21, 2022
</h2>
**Today's Progress**:
<div>
  <img src="#" height="500" style="float: left;" alt="Mobile Minutes Converter">
  <img src="#" style="float: left;" alt="Mobile Minutes Converter">
</div>

**Thoughts:**
**Link to tweet:** [MightyJoeW Day 3](https://twitter.com/MightyJoeW/status/827548443614859264)
**Link to work:** [Minutes to Hour Converter (Codepen link)](http://codepen.io/MightyJoeW/full/qRoeYy/)
<hr>

-->
<!--
<h2 align="center">
Day ?: Thursday July, 21, 2022
</h2>
**Today's Progress**:

**Thoughts:**
**Link to tweet:**
**Link to work:**
<hr> -->
