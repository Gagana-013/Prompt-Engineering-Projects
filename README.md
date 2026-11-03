# Prompt Engineering Projects

## 1. Sentiment Analysis

**Problem Statement:** Classify customer reviews based on their overall sentiment.

**Allowed Outputs:**
- Positive
- Negative
- Neutral

**Prompt:**
Analyze the given customer review and classify its overall sentiment into exactly one of the following categories: Positive, Negative, or Neutral.

Output only a single word. Do not provide explanations or additional text.

**Test Cases:**

| Customer Review | Output |
|---|---|
| The product is excellent, and I love its quality. | Positive |
| The delivery was late, and the product was damaged. | Negative |
| The product arrived yesterday. | Neutral |
| The customer support team was extremely helpful. | Positive |
| The product is not worth the money. | Negative |
| The package contained two items. | Neutral |
| The phone is good, but the battery life is terrible. | Negative |

## 2. Customer Query Urgency Classification

**Problem Statement:** Classify customer queries based on their urgency level.

**Allowed Outputs:**
- High
- Medium
- Low

**Prompt:**
Analyze the given customer query and classify its urgency into exactly one of the following categories: High, Medium, or Low.

Output only a single word. Do not provide explanations or additional text.

**Test Cases:**

| Customer Query | Output |
|---|---|
| My bank account has been hacked, and money is being stolen. | High |
| My internet has been down for the entire day, affecting my work. | High |
| I haven't received my refund for the last seven days. | Medium |
| Can you tell me how to update my profile picture? | Low |
| I need to change my delivery address for an order arriving tomorrow. | High |
| I would like to know about your available subscription plans. | Low |
| I lost access to my account and cannot complete an urgent payment. | High |

## Conclusion

These projects demonstrate how prompt engineering can be used to classify customer reviews and customer queries using predefined categories.

#3.Customer Query Classification Using Prompt Engineering

## 1. Problem Statement

An e-commerce company receives numerous customer queries related to orders, deliveries, payments, refunds, cancellations, and product defects.

The task is to design an effective prompt that classifies each customer query into the appropriate predefined category.

## 2. Input

A customer query in natural language.

## 3. Output

A single word representing the category of the query.

## 4. Allowed Categories

- Delivery
- Shipping
- Refund
- Payment
- Cancellation
- Defect
- Return
- Account
- Unknown

## 5. Prompt

You are a customer query classification assistant.

Analyze the given customer query and classify it into exactly ONE of the following categories:

Delivery, Shipping, Refund, Payment, Cancellation, Defect, Return, Account, Unknown.

**Rules:**

1. Understand the main intention of the customer.
2. Select only one appropriate category.
3. If the query does not match any category, choose Unknown.
4. Output only the category name.
5. Do not provide explanations, punctuation, or additional text.

## 6. Test Cases and Expected Outputs

| No. | Customer Query | Expected Output |
|---|---|---|
| 1 | My order has not arrived yet. | Delivery |
| 2 | My package is stuck in transit. | Shipping |
| 3 | I haven't received my money back. | Refund |
| 4 | Money was deducted twice from my account. | Payment |
| 5 | I want to cancel my order. | Cancellation |
| 6 | The product I received is broken. | Defect |
| 7 | I want to send this product back. | Return |
| 8 | I cannot log in to my account. | Account |
| 9 | What is the capital of India? | Unknown |

## 7. Conclusion

Prompt engineering helps automate customer query classification by identifying the customer's intention and assigning the correct predefined category.

This project demonstrates how AI prompts can be used to classify customer queries accurately and efficiently.
