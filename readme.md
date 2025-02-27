# SaaS Payment Gateway Backend Template using Node.js with Proper Documentation and Clarity of Code.

Hey I'm Shivam, my aim to develop this repository is to help new developers to be able to understand how SaaS payment works using Razorpay which has the best documentation, I'll be dropping my own documentation as well using swagger and also hobbyist developers can use it as a template for their projects.

A backend application built with Node.js and Express for integrating [Razorpay](https://razorpay.com/) payment gateway functionalities. This repository demonstrates how to create orders, capture payments, and manage webhooks using Razorpay’s API, providing a solid foundation for building robust payment solutions.

Platforms to be supported : Android, iOS, PWA.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)

## Features

- **Single Purchase Order Creation:** Easily create new payment orders with customizable amounts and receipts.
- **Subscription Based Purchase Order Creation:** Easily create new subscriptions with customizable amounts and receipts.
- **Payment Capture:** Securely capture payments after authorization.
- **Webhook Handling:** Set up endpoints to process real-time payment events from Razorpay.
- **Secure Integration:** Use environment variables to manage sensitive credentials.

## Prerequisites

- [Node.js](https://nodejs.org/) (v14 or higher recommended)
- [NPM](https://www.npmjs.com/) or [Yarn](https://yarnpkg.com/)
- A valid [Razorpay](https://razorpay.com/) account to obtain API keys


## Things to remember 
- destructuring syntax { function_name } requires module.exports.function_name = function_name;
