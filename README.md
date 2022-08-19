# Module_14

## Background

Assuming the role of a financial advisor at one of the top five financial advisory firms in the world. The advisor's firm constantly competes with the other major firms to manage and automatically trade assets in a highly dynamic environment. In recent years, the firm has heavily profited by using computer algorithms that can buy and sell faster than human traders.

The speed of these transactions gave the firm a competitive advantage early on. But, people still need to specifically program these systems, which limits their ability to adapt to new data. Therefore, the advisor will plan to improve the existing algorithmic trading systems and maintain the firm’s competitive advantage in the market. To do so, enhance the existing trading signals with machine learning algorithms that can adapt to new data.

## What You're Creating

Combining ythe new algorithmic trading skills with the existing skills in financial Python programming and machine learning to create an algorithmic trading bot that learns and adapts to new data and evolving markets.

## Jupyter Notebook Contents:

- Implement an algorithmic trading strategy that uses machine learning to automate the trade decisions.
- Adjust the input parameters to optimise the trading algorithm.
- Train a new machine learning model and compare its performance to that of a baseline model.
- As part of the README.md file in the GitHub repository, create a report that compares the performance of the machine learning models based on the trading predictions that each makes and the resulting cumulative strategy returns.

## Instructions

#### Establish a Baseline Performance
#### Tune the Baseline Trading Algorithm
#### Evaluate a New Machine Learning Classifier
#### Create an Evaluation Report

# Evaluation Report

### Establish a Baseline Performance

Through the creation of a returns DatFrame, it is noticeable through the cumulation plot (shown below), both the Strategy and Actual Returns data shows correlation through the fluctuations in returns. Thus, it is sensible to assume that both variables accuracy and precision and correlation is appropriate.

<img width="384" alt="Screen Shot 2022-08-19 at 6 48 55 pm" src="https://user-images.githubusercontent.com/102783432/185582002-dd2afa02-9d22-4f8b-ac9f-7f6030b7a6ea.png">

### Tune the Baseline Trading Algorithm

When slicing the data from 2015-07-06 10:45:00 to 2021-01-22 09:30:00, it provided useful information as to what impact increasing the window duration variables to. When changing the SMA windows to 8 and 200 respectively, it provided evidence to show that it performed better than the baseline model, with greater correlation between the variables than that of the original.In addition, through the presentation of the plots for both the tuned and original data, there is a distinguishable association between the data. 

<img width="410" alt="Screen Shot 2022-08-19 at 6 50 03 pm" src="https://user-images.githubusercontent.com/102783432/185582154-b7a0cc57-e797-4596-8adc-6244e02378b8.png">

### Evaluate a New Machine Learning Classifier

Using the LogisticRegression model, classification reports using the testing and training data:

Training Data:

<img width="449" alt="Screen Shot 2022-08-19 at 6 42 46 pm" src="https://user-images.githubusercontent.com/102783432/185580930-97795957-2955-46e9-95bc-fdbbf42c362c.png">

Testing Data:

<img width="449" alt="Screen Shot 2022-08-19 at 6 42 45 pm" src="https://user-images.githubusercontent.com/102783432/185581011-8eb4130d-4ee4-4e7b-a882-916f98851e55.png">

Although the classification report for either dataset had a poor accuracy, it provided a goodbasline to interpret the variables precision and total usefulness in determining if enhancing the existing trading signals with machine learning algorithms that can adapt to new data will improve the existing algorithmic trading systems and therefore maintaining the firm’s competitive advantage in the market. Therefore, using the information and findings presented, the new model performed worse than the provided baseline, with greater difference in returns between the two variables was potrayed in the plot. Therefore, providing less correlation and accuracy when comparing the two models. 

<img width="399" alt="Screen Shot 2022-08-19 at 6 56 26 pm" src="https://user-images.githubusercontent.com/102783432/185583515-61bb5350-2710-4a0f-8e70-0db22b0fed14.png">

Thus, from the findings gathered, it is appropriate to suggest that the tuned algorithmic trading dataset, provided a better model than both the baseline and the classifier model. This is assumed, due to the difference in correlation of the variables each model provides, although very similar in presentation and fluctuations, it is observed that the tuned model showed greater similarity of the Strategy and Actual Returns. 

