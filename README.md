# AI-Based Recommendation System using Java and Apache Mahout

## 📌 Project Overview

This project implements an **AI-based Recommendation System** using **Java** and **Apache Mahout**. The system recommends products or items to users based on their preferences using **Collaborative Filtering**.

Recommendation systems are widely used in platforms like **Amazon, Netflix, YouTube, and Spotify** to suggest relevant content to users.

---

## 🤖 AI Concept Used

### Collaborative Filtering

Collaborative filtering recommends items based on similarities between users.

Example:

* If User A and User B have similar interests
* And User A likes Item X
* Then Item X will be recommended to User B

---

## 🛠 Technologies Used

* Java
* Apache Mahout (Machine Learning Library)
* Maven (Build Tool)
* CSV File (Dataset)
* VS Code (IDE)

---

## 📂 Project Structure

```
AI-Recommendation-System-using-Mahout
│
├── pom.xml
├── data.csv
├── README.md
│
└── src
    └── main
        └── java
            └── RecommendationEngine.java
```

---

## 📊 Dataset Format

The dataset is stored in a CSV file:

```
UserID,ItemID,Rating
```

Example:

```
1,101,5
1,102,3
2,101,2
2,104,5
3,103,4
```

Where:

* UserID → User identifier
* ItemID → Product identifier
* Rating → User preference (1 to 5)

---

## ⚙ How the System Works

Step 1: Load user-item rating data
Step 2: Calculate similarity between users
Step 3: Find nearest similar users
Step 4: Predict ratings for unseen items
Step 5: Recommend items to the user

Apache Mahout handles similarity calculation and recommendation generation.

---

## ▶ How to Run the Project

### Step 1: Open terminal in project folder

```
cd AI-Recommendation-System-using-Mahout
```

### Step 2: Compile project

```
mvn compile
```

### Step 3: Run project

```
mvn exec:java
```

---

## ✅ Example Output

```
Recommendations for User 1:
Item ID: 104 | Predicted Rating: 4.6
```

This means the system predicts User 1 will like Item 104.

---

## 🌍 Real-world Applications

* Amazon → Product recommendation
* Netflix → Movie recommendation
* YouTube → Video recommendation
* Spotify → Music recommendation
* Flipkart → Shopping recommendation

---

## 🎯 Features

* AI-based recommendation
* Collaborative filtering algorithm
* Uses Apache Mahout
* Easy to understand and extend
* Lightweight and efficient

---

## 📚 Learning Outcomes

From this project, we learned:

* Basics of recommendation systems
* Collaborative filtering technique
* Using Apache Mahout library
* Implementing machine learning in Java
* Maven project structure

---

## 👨‍💻 Author

Name: Sanjeevi
Project: AI Recommendation System using Apache Mahout
Language: Java
Library: Apache Mahout

---

## 📄 License

This project is for educational purposes.
