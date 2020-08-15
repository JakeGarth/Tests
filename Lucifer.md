## Table of contents
-   [Introduction](#Introduction)
-   [Pre-Requirements](#Pre-Requirements)
-   [How To Run](#How-To-Run)
-   [Architecture](#Architecture)

# Introduction
The purpose of Lucifer is to provide a web-application for staff to see TinkerTank's customers and students through a GUI.

## Pre-Requirements 
Node v12  
Ionic v5  
Angular v9   

## How to Run
Lucifer can only be run effectively when it is retrieving data from Maat. To run Lucifer, start running Maat first. 

To turn on Maat, we use the command "npm run start" in Maat's directory.  

Now, to turn on Lucifer, we use the command "ionic serve" in Lucifer's directory.   

Once Lucifer has booted up, your browser will open https://localhost:8100.  

## Architecture
Lucifer makes an API call to Maat, which requests customer information from Stripe.  

The Architecture for how Lucifer accesses customer information can be pictured in the following way:  
Customer Info -> Stripe Database -> Maat -> Lucifer






