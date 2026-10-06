NAME: DOE CALVIN KWAKU
STUDENT ID.: 223017884



System Analysis and Design Assignment
Online Shopping Order Management System

1. Scenario

An Online Shopping Order Management System allows customers to browse products, place orders, make payments, and track their orders. Administrators manage products and orders, while delivery personnel update delivery statuses.

2. Primary Entities

- Customer
- Product
- Shopping Cart
- Order
- Payment
- Delivery

 3. Responsibilities

- Display available products
- Allow customers to add products to a shopping cart
- Allow customers to place orders
- Process customer payments
- Generate order confirmations
- Track order status
- Update delivery status
- Allow administrators to manage products and orders

  User Story 1 – Place an Order

As a customer,
I want to add products to my cart and place an order,
so that I can purchase the products I need online.

User Story 2 – Track an Order

As a customer,
I want to view the status of my order,
so that I know when my order will be delivered.
Feature: Place an online shopping order

Scenario: Customer successfully places an order

Given the customer has selected a product
And the product is available
And the customer has added the product to the shopping cart
When the customer proceeds to checkout
And provides the required delivery information
And completes the payment
Then the system should create the order
And the system should display an order confirmation

Feature: Track an online shopping order

Scenario: Customer checks order status

Given the customer has placed an order
When the customer opens the order tracking page
Then the system should display the current order status
And the customer should be able to see the delivery progress
