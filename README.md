# daml_ceritifcation_capstone_project

This project is built on top of DAML SDK 2.7.1 using empty skeleton.
# Crop Sale Platform with DAML

This project is an implementation of a simple Crop Sales Platform using DAML (Digital Asset Modeling Language). The platform allows seller to create the sales for the item / update the price and Buyers can buy the product.

## Introduction

This is a simple sell and buy project written in DAML. A smart contract where sellers can define the buyers who can see the sales details and then they can create the product for sales.

1. Buyer need to deposite the amount and the deposited amount must be greater than the crop price.
2. Also, the ready for sale for the crop must be enabled, in order to buyers can buy the crop.

Also note Only the Buyers who maps to the sale can view the crop details and able to buy.
It is built as a part of DAML Fundamentals certification.
 

## Getting Started

To run this project locally, you'll need to have DAML SDK installed on your machine. Follow the official DAML documentation to install the SDK: [DAML SDK Installation](https://docs.daml.com/getting-started/installation.html)

### Cloning the Repository

First, clone this repository to your local machine using the following command: 

### Running the Tests

To run the test scenarios for the crop sale, you can use the DAML Script feature to execute the defined test scripts.

1. Open a terminal window and navigate to the root directory of the project.

2. Run the tests using the following command:
    
    ```daml test```

### Running the Project

To run the project, you can use the DAML Sandbox feature to spin up a local instance of the ledger.

1. Open a terminal window and navigate to the root directory of the project.

2. Run the project using the following command:
    
    ```daml start```

    This will start the sandbox and deploy the crop sales on the ledger.



## Project Structure

The project is organized into three DAML modules:

1. `CropSales.daml`: Contains the main templates and choices to implement the crop sales.

2. `Test.daml`: Contains test scripts to verify the functionality of the crop sales.

3. `Main.daml`: Contains setup scripts for creating user and using navigator, we can execute the actions.


 

