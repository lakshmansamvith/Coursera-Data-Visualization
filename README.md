# Data Visualization for Coursera Dataset provided on Kaggle
Coursera has more than 30000 active courses as of 2020, and a lot of people keep taking up courses over time. This notebook helps in visualizing what are the Top 5 courses that students enroll to, to show how many courses belong to different rating scales, a pie chart to visualize courses seggregated according to difficulty level and more.  

<ol>
<li>Obtaining Dataset and Preprocessing</li>
<li>Using Regular Expressions to establish essential numerical values</li>
<li>Plotting Bar Graph For Top 5 Courses By No of Course Students Enrolled </li>
<li>Countplot for Courses of different ratings </li>
<li>PieChart for percentage of courses according to course_difficulty</li>
<li>PieChart for % of Course_Certification_Types</li>
<li> Barplot for showing Top 5 Institutes which provide most of the courses on Coursera</li>  
</ol>

## 1 Obtaining Dataset
Here is the link to the Kaggle Dataset I used for this notebook. 
[Kaggle Dataset](https://www.kaggle.com/siddharthm1698/coursera-course-dataset)

Like I mentioned Coursera has more than 3000 courses, out of which this dataset has 891 course details.</br> 
This dataset didn't need much preprocessing because none of the values are null. 

         
## 2 Using Regular Expressions to establish essential numerical values
Using Regular Expressions I converted the number of students enrolled columns(string) into an integer column. 

## 3 Plotting Bar Graph For Top 5 Courses By No of Course Students Enrolled 
I used Seaborn for making a Barplot for Top 5 courses(in terms of number of students who enrolled)
![Most Widely Browsed Course Bar plot](https://github.com/lakshmansamvith/Coursera-Data-Visualization/blob/master/Screenshots/Screenshot%20(146).png)

From this it is clearly depicted that Machine Learning By Stanford University is the most widely enrolled course.
   
 ## 4 Countplot for Courses of different ratings
 I used Seaborn for making a countplot for courses based on different ratings This bar plot tells us about how many courses come into which category of rating
 ![Rating Countplot](https://github.com/lakshmansamvith/Coursera-Data-Visualization/blob/master/Screenshots/Screenshot%20(148).png)       
 We can see that most of the courses have a high rating, it is highly unlikely that Coursera keeps a course with less rating as an       active course. 
 
 
 ## 5 PieChart for depicting how much of percent of courses belong to the existing 4 categories
 I used Matplotlib for making a pie chart based on four existing categoires. <br/>
 Beginner<br/>
 Intermediate<br/>
 Advanced<br/>
 Mixed<br/>
 ![Category Pie chart](https://github.com/lakshmansamvith/Coursera-Data-Visualization/blob/master/Screenshots/Screenshot%20(149).png)
 
More than 75% of the courses fall into Beginner and Intermediate categories, this shows us that Coursers emphasises a lot on beginners. 
 
 
 ## 6  PieChart for depicting how much of percent of courses fall into Course, Specialization, Professional Certificate
   I used Matplotlib for making a pie chart based on three existing categoires mentioned above. 
   ![Course/Speciliazation/Professional Certificate](https://github.com/lakshmansamvith/Coursera-Data-Visualization/blob/master/Screenshots/Screenshot%20(150).png)
   
   Most of them fall into single courses. 
       
     
