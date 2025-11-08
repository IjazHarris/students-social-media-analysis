# 🎓 Students’ Social Media Addiction Analysis (Excel Project)

This project explores how students’ **social media habits**, **sleep duration**, and **mental health** relate to their **academic performance**.  
All analysis was conducted in **Microsoft Excel**, using PivotTables, charts, and correlation tests.

## 📁 Project Structure

data/ → contains the raw dataset (Students Social Media Addiction.csv)
analysis/ → Excel workbook with all question-by-question analyses
visuals/ → exported charts and dashboards for presentation
README.md → project overview and summary


## 🧠 Objectives
This project aims to:
- Understand how **sleep, mental health, and social media usage** interact  
- Compare **usage patterns** across countries and genders  
- Explore **academic performance differences** among students with different habits  
- Present the findings in clear, visual formats

- ## 🔍 Dataset Overview
The dataset includes student responses to social media use and lifestyle questions.

| Column | Description |
|---------|--------------|
| Student_ID | Unique identifier |
| Gender | Male / Female |
| Age | Numeric (years) |
| Country | Student’s country of residence |
| Daily_Usage_hrs | Average daily time spent on social media |
| Sleep_Hours | Average sleep per night |
| Mental_Health_Score | Well-being rating (1–100) |
| Most_Used_Platform | Social media app used most often |
| Academic_Performance | Yes / No – if student reports good performance |

## 🧩 Key Questions & Findings

| # | Question | 
|---|-----------|
|1. | Does higher social media usage correlate with lower sleep hours?
<img width="666" height="380" alt="image" src="https://github.com/user-attachments/assets/cb46ffb5-c06b-4d77-a3df-cf6a9cbb2e65" />
📉 The scatterplot shows a downward trend → students who use social media more hours per day tend to sleep less.

| #  | Question |
|--- |-----------|
| 2. | What is the highest addiction score by platform?
<img width="817" height="425" alt="image" src="https://github.com/user-attachments/assets/d7ac4a5a-3fc7-47f8-8d61-1c0b3355832b" />


**Highest Median Addiction:** Instagram and Snapchat show the highest median addiction levels, with the line inside the box around 8.0.


**Most Variable Addiction:** TikTok, YouTube, and Facebook show a similar high degree of variability (spread of the box and whiskers), with an Interquartile Range (IQR, the height of the box) of about 3.0 or more, indicating a wide range of typical responses. Instagram also shows high variability.


**Lowest Addiction (with data)**: LinkedIn shows the lowest median addiction level (around 5.5) and the smallest range/variability among the platforms with a complete box plot.


**Low Data/High Skew:** Platforms like LINE, KakaoTalk, and Vkontakte have minimal data points shown (only an 'X' or a few points), suggesting either low usage in the surveyed group or that the data distribution did not allow for a full box plot to be drawn. WeChat has a median around 6.0 and relatively low variability.


**Outliers:** Several platforms, including TikTok, YouTube, Facebook, and LinkedIn, show outliers (individual dots below the lower whisker), indicating some users reported significantly lower addiction levels than the majority.


Overall, the data suggests that Instagram, Snapchat, and TikTok are associated with the highest addiction levels among the surveyed social media applications.


| #  | Question |
|--- |-----------|
| 3. |Does social media usage affect academic performance differently across academic levels?
<img width="801" height="310" alt="image" src="https://github.com/user-attachments/assets/9ba30ff6-f4ac-4dcb-bc7b-4b065f272218" />


**High School Level** The "Yes" response for High School students is the highest among all groups, averaging approximately $5.8$. This indicates the strongest perceived impact of social media on academic performance at this level.The gap between the "Yes" ($5.8$) and "No" (approximately $3.5$) responses is the largest, emphasizing the dominant perception of an effect.


**Undergraduate Level** The "Yes" average is approximately $5.6$, which is slightly lower than the High School level but still very high.The "No" average is approximately $3.8$, which is the highest "No" average across all groups. This suggests that a slightly larger proportion of undergraduates, relative to the other groups, believe social media does not affect academic performance.


**Graduate Level** The "Yes" average is the lowest among all three groups, at approximately $5.4$.The "No" average is approximately $3.7$, placing it between High School and Undergraduate.The narrowest gap between the "Yes" and "No" responses is observed at the Graduate level, implying the most balanced view (though still leaning heavily towards "Yes") on social media's effect.


| #  | Question |
|--- |-----------|
| 4. | Does sleep duration affect mental health?

<img width="801" height="292" alt="image" src="https://github.com/user-attachments/assets/8b2f46e3-11a1-4d43-ba6c-8c3857e65caa" />


**Finding:**There is a strong positive relationship between students’ average sleep hours and their mental health scores (R² = 0.50) or Trendline moves upwards


**Interpretation:**This suggests that roughly half of the variation in mental health among students can be explained by how much they sleep. Students who get more sleep generally report higher mental health scores.


| #  | Question |
|--- |-----------|
| 5. | Does sleep duration affect mental health?

<img width="659" height="332" alt="image" src="https://github.com/user-attachments/assets/4e2a23df-55ff-4d35-b6ea-fc63a816f929" />


Males spent an average of 4.8 hours daily on social media compared to 5.0 hours for females, indicating slightly higher usage.However, both groups showed similar addiction scores (~7 out of 10), suggesting the degree of addiction does not differ significantly by gender.

| #  | Question |
|--- |-----------|
| 6. | Does the average level of social conflict differ depending on relationship status?
<img width="718" height="392" alt="image" src="https://github.com/user-attachments/assets/48c67b5d-b6df-478d-b780-b8f52bb9431e" />

Students who are in a complicated relationship reported the highest social conflict scores (avg = 3:03), followed by single students (2.90), while  students who are in a relationship reported the lowest (2.76)

Though there's some differences, the conflict score is rather low which indicates that the  sample does not consider social media to be conflicting to their relationship

| #  | Question |
|--- |-----------|
| 7. | Does daily social media use affect academic performance?



<img width="578" height="31" alt="image" src="https://github.com/user-attachments/assets/53a6695d-bbea-4e94-89c3-5f919c48d420" />


Based on the pivot table, more students said yes. So heavier usage is linked with poorer performance.

## 💡 Conclusions
- Balancing social media use is critical for students’ mental and academic well-being.
  
- Healthy sleep patterns contribute to better focus and higher performance.
  
- Social media awareness programs could be tailored to regional and gender-based trends.





