# Credit Card Transaction Journey Map

## Project Overview

This project maps the journey of a real-world, in-person credit card payment made at a restaurant. It follows the transaction from the moment the card is presented at the payment terminal through authorization and, later, settlement, showing how each participant in the payment ecosystem contributes to completing the purchase.

The result is a visual process map, built in Lucidchart, that breaks a routine everyday purchase into its underlying steps and explains what happens behind the scenes.

## Project Objectives

- Understand how a credit card payment moves from the point of sale to the cardholder's account.
- Identify each participant in the transaction and the role it plays.
- Distinguish between **authorization** (approving the payment) and **settlement** (moving the funds).
- Translate a complex, multi-party financial process into a clear, easy-to-follow visual.

## Transaction Flow

The payment involves the following participants:

| Participant | Role |
|---|---|
| **Cardholder** | The customer who pays for the meal using a credit card. |
| **Merchant** | The restaurant that accepts the card payment for goods and services. |
| **Payment Terminal** | The point-of-sale device that reads the card and securely captures the transaction details. |
| **Payment Processor** | Routes transaction data between the merchant, the acquiring bank, and the card network. |
| **Acquiring Bank** | The merchant's bank, which submits transactions on the merchant's behalf and receives the funds at settlement. |
| **Card Network** | Connects acquirers and issuers, routes the authorization request, and facilitates clearing and settlement. |
| **Issuing Bank** | The cardholder's bank, which issued the card, approves or declines the transaction, and bills the cardholder. |

> **Note:** The project research did not confirm the specific companies acting as the payment processor or the acquiring bank for this transaction. These participants are therefore identified by their role rather than by name.

**Simplified flow:**

1. The cardholder presents the card at the restaurant's payment terminal.
2. The terminal sends the transaction details to the payment processor.
3. The request is routed through the acquiring bank and the card network to the issuing bank.
4. The issuing bank checks the account (available credit, fraud signals, card status) and returns an approval or decline.
5. The response travels back through the same path to the terminal, and the purchase is completed.
6. Later, the transaction is cleared and settled, and funds move from the issuer to the acquirer and then to the merchant.

## Authorization vs. Settlement

A key lesson from this project is that a card payment happens in two distinct stages:

- **Authorization** determines whether the payment is approved. It happens in seconds at the point of sale and confirms that the card is valid and that the cardholder has enough available credit. No money changes hands at this stage; the amount is placed as a pending hold.
- **Settlement** is the separate process of actually moving funds between the issuing bank, the acquiring bank, and the merchant. It typically happens in batches, after the merchant submits its transactions.

In this project, the purchase was made on **September 11, 2026**, and the transaction posted to the cardholder's account on **September 14, 2026**. This gap illustrates that approval at the table and final posting to the account are two separate events.

## Key Takeaways

- A single card swipe or tap involves multiple independent organizations working together.
- Authorization and settlement are separate processes that happen at different times.
- A "pending" charge reflects authorization; a "posted" charge reflects completed processing.
- The card network acts as the central connection between the merchant's side (acquirer) and the cardholder's side (issuer).
- Process mapping is an effective way to make complex financial systems easier to understand.

## Tools Used

- **Lucidchart** — to design and visualize the transaction journey map.
- **FinTech research** — to identify participants, their roles, and the stages of card payment processing.

## Project Deliverable

[View the Credit Card Transaction Journey Map (PDF)](CC_Journey_v5%20%283%29.pdf)

## Skills Demonstrated

- Payment card processing
- FinTech fundamentals
- Business process mapping
- Research
- Process visualization
