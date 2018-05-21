# Grammarly Analytics the Messy Way
To review my progress with Grammarly, I needed to extract my Grammarly stats from the emails they send each week.  Grammarly does not have the data in the "Your Weekly Progress Report" email available on its website or in the Mac Desktop app.

In the "Your Weekly Progress Report" email, Grammarly sends you stats which compare you to other users and give you a week by week bar chart for the past four weeks (the bar's value is unlabelled). 

I used the Gmail API to extract the emails and Pandas to clean and filter the data. It's pretty messy... At the end of my script, I get a few charts that show my progress over time.

This code will work for others, but you will have to modify it to match your Grammarly usage, how many emails you have got, and any updates to Grammarly's email templates. 

Conclusion
I wanted to see these stats for a long time. I created this script as a learning exercise. I am sure someone could make it prettier. 