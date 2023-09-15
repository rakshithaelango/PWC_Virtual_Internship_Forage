# PWC_Virtual_Internship_Forage

This repository is realted to the PWC Power Bi Virtual internship. As of now i have completed Task 1 And Task 2.

## Introduction to Task 1:

* Background information on task is:
  
    All in on digital transformation: Creating a stronger, nimbler, more resilient future!. We aim to build innovative technology solutions that differentiate us from our competitors and digitise the business. Part of that included a strategic decision to invest in upskilling programmes so our people could learn how to use digital tools for data visualisation as well as automation, data cleansing and more. If our people could use these tools to solve common problems, they’d help us become more efficient and growth-oriented now and more innovative later in Business Services and beyond. Now, employees are learning to build bots – over 2,400 have been created so far – to automate workflows. We continue to invest to make processes more intuitive using machine learning, PowerBI and eventually artificial intelligence (AI). These are key to working faster and solving problems differently for ourselves and our clients.
This is why you're here! Our Digital Accelerator programme is an internal chance that takes groups of our employees out of their day jobs and puts them through  trainings that teaches them skills in technology such as automation, machine learning, design thinking, and digital storytelling. PowerBI is an important part of it as visualising data helps to handle and understand clients.

We have to write blog of words to describe our Virtual internship to set the mood to start experience in Power BI.

## Introduction to Task 2:

* Background information on task is:

     The digital revolution and our fast-changing world requires a skills revolution. And it’s not just about the digital skills. The skills revolution is about helping people build their digital awareness, emotional intelligence and creativity to fully participate in the digital future workplace — and it needs to start now. At PwC, we are working with other organisations across the world, building on our work with clients and on upskilling our 276,000 people. Still, more must be done if we are to ensure everyone has the opportunity to learn, work and participate in the digital world. This is at the heart of our purpose. We are enabling employees who are motivated to further accelerate their skills to do so by offering them a “career pivot” to become what we call “Digital Accelerators”. Accelerators rapidly deepen their skills in digital specialties, such as data, automation, AI, and digital storytelling by learning a variety of self-service tools and coding languages and applying these skills across our business. We're happy you joined us, welcome to the team! Giulia is your manager and helps you through your upskilling journey in PowerBI - your step to become a true data jedi and Digital Accelerator. But wait no more, word spreads fast and an important client reached out to you to help him visualising their data. 
   
This Task 2: is about call centre. Claire is call centre manager at phonenow. She looking for transparency and insights into the data we have here at the call centre told to create great visualising data. Create a dashaboard in Power Bi for claire that reflects all relevant KP and metrices in the dataset.

Possible KPIs:

    * Overall customer satisfaction.
    
    * Overall calls answered/abandoned.
    
    * Calls by time.
    
    * Average speed of answer.
    
    * Agent’s performance quadrant -> average handle time (talk duration) vs calls answered.


## In-depth Dashboard Creations:

* Understanding  and importing data.
  
* Transforming Data and Using DAX measures.

    *    Created columns:
      
         Call Answered Call Answered = IF(Sheet1[Answered (Y/N)]="y",1,0)

         Call Rejected = IF(Sheet1[Answered (Y/N)]="n",1,0)

         Call Resolved = IF(Sheet1[Resolved] ="y",1,0)

         Call Unresolved = IF(Sheet1[Resolved] ="n",1,0)

    *    Average speed of answer = AVERAGE('Sheet1'[Speed of answer in seconds])
 
    *    Total calls = COUNTROWS('Sheet1')
 
    *    Overall satisfaction = AVERAGE(Sheet1[Satisfaction rating])
 
* Creating Dashboard:

       * Cards: Used to showcase Total calls and Avg speed of calls.

       * Fliters: Used to showcase Agent and Date.

       * Gauge: Used to showcase Overall statisfaction.

       * Donut Charts: Used to showcase Call Answered / Rejcted and Calls Resolved / Unresolved.

       * Area charts: Used to showcase Agent Satisfaction rating and Average Satisfaction rating by Topic.

       * Clustered column charts: Used to showcase Call Answered and Call Rejected by Topic and  Call Answered and Call Rejected by Agent.

       * Table: Used to showcase Agent / Total calls / Calls resolved / Calls answered.

 * Visualizing Dashboard: 

      ![Screenshot (397)](https://github.com/rakshithaelango/PWC_Virtual_Internship_Forage/assets/116090323/416e24e7-73df-4786-a582-15041b38304f)









