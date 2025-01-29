# Project Proposal

[Sherry Liu](https://github.com/SherryKu), [Veronica Zhao](https://github.com/verozhao)

Jan 28, 2025

## Project title

Smart Refrigerator Management System (SRMS)

## What and why?

We propose developing a Smart Refrigerator Management System (SRMS), a mobile (and/or web) application designed to help people better manage their refrigerated food items and reduce food waste. 🥦📉 

The problem this system addresses is significant: according to the U.S. Food & Drug Administration, the average household wastes approximately 30% to 40% of their food, costing residents $310 billion. 💰🚮 A large portion could be due to poor refrigerator management and forgotten expired items. Moreover, the forgotten expired food items can contaminate other foods in the refrigerator, creating potential health risks 🤢 and requiring extensive cleaning 🧼. Many people, like ourselves, struggle to track expiration dates, forget what food they have, and end up with spoiled items or duplicate purchases. 🛒➡️🗑️ Our system provides a feasible way to mitigate this issue. ✅

Different refrigerator models offer varying preservation features and storage zones optimized for specific types of food. 🥩🧀 For example, some models have specialized compartments for fruits and vegetables with humidity control, while others have precise temperature zones for meat and dairy. However, most users don't fully utilize these features because they don't understand how to match different foods with the optimal storage locations in their specific refrigerator model. 🤷‍♂️❄️ This system would bridge this knowledge gap by providing personalized storage recommendations based on both the food type and the unique features of the user's refrigerator model. 🗂️📊

This system would solve these problems by providing automated tracking of food items, expiration dates, and customized storage recommendations based on different refrigerator models. ✅📆 The system enables users to check their refrigerator contents without opening the door, reducing energy waste ⚡ and maintaining optimal temperature 🌡️. Additionally, it would help users maximize their groceries by suggesting recipes 🍽️ based on available ingredients and highlighting missing ingredients that could be automatically added to shopping lists 🛍️, with potential future integration with grocery delivery services like Amazon Fresh or Whole Foods. 🚚 This comprehensive approach would ultimately reduce food waste, save money, and improve food safety. 💵🌱🍽️

## For whom?

This software is designed for several specific groups of end-users:

- Busy professionals who regularly cook but struggle to keep track of their groceries
- Families managing shared refrigerators who need better coordination of food purchases and usage
- Health-conscious individuals who want to ensure their food is stored properly and consumed within optimal freshness periods
- Budget-conscious consumers who want to minimize food waste and optimize their grocery shopping through better inventory management and smart recipe suggestions
- Technology-savvy homeowners who have invested in modern refrigerators but aren't fully utilizing their advanced features

We have already spoken with several potential users, including our roommates, college friends, and family members who actively manage household refrigerators, and they have expressed strong interest in such a system.

Unlike some systems that need the involvement of business owners to test, which raise additional difficulties when partnering with those end-users, being university students, we have direct access to the user segments that can potentially be the end-users for this system, particularly through our dormitory communities and shared student apartments. Our immediate environment provides an ideal testing ground with users who fit multiple target segments: busy students who cook, health-conscious individuals sharing refrigerators, and budget-aware consumers wanting to minimize waste. This proximity to our user base will allow for rapid feedback cycles and iterative improvements throughout the development process.

## How?

The system will provide the following key functionalities from an end-user's perspective:

Food Item Management: Users can add items to their digital inventory by uploading photos of the food or receipts. The system will use image recognition to identify items and automatically input relevant details. If the uploaded image is the actual picture of the food, the system may detect its best-by date by looking at its visual characteristics (color, texture, surface conditions) to assess its current freshness level. If the light or quality of the food is not good enough to provide those information, or if the uploaded image is the recept, the system may extract printed best-by dates from packaging, the suggested best-by dates from internet/food sellers, or the standard storage timelines. Users can also view their refrigerator contents remotely without opening the door, reducing energy waste and maintaining optimal temperature.

Expiration Tracking: The system maintains a database of standard food storage times and sends notifications when items are approaching expiration. Users can see a prioritized list of what needs to be consumed soon. The system adjusts expiration predictions based on the specific storage conditions of each refrigerator zone.

Model-Specific Storage Optimization: Based on the user's refrigerator model (input during setup), the system provides customized storage recommendations for optimal food preservation. This includes suggested temperature settings for different compartments and ideal storage locations based on the refrigerator's specific preservation features (such as humidity-controlled drawers or quick-cooling sections).

Recipe Suggestions: An AI-powered recipe recommendation system suggests meals based on available ingredients, prioritizing items nearing expiration. Users can filter suggestions based on dietary preferences and cooking time. When a recipe is selected, the system highlights missing ingredients that could be automatically added to shopping lists for future integration with grocery delivery services such as Amazon fresh delivery, wholefoods delivery, Uber delivery etc.

Inventory Analytics: The system provides insights into food waste patterns, most/least used items, and shopping recommendations to help users optimize their grocery purchases.

## Scope


This project strikes an appropriate balance for a semester-long development by a team of 4-6 programmers. The core functionality of inventory management and expiration tracking provides a solid foundation that can be implemented within the first half of the semester. The image recognition and recipe recommendation features add complexity that makes the project challenging without being overwhelming. We can leverage existing APIs for image recognition and recipe databases to avoid rebuilding these components from scratch. The project can be developed incrementally, with the basic tracking system implemented first, followed by the AI-powered features. The mobile application format provides natural boundaries for the project scope, while still allowing for expansion if time permits. The technical requirements involve mobile development, database design, API integration, and AI implementation - providing enough complexity to engage the entire team while remaining achievable within the semester timeframe.

