# Fitness-Buddy-AI-Powered-Nutrition-Fitness-Assistant
# 🧠 Fitness Buddy – AI-Powered Nutrition & Fitness Assistant

## 📌 Problem Statement No.13 – Fitness Buddy

In today’s fast-paced world, individuals often struggle to maintain a healthy lifestyle due to lack of time, personalized guidance, and motivation. Traditional fitness solutions can be expensive and rigid, making them difficult to follow consistently.

**Fitness Buddy** is a smart, conversational AI assistant designed to promote healthier living. It offers users:
- 🏋️ Personalized home workout suggestions
- 🍽️ Nutritious and easy-to-make meal plans
- 💧 Hydration and general wellness tips
- 📅 Daily motivation and habit-building strategies

> 💡 Powered by **IBM Watsonx.ai**, **Granite Foundation Model**, and **IBM Cloud Object Storage** (Free Tier – IBM Cloud Lite)

---

## 🌟 Key Features

- 🏠 Home workout plans (equipment-free or with equipment)
- 🥗 Diet plans for weight loss, gain, or maintenance
- 🍎 Nutrition facts for fruits, vegetables, grains, etc.
- 💧 Water intake and hydration suggestions
- 💬 Friendly, multilingual, and beginner-friendly responses
- ✅ Works 24/7 with no external API dependency

---

## 🧠 Technology Stack

- **IBM Watsonx.ai Studio**
- **IBM Granite Foundation Model**  
  - `granite-13b-chat` or `granite-3-8b-instruct`
- **IBM Cloud Object Storage**
- **Watsonx Agent Lab (Chat & Build)**

---

## 🚀 Setup Instructions

### ✅ Step 1: Access IBM Watsonx.ai
1. Log in at [IBM Cloud](https://cloud.ibm.com)
2. Navigate to **Watsonx > Watsonx.ai**

### ✅ Step 2: Create Agent Project
1. Go to **Gen AI > Automating Tasks > Agent Lab**
2. Click **Create New Project**
3. Project Name: `Fitness Buddy`
4. Attach IBM Cloud Object Storage when prompted

### ✅ Step 3: Build Agent in Agent Lab
1. Go to the **Chat and Build** tab
2. Click **Associate Service** and add/create `watsonx.ai Runtime`
3. Select Model: `granite-13b-chat` or `granite-3-8b-instruct`
4. Paste agent prompt (see below):

```txt
Hi! I’m your Fitness Buddy – I can help you with home workouts, healthy diet plans, hydration tips, and wellness motivation. Ask me anything!
