# Payment-Date-Prediction


## Introduction

The B2B world operates differently from the B2C or C2C world. Businesses work with other businesses on credit. When a buyer business orders goods from the seller business, the seller business issues an invoice for the same.

This invoice for the goods contains various information like the details of the goods purchased and when it should be paid. This is known in accounting terminology as “Accounts Receivable”. The seller business interacts with various businesses and sells goods to all of them at various times.

Hence, the seller business needs to keep track of the total amount it owes from all the buyers. This involves keeping track of all invoices from all the buyers. Each invoice will have various important fields like a payment due date, invoice date, invoice amount, baseline date, etc.

## Problem Statement

The buyer business needs to clear its amount due before the due date. However, in real-world scenarios, the invoices are not always cleared, i.e., paid in full amount by the due date.

The date on which a customer clears the payment for an invoice is called the payment date.

Build a Machine Learning Model to predict the payment date of an invoice when it gets created in the system.

## Objectives

In the ideal world, the buyer business should pay back within the stipulated time (i.e., the Payment Term). However, in the real world, the buyer business seldom pays within their established time frame, and this is where the Accounts Receivable Department comes into the picture.

Every business consists of a dedicated Accounts Receivable Department to collect and track payment of invoices. It consists of an Accounts Receivable team that is responsible for:
- Collecting payments from customers for their past due invoices.
- Sending reminders and follow-ups to the customers for payments to be made.

## Methodology

We are provided with an invoices dataset which we need to parse and process. Then we are supposed to apply feature engineering techniques to extract patterns and identify features for efficient modeling.

An Invoices dataset that contains the past payment information and behavior of various buyers. Based on the previous payment patterns, the ML model needs to predict what will be the date a payment is made by the customer for an invoice.

The model also needs to predict which aging bucket the invoice falls into based on the predicted payment date.

## Conclusion

The dataset was processed and feature engineering processes were applied on it. Then it was applied on multiple machine learning models (Linear Regression, Decision Tree Regressor, XGB Regressor, Random Forest Regressor, Support Vector Regression) to find the best Mean Squared Error (MSE).

Finally, the XGB Regressor model was used to predict the payment date from the given dataset.

## Web Application

![image](https://github.com/user-attachments/assets/5ec8aef0-cd5f-4d71-aa28-24d9b7c4ab21)

