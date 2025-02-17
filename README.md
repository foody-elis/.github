<img src="resources/README.gif">

# Foody ELIS

# Table of Contents

- [Description](#description)
    - [Useful Links](#useful-links)
    - [What is Foody](#what-is-foody)
- [Project Repositories](#project-repositories)

## Description

### Useful Links

- Documentation: https://docs.google.com/document/d/1p1RFOiUF8x7opr-N9B8PLcPE7cJZiqI1_v2iclKKEvk/edit?usp=sharing
- Presentation: https://pitch.com/v/presentazione-foody-hk9puv

### What is Foody

Foody is an **innovative** and **centralized** software solution designed to optimize interactions between **users** and
**restaurants**. It offers an all-in-one platform for **table reservations**, **in-restaurant orders**, **payments** and
**reviews** through a user-friendly interface.

The system includes a mobile app for customers to find restaurants, book tables, place orders, make payments and leave
reviews, as well as a dedicated app for restaurant owners to **manage menus**, **reservations**, and **customer feedback
**. Additionally, it supports restaurant staff by **streamlining order management** and communication between the
kitchen and dining area, improving efficiency and service accuracy.

Foody addresses the growing need for digitalization in the restaurant industry, providing a **scalable** and *
*innovative** solution to enhance both customer experience and operational performance.

## Project Repositories

The source code for the project is stored on GitHub under the **foody-elis** organization, which contains the following
repositories:

| Repository                                                                       | Description                                                                                                                                       |
|----------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------|
| **[foody-api](https://github.com/foody-elis/foody-api)**                         | Backend system exposing APIs, interacting with the relational database, and integrating with third-party services.                                |
| **[foody-app](https://github.com/foody-elis/foody-app)**                         | Mobile application for **end users**, enabling them to browse restaurants, make bookings, place orders, and leave reviews.                        |
| **[foody-business-app](https://github.com/foody-elis/foody-business-app)**       | Application for **restaurant staff (waiters and cooks)** to manage and process customer orders efficiently.                                       |
| **[foody_api_client](https://github.com/foody-elis/foody_api_client)**           | Dart library that simplifies interaction with Foody's APIs, providing pre-built methods for developers.                                           |
| **[foody-cloud-functions](https://github.com/foody-elis/foody-cloud-functions)** | **Serverless functions** running on **Firebase**, used for asynchronous operations such as push notifications and automatic order status updates. |
| **[multiselect_dropdown](https://github.com/foody-elis/multiselect-dropdown)**   | **Custom Flutter library** developed for advanced **multi-selection dropdowns**, used within Foody's apps for enhanced selection experiences.     |

This structure ensures **modularity and scalability** across all components of the Foody ecosystem.