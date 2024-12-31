# DIY Spotify Wrapped 
 Using my 2024 Spotify Data to create a visual in PBI.

***What is Spotify Wrapped?*** <br>
Spotify Wrapped is a feature available to Spotify premium users that tells the user about their listening history in the corresponding year.
The metrics are usually the same each year, such as your top 5 artists and songs of the year, how many minutes you have listened to, and your most played genre.

 ***Inspiration*** <br>
 I am an avid user of Spotify and I am always excited to see (and flex) my Spotify wrapped to my friends. 
 I thought it would be a cool idea to create my own version of Spotify wrapped using Power BI, as it is a tool that many employers use in the field in which I'm interested in.

***Goals*** <br>
Before starting this project, I wanted to know a few things about my listening history this year:
1. Which artists have you listened to the most this year? (could split this into 4 quarters (or a slider for the user to see) as my music listening changes a lot)
2. Which songs have you listened to the most this year? (could split this into 4 quarters (or a slider for the user to see) as my music listening changes a lot)
3. Most listened to album
4. What time of the day were you most active on Spotify?


***Progress*** <br>
Firstly, I wanted to create a visual that shows each song played in 2024 and how many minutes was streamed.
I created a new measure that converted the milliseconds played to minutes played using a DAX function.<br>
![image](https://github.com/user-attachments/assets/75e637c8-9533-4fb6-9cff-0ade2e6c266a) <br><br>

For goals 1, 2, and 3, I created 3 visuals to show my most played for the year<br>
![image](https://github.com/user-attachments/assets/3357d577-7858-4779-bd64-398526ddf30f)<br>
As you can see, my most listened to song of 2024 was TOUCH by Katseye, my most listened to artist was keshi, and my most listened to album was Requium.
And then I added a slicer so that the user can choose the time frame.<br>

![image](https://github.com/user-attachments/assets/a186ee87-90bc-4b8d-a0ea-d7376b1ab706)
<br>
As you can see, my most listened to song in Q1 2024 was Magnetic by ILLIT, my most listened to artist in Q1 2024 was LE SERRAFIM, and my most listened to album was SUPER REAL ME by ILLIT.<br><br>

For task 4, I needed to create two more columns, hour and day so I could put them into a heatmap. So I created these two columns using the following DAX functions:<br>
![image](https://github.com/user-attachments/assets/53ed0350-0179-493b-b743-eab78cff9f5f)<br>
![image](https://github.com/user-attachments/assets/476ebd33-c39d-4911-b448-60dc8207e7bc)<br><br>

I then created a heatmap of when I listened to music the most and a corresponding slider to adjust the timeframe.<br>
![image](https://github.com/user-attachments/assets/8c914142-c3f4-44ae-9e2f-37447857dfc6)<br>

As you can see, throughout 2024, I spent most of my Monday nights at 8pm listening to music.<br><br>

***Final Thoughts*** <br>
This was a pretty interesting project to make, I find it really cool how I can adjust the slider around so I can see my listening habits throughout the year. I also liked how each of the visuals are interacting and how I can play around with the project to try to deduce other information as well. Such as if I clicked on my most listened song of the year, TOUCH, it would show me the corresponding heatmap of when I listened to them! I might come back to this project every year and update the database with my new listening habits for the corresponding year! I was also able to get some hands on experience with PowerBI and was exposed to some DAX used within PowerBI as well!<br>

Here is the final visual: <br>
![image](https://github.com/user-attachments/assets/96d8ae0c-a693-4c63-a51d-33c988366fa5)








