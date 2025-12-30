![causeforapplause](https://github.com/user-attachments/assets/3a2435e2-ad65-4a93-9e3c-61f4170bc45e)


# 🔭 Features:

- Automated Data Gathering, Updating and Processing
- Applause Categorical Timing and Frequency
- Interactive Dashboard 
- Statistical Modelling  
- Topic Clustering  
- Sentiment Analysis


          
# 🔩 Technologies:

-  Google Sheets
-  Python/pyAudio/Beautifulsoup/Pandas/R
-  Power Bi 
-  DAX
-  SQL



# ♟️ The Process:
I wanted to create something that could help answer the why and when people applaud so I began research on political speeches throughout the western world. Initially I recorded sentiments, applause length, pause before applause, but this took way too long to complete thus I built my Applause Bot by developing an Ai Machine Learning program within Python leveraging pyaudio, Beautifulsoup, training it on my library of pre-recorded applauses so that it knew what to listen out for, while also loading it with my pre researched categories to ensure the causes for applauses are recorded automatically along with the timing.


# 👁️‍🗨️ Insights:
- We can see speeches are rarely ended on attacks
- Signaling Shared Values takes a majority hold on frequency, but comes in 2nd on length in seconds 
- Shared Values are spread throughout the speeches from start to middle to end
- Where as attacks are primarily clustered towards the middle and late start
- Recognition of constituents is 2nd but this may be skewed by the recent ending on the US government shutdown

# 🎬 Preview:

<img width="1311" height="737" alt="Comp Disp" src="https://github.com/user-attachments/assets/8873085a-71b4-4b51-8bf5-8f35d2a1722a" />

https://github.com/user-attachments/assets/f5db8118-6613-4dd4-b193-49fafa32280b

https://github.com/user-attachments/assets/3666f9cf-1aa2-404a-8281-fc841b400e48

![Data Relations](https://github.com/user-attachments/assets/ceae3a18-bd68-4302-98d4-f8037878794b)

# 🗳️ Lessons and Improvements:

- I needed a category attribute number because otherwise it would not allow me to order them appropriately for the spread graph, it seems Power Bi has a lot of difficulty using categories that are only a text type when placed on an axis

- Given that this is a contemporary look at causes for applauses the data makes sense even if the US skewers the set

- Different time lengths of speeches are currently skewing the data, I am considering only selecting speeches of a similar length to fix this

- The applause bot (code snippit below) cannot yet identify categories behind the applause, it can only detect moments and lengths of applause



<img width="980" height="947" alt="Applause ML" src="https://github.com/user-attachments/assets/a7510d0b-f739-488c-baed-53958f7c7609" />


