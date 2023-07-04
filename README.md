# Crime Rate Predictor - Unlock Safety: Reduce Crime Rate Together

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Crime Rate Predictor is an application that uses machine learning techniques to predict crime rates in 19 Indian metropolitan cities. The goal of this project is to assist law enforcement agencies in understanding crime patterns and allocating resources effectively to reduce crime rates and improve public safety.

## About the Application

Crime rate prediction has become an important tool for law enforcement agencies to help them better understand patterns of crime and anticipate where crime is likely to occur. By predicting future crime trends, law enforcement agencies can better allocate resources to areas that are likely to experience increases in criminal activity. This could lead to a decrease in crime overall, as well as an increase in public safety. Additionally, crime rate prediction can help police departments develop better strategies for responding to crime as it happens.

The dataset is prepared manually based on the publication available on the Indian National Crime Rate Bureau (NCRB) official website. This data provides statistics on crimes committed in 19 metropolitan cities during the year 2014 to 2021. With the help of this application, we can predict the crime rates for 10 different categories of crime that are likely to occur in 19 Indian metropolitan cities over the next few years. It includes statistics on 10 different categories of crime, including murder, kidnapping, crime against women, crime against children, crime committed by juveniles, crime against senior citizens, crime against SC, crime against ST, economic offences, and cybercrimes.

The system uses scikit-learn's Random Forest Regression model, which takes year, city name, and crime type data as inputs. Random Forest Regression is a type of an ensemble learning techniques that can be used to predict continuous values from a collection of data. It works by creating a large number of "decision trees" which each make a prediction about the target variable. Then it averages all the predictions to come up with a final prediction. This makes it more accurate than a single decision tree. The model predicts the crime rate with an accuracy of 93.20% on the testing dataset.
