# Prompt Engineering Projects

This repository contains three projects based on Prompt Engineering. These projects demonstrate how AI prompts can classify customer reviews and customer queries into predefined categories.

---

# 1. Sentiment Analysis Using Prompt Engineering

## Problem Statement

An online shopping company wants to analyze customer reviews automatically to understand customer satisfaction. The task is to design a prompt that identifies the sentiment expressed in a customer review.

Classify each review into one of three categories based on the customer's overall sentiment.

## Input

A customer review in natural language.

## Output

A single word representing the sentiment.

## Allowed Outputs

- Positive
- Negative
- Neutral

## Prompt

You are a sentiment analysis assistant.

Analyze the given customer review and classify its overall sentiment into exactly ONE of the following categories:

Positive, Negative, Neutral.

Rules:

1. Understand the overall opinion expressed in the review.
2. Select only one appropriate sentiment category.
3. Choose Positive for reviews expressing satisfaction or happiness.
4. Choose Negative for reviews expressing dissatisfaction or complaints.
5. Choose Neutral for reviews that express neither positive nor negative feelings.
6. Output only the sentiment category.
7. Do not provide explanations, punctuation, or additional text.

## Test Cases

| Customer Review | Expected Output |
|---|---|
| The product is excellent, and I love its quality. | Positive |
| The delivery was late, and the product was damaged. | Negative |
| The product arrived yesterday. | Neutral |
| The customer support team was extremely helpful. | Positive |
| The product is not worth the money. | Negative |
| The package contained two items. | Neutral |
| The phone is good, but the battery life is terrible. | Negative |

## Conclusion

Prompt engineering helps analyze customer reviews automatically by identifying their overall sentiment and classifying them as Positive, Negative, or Neutral.

---

# 2. Customer Query Urgency Classification Using Prompt Engineering

## Problem Statement

A customer support company receives thousands of queries daily. To prioritize customer requests, the company wants an AI system that identifies the urgency level of each query.

The task is to design an effective prompt that analyzes a customer query and classifies its urgency.

## Input

A customer query in natural language.

## Output

A single word representing the urgency level.

## Allowed Outputs

- High
- Medium
- Low

## Prompt

You are a customer query urgency classification assistant.

Analyze the given customer query and classify its urgency into exactly ONE of the following categories:

High, Medium, Low.

Rules:

1. Understand the customer's problem and its urgency.
2. Select only one appropriate urgency level.
3. Choose High for critical or time-sensitive issues that require immediate attention.
4. Choose Medium for issues that need attention but are not immediately critical.
5. Choose Low for general questions or non-urgent requests.
6. Output only the urgency level.
7. Do not provide explanations, punctuation, or additional text.

## Test Cases

| Customer Query | Expected Output |
|---|---|
| My bank account has been hacked, and money is being stolen. | High |
| My internet has been down for the entire day, affecting my work. | High |
| I haven't received my refund for the last seven days. | Medium |
| Can you tell me how to update my profile picture? | Low |
| I need to change my delivery address for an order arriving tomorrow. | High |
| I would like to know about your available subscription plans. | Low |
| I lost access to my account and cannot complete an urgent payment. | High |

## Conclusion

Prompt engineering helps automate customer query urgency classification by analyzing the customer's problem and assigning an appropriate urgency level.

This helps customer support companies prioritize requests and respond to urgent issues efficiently.

---

# 3. Customer Query Classification Using Prompt Engineering

## Problem Statement

An e-commerce company receives numerous customer queries related to orders, deliveries, payments, refunds, cancellations, and product defects.

The task is to design an effective prompt that classifies each customer query into the appropriate predefined category.

## Input

A customer query in natural language.

## Output

A single word representing the category of the query.

## Allowed Categories

- Delivery
- Shipping
- Refund
- Payment
- Cancellation
- Defect
- Return
- Account
- Unknown

## Prompt

You are a customer query classification assistant.

Analyze the given customer query and classify it into exactly ONE of the following categories:

Delivery, Shipping, Refund, Payment, Cancellation, Defect, Return, Account, Unknown.

Rules:

1. Understand the main intention of the customer.
2. Select only one appropriate category.
3. If the query does not match any category, choose Unknown.
4. Output only the category name.
5. Do not provide explanations, punctuation, or additional text.

## Test Cases

| Customer Query | Expected Output |
|---|---|
| My order has not arrived yet. | Delivery |
| My package is stuck in transit. | Shipping |
| I haven't received my money back. | Refund |
| Money was deducted twice from my account. | Payment |
| I want to cancel my order. | Cancellation |
| The product I received is broken. | Defect |
| I want to send this product back. | Return |
| I cannot log in to my account. | Account |
| What is the capital of India? | Unknown |

## Conclusion

Prompt engineering helps automate customer query classification by identifying the customer's intention and assigning the correct predefined category.

This project demonstrates how AI prompts can be used to classify customer queries accurately and efficiently.

---

# Overall Conclusion

These three projects demonstrate the use of Prompt Engineering in real-world applications.

They show how effective prompts can help AI systems perform sentiment analysis, identify customer query urgency, and classify customer queries into predefined categories.
