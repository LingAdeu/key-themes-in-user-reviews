![header](header.png)

# Investigating Key Themes in GoPay User Feedback: A Topic Modeling Approach

## About
Due to the massive amount of user reviews on GoPay app, manually analyzing feedback what the users talk about, indicating their satisfaction level about the app, e.g., transaction speed, payment status, or top-up issues, is challenging. This project addresses the analysis challenge by utilizing topic models, namely Latent Dirichlet Allocation (LDA), Latent Semantic Analysis (LSA), and Nonnegative Matrix Factorization (NMF), to extract underlying themes from the user app reviews. The first phase of this project, covering historical data analysis and predictive modeling using LDA (coherence score: 0.54), shows that all the majority of themes indicate positive perceptions about GoPay app. Some pain points were also identified in the historical data analysis that some users complained about inabilities to do transactions with and log in to the app. The next phase of this project will experiment the use of other algorithms and evaluate whether the coherence scores can be higher than the LDA performance score. Just for context, although coherence score of 0.54 is considered 'moderate' by the general standard, this coherence score is reasonably good in user reviews since reviews normally contain varying topics.

## Content
The predictive models are separated from each other because training one model is computationally intensive enough. Separating each model becomes a solution to decrease the computational source when executing the codes in each notebook.

    .
    ├── README.md
    ├── data
    │   └── review_gopay_newest_sort.csv
    ├── header.png
    ├── notebook
    │   ├── 01_Data-Analysis.ipynb
    │   ├── 02_Latent-Dirichlet-Allocation.ipynb
    │   ├── README.md
    └── requirements.txt

## Feedback
If there are any questions or suggestions for improvements, feel free to contact me here:

<a href="https://www.linkedin.com/in/adelia-januarto/" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/linkedin/default.svg" width="52" height="40" alt="linkedin logo"/>
  </a>
<a href="mailto:januartoadelia@gmail.com" target="_blank">
    <img src="https://raw.githubusercontent.com/maurodesouza/profile-readme-generator/master/src/assets/icons/social/gmail/default.svg"  width="52" height="40" alt="gmail logo"/>
  </a>