# RAiD Software Engineering Challenge

## Introduction

Welcome to the RAiD Software Engineering Technical Assessment. In this challenge, you are tasked with developing a simple full stack web application: a Point of Sales application for a fruit store, as detailed below.

Following your submission, a technical interview will be conducted to discuss your code, the design decisions you made, and any challenges you encountered during the development process. During the interview, you will be required to:

- Present your application functions (and which user stories you completed)
- Highlight any unfamiliar tools, frameworks, or coding practices you used in this challenge and the challenges you faced
- Be prepared to explain your development choices and thinking process
- Be prepared to add/modify functionality on the spot
  The challenge aims to be beginner-friendly and should take about 4-6 hours to complete. Plagiarism is strictly prohibited; submissions will be compared for originality.

## Assessment Objectives

The goal of this technical assessment is to evaluate key aspects of your software engineering skills and mindset. We are looking for candidates who demonstrate:

1. Learning Attitude and Problem-Solving Skills. An enthusiasm for tackling problems in unfamiliar contexts and a keenness to learn.

2. Coding Fundamentals. A good grasp and ability to apply fundamental programming principles to produce efficient, robust, and secure code.

3. User-Centric Development. Ability to understand user stories and develop an intuitive and functional application from them.

4. Efficient Use of Tools and Frameworks. Proficiency in evaluating and selecting appropriate tools and frameworks that streamline development and enhance application performance.

5. Readable, Clean Code. The capability to write code that is not only functional, but also readable and clean, facilitating teamwork, easier maintenance, and scalability.

## Deliverables

You are required to deliver:

1. A public domain address to access the web application.

2. A public github repository containing the source code. If you wish, you may keep the repository private and grant read access to the interview panel.

3. a README file within your repository containing a list of the user stories you implemented.

## User Stories

You are required to develop a full stack web application to serve as a Point of Sales application for an online fruits store. The application will have two user personas; a customer and a store owner.

The fruits store contains the following fruits. You may include additional fruits.

| Fruit  | Price | Starting Stock |
| ------ | ----- | -------------- |
| Apple  | $1.00 | 30             |
| Orange | $1.50 | 25             |
| Banana | $2.00 | 40             |

### Required User Stories

You are required to features to fulfil the following user stories:

1. As a customer, I want to see a list of fruits that are available to buy (complete with stock and pricing information), so that I can decide which fruits I want to buy.

2. As a customer, I want to keep track of the fruits and quantity that I have shortlisted (including the total amount I need to pay), so that I can adjust my purchasing decisions as I shop.

3. As a customer, I want to submit my order of the fruits I selected, so that I can complete my purchase when I am done shopping. Assume that payment is done separate from this POS application.

4. As an owner, I want to see the orders that my customers have submitted, so that I can fulfill their orders.

### **_Optional_** User Stories

You may choose to implement some or all of following user stories in order to demonstrate your technical proficiency. You **_DO NOT_** need to implement these stories in order to be considered for the next stage of the interview process.

5. As an owner, I want to see the total sales for each day and for each fruit, so that I can track the performance of my store.

6. As an owner, I want to be able to add new fruits and amend my stock levels, so that I can keep my online store up to date.

7. As a customer, I want to be able to log in and see my order history, so that I can track my previous purchases.

8. As a customer, I want to be able to re-order a previous order, so that I can quickly purchase the same items again.

9. As a customer, I want to know how many people are currently considering buying a fruit, so that I can make a quick decision before the stock runs out.

10. As a customer, I want to be able to ask the store owner common questions about a fruit, so that I can make an informed decision about my purchase.

11. As a customer, I want to be able to use the app on my phone so I can shop on the go.

12. As a customer, I want my order shortlist to be saved so that I can continue shopping on my device layer, even if I have not logged in.

13. As a customer, after logging in, I want my order shortlist to be saved so that I can log in and continue shopping on another device later.

14. As an owner, I want to be able to serve millions of customers at the same time, so that I can scale my business.

15. As an owner, I do not want my customers to be able to see the whole store's order history, or amend my stocks, or perform any actions that should only be available for me.

16. As an owner, I want my customers' order submissions to be encrypted, so they cannot be intercepted by my competitors.

17. As a customer, I want the fruit store pages to load quickly at all times, so that I can browse and shop without delays.

## Technical Requirements

Your web application must be a three-tier application:

1. Front End. A React web application written in Javascript or Typescript and built with Create React App, Vite, or Next.js.

2. Server. An API server written in Javascript or Typescript and run on Node.js. You may also write the API server using Next.js.

3. Database. Any database (e.g. postgresql, mongodb, etc.)
   You are free to use any additional tools, frameworks, or libraries to help you build the application. You are also free to use any CSS framework or library to style your application.
