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

# Customer Query Urgency Classification Using Prompt Engineering

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

This project demonstrates how AI prompts can help customer support companies prioritize requests and respond to urgent issues efficiently.
