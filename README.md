# Naive Bayes from Scratch in Python

[![Build Status](https://travis-ci.org/gbroques/naive-bayes.svg?branch=master)](https://travis-ci.org/gbroques/naive-bayes)

A custom implementation of a Naive Bayes Classifier written from scratch in Python 3.

[![Bayes Theorem](bayes-theorem.png)](http://www.saedsayad.com/naive_bayesian.htm)

From [Wikipedia](https://en.wikipedia.org/wiki/Naive_Bayes_classifier):

> Dalam Machine learning, pengklasifikasi Bayes naive adalah keluarga pengklasifikasi probabilistik sederhana berdasarkan penerapan teorema Bayes dengan asumsi independensi yang kuat (Naive) di antara fitur-fiturnya..

## Dataset

#### Loan Defaulters

| Home Owner | Marital Status | Annual Income | Defaulted Borrower |
| ---------- | -------------- | ------------- | ------------------ |
| Yes        | Single         | $125,000      | No                 |
| No         | Married        | $100,000      | No                 |
| No         | Single         | $70,000       | No                 |
| Yes        | Married        | $120,000      | No                 |
| No         | Divorced       | $95,000       | Yes                |
| No         | Married        | $60,000       | No                 |
| Yes        | Divorced       | $220,000      | No                 |
| No         | Single         | $85,000       | Yes                |
| No         | Married        | $75,000       | No                 |
| No         | Single         | $90,000       | Yes                |

**Source:** *Introduction to Data Mining* (1st Edition) by Pang-Ning Tan

Figure 5.9, Page 230

## How to Run
Jalankan dengan Python 3 atau yg lainya.

`python main`
