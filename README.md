# Project Proposal

[Sherry Liu](https://github.com/SherryKu), [Veronica Zhao](https://github.com/verozhao)

Jan 28, 2025

## Project title

Smart Refrigerator Management System (SRMS)

## What and why?

We propose developing a Smart Refrigerator Management System (SRMS), a mobile (and/or web) application designed to help people better manage their refrigerated food items and reduce food waste. 🥦📉 

The problem this system addresses is significant: according to the U.S. Food & Drug Administration, the average household wastes approximately 30% to 40% of their food, costing residents $310 billion. 💰🚮 A large portion could be due to poor refrigerator management and forgotten expired items. Moreover, the forgotten expired food items can contaminate other foods in the refrigerator, creating potential health risks 🤢 and requiring extensive cleaning 🧼. Many people, like ourselves, struggle to track expiration dates, forget what food they have, and end up with spoiled items or duplicate purchases. 🛒➡️🗑️ Our system provides a feasible way to mitigate this issue. ✅

What makes this problem more complex is that modern refrigerators come with sophisticated features that could help prevent food waste, but these features often go unused. Different refrigerator models offer varying preservation features and storage zones optimized for specific types of food. 🥩🧀 For example, some models have specialized compartments for fruits and vegetables with humidity control, while others have precise temperature zones for meat and dairy. However, most users don't fully utilize these features because they don't understand how to match different foods with the optimal storage locations in their specific refrigerator model. 🤷‍♂️❄️ This system would bridge this knowledge gap by providing personalized storage recommendations based on both the food type and the unique features of the user's refrigerator model. 🗂️📊

This system would solve these problems by providing automated tracking of food items, expiration dates, and customized storage recommendations based on different refrigerator models. ✅📆 The system enables users to check their refrigerator contents without opening the door, reducing energy waste ⚡ and maintaining optimal temperature 🌡️. Additionally, it would help users maximize their groceries by suggesting recipes 🍽️ based on available ingredients and highlighting missing ingredients that could be automatically added to shopping lists 🛍️, with potential future integration with grocery delivery services like Amazon Fresh or Whole Foods. 🚚 This comprehensive approach would ultimately reduce food waste, save money, and improve food safety. 💵🌱🍽️

## For whom?

This software is designed for **anyone** who wants to **better manage their refrigerated food, reduce waste, and optimize grocery usage**. While the system is particularly useful for certain groups, **any user can benefit from its features**.  

### **Primary Users** 👥  
- **Busy professionals** 🏢👨‍🍳 who cook regularly but struggle to keep track of their groceries.  
- **Families managing shared refrigerators** 👨‍👩‍👧‍👦 who need better coordination of food purchases and usage.  
- **Health-conscious individuals** 🥗🏋️ who want to store food properly and consume it within optimal freshness periods.  
- **Budget-conscious consumers** 💰🛒 who aim to minimize food waste and optimize grocery shopping through inventory tracking and smart recipe suggestions.  
- **Tech-savvy homeowners** 🏠📱 who own modern refrigerators but aren’t fully utilizing their advanced features.  

### **Accessible to Everyone** 🌎  
Even if users don’t fit into these specific categories, anyone who wants to track their food inventory, get expiration reminders, or receive smart recipe suggestions can use this app.  

We have already spoken with **roommates, college friends, and family members** who actively manage household refrigerators, and they have expressed strong interest in such a system.  

Unlike systems that require **business partnerships** for testing, our status as **university students** gives us **direct access** to everyday users in dormitory communities and shared apartments. This allows us to **test, refine, and improve** the app based on real-world feedback from:  
- Busy students who cook 🏫🍳  
- Health-conscious individuals sharing refrigerators 🥦👩‍⚕️  
- Budget-aware consumers looking to reduce waste 🛍️📉  

Since this app is **user-friendly and widely applicable**, it can be a valuable tool for **any household** looking to improve food organization and reduce waste. 🚀  


## How?

The system will provide the following key functionalities from an end-user's perspective:

### 🥦 Food Item Management  
- Users can add items to their digital inventory by **uploading photos** of the food or **receipts**. 📸🧾  
- The system will use **image recognition** to identify items and automatically input relevant details.  
- If the uploaded image is an actual picture of the food, the system may **detect its best-by date** by analyzing color, texture, and surface conditions to assess freshness. 🍎🥩  
- If lighting or food quality is insufficient for analysis, or if the image is a receipt, the system may:  
  - Extract **printed best-by dates** from packaging. 🏷️  
  - Suggest **best-by dates** based on data from food sellers or standard storage guidelines. 📅  
- Users can view refrigerator contents remotely without opening the door, reducing **energy waste** and maintaining optimal **temperature levels**. ❄️🔋  

### ⏳ Expiration Tracking  
- The system maintains a **database of standard food storage times** and sends notifications when items approach expiration. 📢  
- Users receive a **prioritized list** of items that need to be consumed soon. 🥗⏳  
- Expiration predictions adjust based on the **specific storage conditions** of each refrigerator zone. 📊  

### ❄️ Model-Specific Storage Optimization  
- Users input their **refrigerator model** during setup. 🏠🗂️  
- The system provides **customized storage recommendations** for optimal food preservation.  
- Includes **suggested temperature settings** 🌡️ and **ideal storage locations** based on the refrigerator's preservation features (e.g., humidity-controlled drawers or quick-cooling sections).  

### 🍽️ AI-Powered Recipe Suggestions  
- The system suggests meals based on available ingredients, prioritizing those nearing expiration. 🍲  
- Users can filter suggestions based on **dietary preferences** and **cooking time**. 🥦⏳  
- When a recipe is selected, the system:  
  - Highlights **missing ingredients** 🛒  
  - Allows users to add missing ingredients to shopping lists for future grocery delivery integration (Amazon Fresh, Whole Foods, Uber Eats, etc.). 🚚🛍️  

### 📊 Inventory Analytics  
- Users can access insights into food waste patterns to track **most/least used items**. 📉  
- The system provides **shopping recommendations** to optimize grocery purchases. 🛒✅  


## Scope


This project strikes an appropriate balance for a semester-long development by a team of 4-6 programmers. The core functionality of inventory management and expiration tracking provides a solid foundation that can be implemented within the first half of the semester. The image recognition and recipe recommendation features add complexity that makes the project challenging without being overwhelming. We can leverage existing APIs for image recognition and recipe databases to avoid rebuilding these components from scratch. The project can be developed incrementally, with the basic tracking system implemented first, followed by the AI-powered features. The mobile application format provides natural boundaries for the project scope, while still allowing for expansion if time permits. The technical requirements involve mobile development, database design, API integration, and AI implementation--providing enough complexity to engage the entire team while remaining achievable within the semester timeframe.

