<img width="734" alt="report" src="https://github.com/limon27121/demo-transaction-api-jmeter/assets/90955039/a1b443f4-5104-4023-a94b-a1a587c8f83a"># Demo Transaction API JMeter Test Plan

## Overview
This repository contains a JMeter test plan (`demo-transaction-api.jmx`) to perform a series of transactions and operations on a financial API. The test plan includes:
1. Admin creating an agent and a customer.
2. Depositing 2000 tk to the agent from the system account.
3. Depositing 1000 tk to the customer from the agent's account.
4. Checking the balance of the customer account.
5. Withdrawing 500 tk from the customer account.
6. Making a payment of 200 tk from the customer account to a merchant.

## Prerequisites
- Apache JMeter installed.
- Java JDK installed.
- Clone this repository.

## Structure
```plaintext
.
├── demo-transaction-api.jmx
└── README.md


# Testing Report Picture
<img src="report.png" alt=" Testing report Screenshot" width="900">

  
