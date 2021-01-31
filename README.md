# Heroku Deploy

Deploying to Heroku can be pretty annoying, confusing, and time-consuming. I've put this together using the instructions I was taught. This ALSO serves to implement database usage, so if you want to stop after initially creating a successful upload, that's cool too! It's **PRACTICALLY** fool proof, I promise!!
**
(Assuming you are using: NODE, PG, PostgresQL, DBeaver)
**
Here we go!
**

**Step 1:**
* Have a computer. Alright, I'm kidding.... here's the **real** step one. 
> * Open up your terminal. (I'll be using GITBash on Windows)
> * Heroku has some benefits when using certain libraries. In this case we're using PG and that automatically provisions a Postgres DB...score!
> * In your terminal type in: ```heroku create```
> * This is what it will look like after you execute:
![1](./images/1.png)

**2:**
* Now let's run ```git push heroku main``` (our initial push into Heroku)
![2](./images/2.png)

**3:**
* Now to provision Postgres: ```heroku addons:create heroku-postgresql:hobby-dev```
(this now tells us the db has been created and it's empty. Awesome. I'm glad you're keeping up!)
![3](./images/3.png)

**4:**
![4](./images/4.png)

**5:**
![5](./images/5.png)

**6:**
![6](./images/6.png)

**7:**
![7](./images/7.png)

**8:**
![8](./images/8.png)

**9:**
![9](./images/9.png)

**10:**
![10](./images/10.png)

**11:**
![11](./images/11.png)

**12:**
![12](./images/12.png)

**13:**
![13](./images/13.png)



# DATABASE SETUP


**1:**
![1](./images/db/1.png)

**2:**
![2](./images/db/2.png)

**3:**
![3](./images/db/3.png)

**4:**
![4](./images/db/4.png)

**5:**
![5](./images/db/5.png)

**6:**
![6](./images/db/6.png)

**7:**
![7](./images/db/7.png)

**8:**
![8](./images/db/8.png)

**9:**
![9](./images/db/9.png)

**10:**
![10](./images/db/10.png)

**11:**
![11](./images/db/11.png)

**12:**
![12](./images/db/12.png)




