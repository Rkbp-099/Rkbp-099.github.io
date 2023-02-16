---
permalink: /markdown/
title: "Projects"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---
<br>

**Surveillance Alert System based on Image Captioning using Deep Learning Approaches**

In the field of image analytics, semantic segmentation can determine the objects in an image, but fails to explain the relationship between these objects. Automatic caption generation can help to identify these events and be used to alert users to take action. Our team tackled this challenge by implementing an Image Captioning system using CNN-LSTM architecture and compared results with GPT2-generated captions. The training dataset was from Kaggle and contained 8092 images from Flickr with 5 captions as the target label. To address the lack of surveillance-related images, we manually added 568 surveillance images and captions. The resulting Image Captioning model generated captions that were used to send alerts to stakeholders if the captions contained red-flag words.

[Code](https://github.com/sau97/Surveillance-Alert-System)
| [Medium Article](https://medium.com/@saurabh.arora_80184/image-captioning-based-surveillance-alert-system-6f8c81c4a18e)

---

**Enhaced Trip Advisor Recommendation System**

This was my final project during my Fall semester at UT Austin for my Analytics for Unstructured Data course. We scraped 4000 reviews and descriptions using Selenium off the Trip Advisor Website for 400 destinations across the globe. We calculated the similarity between the reviews and descriptions provided by the business owners/tripadvisor. Then we performed the sentiment analysis on the reviews and provided more accurate descriptions using topic modeling. The tools used included Selenium, spaCy, Vader, and NLTK.

[Code & Report](https://github.com/sau97/Trip-Advisor-Recommender-System)

---

**Trump and other Presidents: Speech Analysis**

For a group project in the Unstructured Data Analytics course at UT Austin's MS Business Analytics program, we analyzed the difference in former President Trump's speeches compared to other presidents using the Presidential Speech Archive as our dataset. We used NLP techniques such as SpaCy similarity analysis, Lift Analysis, polarity and subjectivity analysis, and topic modelling with LDA to draw insights on the uniqueness of Trump's language and messaging compared to other presidents. Our findings revealed that modern speeches tend to be more alike, but Trump's speeches were found to have a lot of information on specific, opinionated topics and to focus on nationalist, COVID-19, immigration, and terrorism, while other presidents focused on topics such as war, taxes and economy, crime, and space.

[Code](https://github.com/parthiv-borgohain/Trump-and-other-Presidents-Speech-Analysis)
| [Report](https://github.com/parthiv-borgohain/Trump-and-other-Presidents-Speech-Analysis/blob/main/Presentation%20Slides.pdf)

---

**Index Fund Using Integer Programming**

In this project, we designed an Index fund to track the NASDAQ-100 index using an integer program and a linear program to pick stocks and allocate weights respectively. The performance of the index fund was evaluated for different values of m and compared to the NASDAQ-100 index. The goal was to find a practical and cost-effective way to create an index fund that mirrors the broad market.

[Code](https://github.com/parthiv-borgohain/Index-Fund-Using-Integer-Programming/blob/main/Optimization%20Project%202%20-%20Parthiv%20Borgohain%20-%20Final.ipynb)
| [Report](https://github.com/parthiv-borgohain/Index-Fund-Using-Integer-Programming/blob/main/Optimization%201%20Project%202%20Report.pdf)

---

**Car Brands Consumer Perception Analysis**

In this project, we analyzed user-generated content from the Edmunds car review forum to understand consumer perceptions of car brands. We used natural language processing techniques and visualized the results with a Multidimensional Scaling plot. Our analysis revealed the top 10 car brands, the attributes associated with those brands, and the most desired brand from the discussions. The insights from this project can inform marketing strategies for car brands.

[Code & Report](https://github.com/parthiv-borgohain/Car-Brands-Consumer-Perception-Analysis)

---

**Capital Bikeshare Traffic Planning**

This project aimed to understand the demand for bike sharing services in the Washington, D.C region and how it is affected by the number of registered and casual users. Using trip data from Capital Bikeshare, we predicted the hourly ridership by employing various regression and tree-based models. Our analysis showed that XGBoost, a tree-based ensemble method, performed the best with an R-Square of 88.7%. Our findings revealed that the Hour of the Day was the most significant factor affecting both registered and casual riders, with temperature also having an impact on casual riders. Our recommendations for Capital Bikeshare include offering a weekend pass option and implementing dynamic pricing based on weather conditions to increase usage and optimize pricing. Our model provides valuable insights for planning and optimization.

[Code](https://github.com/parthiv-borgohain/Capital-Bikeshare-Traffic-Planning)
| [Report](https://github.com/parthiv-borgohain/Capital-Bikeshare-Traffic-Planning/blob/main/Capital_Bikeshare_ML_updated.pdf)

---

**Feature Selection Optimization**

This project aimed to compare the effectiveness of two methods for variable selection in Machine Learning algorithms. The first approach was Mixed Integer Quadratic Programming (MIQP) which is a direct variable selection method based on optimization of the Ordinary Least Squares linear regression. The second approach was Lasso Regression, an indirect method that performs regularization and feature selection implicitly. The results showed that MIQP provided more accurate results but took longer to run, while Lasso was quicker but with less accuracy. The choice between the two methods depends on the resources available and the size of the dataset. If the task requires maximum accuracy and the company has enough data points, MIQP is recommended. If the dataset is large, Lasso would be a better option. Both methods have a place in analysis, and the choice between them should be made based on individual circumstances.

[Code](https://github.com/parthiv-borgohain/Feature-Selection-Optimization/blob/main/Project-3.ipynb)
| [Report](https://github.com/parthiv-borgohain/Feature-Selection-Optimization/blob/main/Project%203%20-%20Report.pdf)

---

**NASA Near Earth Objects Analysis**

In this project, we used NASA's Near Earth Objects dataset to predict whether a certified asteroid would be hazardous to Earth by analyzing variables such as diameter, relative velocity, and more. Through exploratory analysis and machine learning techniques, we found that the absolute magnitude variable had the strongest relationship with the target variable. Our best performing model was Gradient Boosting with a test accuracy of 92.02%. The key takeaways from our analysis were that only 4 variables were used to predict the target variable, with the remaining variables being dropped before fitting the models. Our predictive model probably will not show significant improvement over the baseline model as the 4 variables did not prove to be strong predictors. As a next step, we plan to work with a larger dataset with a more balanced distribution of the target variable to potentially improve the model.

[Code](https://github.com/parthiv-borgohain/NASA-Near-Earth-Objects-Analysis)
| [Report](https://github.com/parthiv-borgohain/NASA-Near-Earth-Objects-Analysis/blob/main/Project%20Report.pdf)
| [Presentation](https://github.com/parthiv-borgohain/NASA-Near-Earth-Objects-Analysis/blob/main/Python%20Project.pdf)

---

**Marketing Budget Allocation**

This project involved using linear programming to allocate a 10 million USD marketing budget to 10 different channels, including Print, TV, SEO, AdWords, Facebook, LinkedIn, Instagram, Snapchat, Twitter, and Email. We had to ensure that no channel exceeded a budget of 3 million USD and that investments in Print and TV were not more than Facebook and Email. The total investment in social media platforms had to be twice the investment in SEO and AdWords. Our team used ROI calculations from two consulting firms and solved the linear program using Gurobi to come up with an optimal budget allocation strategy.

[Code](https://github.com/parthiv-borgohain/Marketing-Budget-Allocation/blob/main/Optimization_Project_I_Final.ipynb)
| [Report](https://github.com/parthiv-borgohain/Marketing-Budget-Allocation/blob/main/Optimization%20Project%201%20Report.pdf)

