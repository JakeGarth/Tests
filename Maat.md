## Table of contents
-   [Introduction](#Introduction)
-   [Pre-Requirements](#Pre-Requirements)
-   [How To Run](#How-To-Run)

# Introduction
The purpose of Maat is to enable Lucifer to make API calls regarding TinkerTank's database of customers/students/subscriptions. 
Essentially, Maat is a middleware between Lucifer and the Stripe database.

## Pre-Requirements
MongoDB v4
Node v12
Ionic v5
Angular v9 


## How to Run
Maat can either be run by:
a) Indepedently, via tests; or
b) In conjuction with Lucifer

### Running Tests
The existing tests within Maat can run using this format in the CMD: "npm run test:{{test name}}".

The following list contains all the available tests:
"test:all"
"test:intercom" 
"test:stripe"
"test:students"
"test:memberships" 
"test:customers" 
"test:records" 
"test:camps"
"test:playbooks"
"test:media"
"test:prod"

### Running With Lucifer
We first have to turn on Maat, then turn on Lucifer. 

To turn on Maat, we use the command "npm run start" in Maat's directory.

Now, to turn on Lucifer, we use the command "ionic serve" in Lucifer's directory. 

Once Lucifer has booted up, your browser will open "https://localhost:8100". You can learn about Lucifer in Lucifer's [README.md](https://www.google.com).



