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

Through the creation of a returns DatFrame, it is noticeable through the cumulation plot, both the Strategy and Actual Returns data shows correlation through the fluctuations in returns. Thus, it is sensible to assume that both variables accuracy and precision and correlation is appropriate.

### Tune the Baseline Trading Algorithm

When slicing the data from 2015-07-06 10:45:00 to 2021-01-22 09:30:00, it provided useful information as to what impact increasing the window duration variables to. When changing the short window to 8 and the long window to 200, there is a slight change in the fluctuations of returns, with seemingly greater returns for both variables. However, as this is a small portion of the DataFrame, it is unreasonable to assume that the results follow the original data. However, through the presentation of the plots for both the tuned and original data, there is a distinguishable association between the data. 

### Evaluate a New Machine Learning Classifier

Using the LogisticRegression model, classification reports using the testing and training data:

Training Data:

<img width="449" alt="Screen Shot 2022-08-19 at 6 42 46 pm" src="https://user-images.githubusercontent.com/102783432/185580930-97795957-2955-46e9-95bc-fdbbf42c362c.png">

Testing Data:

<img width="449" alt="Screen Shot 2022-08-19 at 6 42 45 pm" src="https://user-images.githubusercontent.com/102783432/185581011-8eb4130d-4ee4-4e7b-a882-916f98851e55.png">

Although the classification report for either dataset had a poor accuracy, it provided a goodbasline to interpret the variables precision and total usefulness in determining if enhancing the existing trading signals with machine learning algorithms that can adapt to new data will improve the existing algorithmic trading systems and therefore maintaining the firm’s competitive advantage in the market. 

