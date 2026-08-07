# Project Methodology

## 1. Problem Definition

Digital payment systems are increasingly exposed to evolving fraud patterns. Traditional rule-based detection can struggle when fraudulent behaviour changes over time.

This project explores an adaptive fraud-protection approach that combines transaction analysis, behavioural indicators, machine-learning classification and risk-based decision-making.

## 2. Research Context

The original research focuses on the rapidly digitalised payment ecosystem, with particular consideration of contactless payment in the United Kingdom.

The technical prototype uses a publicly available credit-card transaction dataset for experimental machine-learning analysis.

The dataset is therefore treated as an experimental proxy and does not represent live UK contactless-payment transactions.

## 3. Proposed Approach

The proposed fraud-protection workflow consists of:

1. Transaction data collection
2. Data preprocessing
3. Exploratory analysis
4. Feature analysis
5. Fraud classification
6. Model evaluation
7. Risk assessment
8. Adaptive authorization

## 4. Machine Learning

The implementation will investigate supervised machine-learning approaches for distinguishing legitimate transactions from potentially fraudulent transactions.

The models will be evaluated using security-relevant performance measures rather than relying solely on overall accuracy.

Key evaluation measures include:

- Precision
- Recall
- F1-score
- Confusion matrix
- False-positive rate
- False-negative behaviour

## 5. Adaptive Risk Decision

The eventual prototype will investigate how model predictions can contribute to a risk-based authorization process.

Conceptually:

Low risk → Approve

Medium risk → Additional verification

High risk → Block or escalate for investigation

The specific thresholds will be determined during implementation and evaluation rather than assumed in advance.

## 6. Security Considerations

The project will consider the security implications of:

- False positives
- False negatives
- Class imbalance
- Evolving fraud behaviour
- Model performance
- Risk-based authorization
- Potential operational deployment challenges

## 7. Implementation Status

This repository is being developed as an independent technical implementation of the research concept.

The implementation, experiments and results will be documented progressively as the project is developed.
