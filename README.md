# Project Proposal

[Sherry Liu](https://github.com/SherryKu), [Veronica Zhao](https://github.com/verozhao)

Jan 28, 2025

## Project title

*Give your project a nice title.*

Simple Supply Chain Management System (SCMS)

--------

Smart Refrigerator Management System (SRMS)

## What and why?

*What software system would you like to build this semester, and why? Include a description of what problem the system would solve and why this is important.*

We propose building a Simple Supply Chain Management System (SCMS) designed to streamline and automate key supply chain processes for small-scale retail operations. The system focuses on two critical areas: inventory & supplier management and order processing collaboration.

The problem this system solves is the inefficient manual management of inventory and orders in small retail businesses like pharmacies and convenience stores. Many such businesses still rely on paper-based systems or basic spreadsheets, leading to inventory errors, delayed reordering, and poor supplier coordination. By automating these processes, the system will reduce human error, prevent stock-outs, and improve overall operational efficiency.  


--------


We propose developing a Smart Refrigerator Management System (SRMS), a mobile (and/or web) application designed to help people better manage their refrigerated food items and reduce food waste. The problem this system addresses is significant: according to the U.S. Food & Drug Administration, the average household wastes approximately 30% to 40% of their food, costing residents $310 billion. A large portion could due to poor refrigerator management and forgotten expired items. Moreover, the forgotten expired food items can contaminate other foods in the refrigerator, creating potential health risks and requiring extensive cleaning. Many people, like myself, struggle to track expiration dates, forget what food they have, and end up with spoiled items or duplicate purchases.

Different refrigerator models offer varying preservation features and storage zones optimized for specific types of food. For example, some models have specialized compartments for fruits and vegetables with humidity control, while others have precise temperature zones for meat and dairy. However, most users don't fully utilize these features because they don't understand how to match different foods with the optimal storage locations in their specific refrigerator model. This system would bridge this knowledge gap by providing personalized storage recommendations based on both the food type and the unique features of the user's refrigerator model.

This system would solve these problems by providing automated tracking of food items, expiration dates, and customized storage recommendations based on different refrigerator models.  The system enables users to check their refrigerator contents without opening the door, reducing energy waste and maintaining optimal temperature. Additionally, it would help users maximize their groceries by suggesting recipes based on available ingredients and highlighting missing ingredients that could be automatically added to shopping lists, with potential future integration with grocery delivery services like Amazon Fresh or Whole Foods. This comprehensive approach would ultimately reduce food waste, save money, and improve food safety.

## For whom?

*Who will this software be for? These people are your end-users or customers. Do not make software for imaginary users who do not exist - you must have real people as your initial end-users. Tell us who they are. For example, is it for a particular type of business, mass consumer, a campus office, a professor, or friends or family, or ... people just like you. Understanding who your end-users are, and ideally speaking with some along the way, will help you refine your designs to be suitable for your audience, and understand whether you have succeeded at the end or not.*

This software is specifically designed for small-sized pharmacies and convenience stores. The system will serve multiple end-users within these businesses:

- Inventory managers who need to monitor stock levels and manage supplier relationships
- Stock clerks who handle the physical receipt and dispatch of products
- Sales managers who process customer orders
- Customers who place and track their orders


--------

This software is designed for several specific groups of end-users:

- Busy professionals who regularly cook but struggle to keep track of their groceries
- Families managing shared refrigerators who need better coordination of food purchases and usage
- Health-conscious individuals who want to ensure their food is stored properly and consumed within optimal freshness periods
- Budget-conscious consumers who want to minimize food waste and optimize their grocery shopping through better inventory management and smart recipe suggestions
- Technology-savvy homeowners who have invested in modern refrigerators but aren't fully utilizing their advanced features

We have already spoken with several potential users, including our roommates, college friends, and family members who actively manage household refrigerators, and they have expressed strong interest in such a system.

## How?

*A description of what the system will do from an end-user's perspective. Be as complete as necessary to fully explain the system, but do not worry about technical implementation - this will be developed in subsequent work.*

The system consists of two main modules:

1. Inventory & Supplier Management Module
- Inventory managers can view real-time stock levels, supplier details, and initiate reorders
- Stock clerks can record incoming products, assign storage locations, and process outgoing orders
- The system maintains detailed inventory history and supplier information


2. Sales Processing Module
- Customers can create orders, modify them before processing, and track order status
- Sales managers can monitor new orders and generate picking lists for stock clerks
- The system maintains a comprehensive order history

All operations will be handled sequentially to ensure data consistency and avoid conflicts.


--------
The system will provide the following key functionalities from an end-user's perspective:

Food Item Management: Users can add items to their digital inventory by uploading photos of the food or receipts. The system will use image recognition to identify items and automatically input relevant details.

Expiration Tracking: The system maintains a database of standard food storage times and sends notifications when items are approaching expiration. Users can see a prioritized list of what needs to be consumed soon.

Storage Optimization: Based on the user's refrigerator model (input during setup), the system provides customized storage recommendations for optimal food preservation, including suggested temperature settings and ideal storage locations within the refrigerator.

Recipe Suggestions: An AI-powered recipe recommendation system suggests meals based on available ingredients, prioritizing items nearing expiration. Users can filter suggestions based on dietary preferences and cooking time.

Inventory Analytics: The system provides insights into food waste patterns, most/least used items, and shopping recommendations to help users optimize their grocery purchases.

## Scope

*A brief justification that the proposal is neither too easy nor too ambitions for a group of approximately 4 - 6 programmers to undertake in one semester.*

This project is appropriately scoped for a 4-6 person team over one semester. The system's focus on small retail operations eliminates the need to handle complex manufacturing processes, making it more manageable. The sequential processing model significantly simplifies implementation by avoiding concurrent operations and complex synchronization issues. The project has clearly defined modules that team members can develop in parallel, allowing for efficient distribution of work. While the core functionality is well-defined, the system architecture allows for additional features if time permits. The existence of similar systems in the market provides valuable reference points for design decisions, reducing uncertainty in the development process. The project offers enough complexity through its database design, multiple user interfaces, and order processing logic to be challenging and educational, while remaining achievable within the semester timeframe.

--------


This project strikes an appropriate balance for a semester-long development by a team of 4-6 programmers. The core functionality of inventory management and expiration tracking provides a solid foundation that can be implemented within the first half of the semester. The image recognition and recipe recommendation features add complexity that makes the project challenging without being overwhelming. We can leverage existing APIs for image recognition and recipe databases to avoid rebuilding these components from scratch. The project can be developed incrementally, with the basic tracking system implemented first, followed by the AI-powered features. The mobile application format provides natural boundaries for the project scope, while still allowing for expansion if time permits. The technical requirements involve mobile development, database design, API integration, and AI implementation - providing enough complexity to engage the entire team while remaining achievable within the semester timeframe.

