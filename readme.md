# ATMSimulator Project

## Background

The goal of this project is to create an ATM simulator using Java. The simulator should authenticate a user, offer different types of accounts, and provide account services.

## Instructions

- Fork this repository via GitHub
- Clone it by clicking the green clone button, copying the URL, and using your terminal to $ git clone
- Create a new branch called develop from master and push develop
- Create a new branch for your first feature and push it
- Work on the new feature
- When the feature is complete, push the code and use GitHub to merge the code into the develop branch via a Pull Request
- Pull the new develop using $ git pull on your terminal
- Create a new branch from develop for your next feature
- Rinse repeat. New feature branch > write code > commit/push code > merge using Pull Request > pull changes to local develop > new feature branch. 

## Requirements

- The ATM should support multiple users with a login/logout feature
- It should support multiple bank accounts per user
- At a minimum, it should support Savings, Checking, and Investment account types
- Users should be able to withdraw, deposit, and transfer money between accounts
- The Savings account should accrue interest at some rate
- Bonus points if Savings Accounts have tiers with different rates
- Users should be able to initiate a transfer from their account to another user's account
- Users should not be able to have more than one Checking account
- User interaction should be supported via a command line interface
- Users should be able to update their user profile information
- User profiles should include the following information: user name, password, first name, last name, and email address
- While the application is running, it should maintain the state of the various accounts and users. I.e., if a user logs out and another logs in, it should be able to fetch whatever the user's information was including their accounts balances
- Invalid user input should not cause the application to unexpectedly fail. I.e., include error handling
- The ATM should not shut down once a user has performed a transaction. It should stay running until terminated by the developer.
- 70% of lines should be covered by tests


