![header](header.png)

# Investigating Key Themes in GoPay User Feedback: A Topic Modeling Approach

## About
The increasing volume of user reviews on the GoPay app presents a challenge for the Product Managers in understanding user satisfaction and concerns. Manually analyzing reviews to extract insights such as transaction speed, payment status, or top-up issues is both labor-intensive and inefficient. This project aimed to automate the review analysis using quantitative data analysis and topic modeling to uncover key information in user feedback.

Quantitative analysis revealed important patterns in user satisfaction based on Customer Satisfaction (CSAT) scores submitted with Play Store reviews. It was observed that most users were satisfied, with the majority giving the app a rating of 5. Temporal analysis showed that user satisfaction scores were initially low but improved after three months, stabilizing above 4, indicating consistent satisfaction over time. Additionally, app version analysis pointed to lower ratings in early releases, likely due to bugs that frustrated users, a finding that corroborated the temporal trends. The content analysis revealed that shorter, positive reviews, often containing words like *mantap* (*amazing*), were common among high ratings, while low-rated reviews frequently referenced usability issues such as transactions and login problems.

The project also applied Latent Dirichlet Allocation (LDA) topic modeling, which identified seven key themes from the reviews, including app features, praise, ease of transaction, and login issues. The dominant topic was praise-related reviews, aligning with the high satisfaction scores noted in the quantitative analysis. Although the LDA coherence score of 0.54 is considered moderate, it is acceptable given the varied nature of user reviews. Notably, the cost-benefit analysis demonstrated that automating this review analysis process is 7.3 times more cost-efficient than manual approaches.

As a next step, the project will explore other topic modeling algorithms to improve the extraction of themes from user feedback and potentially enhance the coherence scores for more accurate topic generation.

## Folder Organization
The predictive models are separated from each other because training one model is computationally intensive enough. To manage the computational resource when executing the codes in each notebook, I separate different models and data analysis into several Jupyter notebooks.

    .
    ├── README.md                                 <- Top-level README 
    ├── data
    │   └── review_gopay_newest_sort.csv          <- Raw dataset
    ├── model
    │   └── lda_model.pkl                         <- LDA model
    ├── notebook
    │   ├── 01_Data-Analysis.ipynb                <- Introduction & Data Analysis
    │   ├── 02_Latent-Dirichlet-Allocation.ipynb  <- Topic modeling with LDA
    └── requirements.txt                          <- File for reproducing env

>[!important]
> Some data visualization outputs cannot be displayed properly, e.g., color map and interactivity, when reading the notebook directly on GitHub. For better experience in reading the Jupyter notebooks on which I carried out the analysis and built predictive models in, please use the following links: 
> - [Data analysis notebook](https://nbviewer.org/github/LingAdeu/key-themes-in-user-reviews/blob/main/notebook/01_Data-Analysis.ipynb)
> - [LDA notebook](https://nbviewer.org/github/LingAdeu/key-themes-in-user-reviews/blob/main/notebook/02_Latent-Dirichlet-Allocation.ipynb)
> - NMF notebook (soon)

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>