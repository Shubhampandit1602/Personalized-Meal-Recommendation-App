
# 🍱 HomeSpice Bliss – Personalized Meal Recommendation App

A full-stack web application offering **healthy, affordable, and personalized meals** for hostellers and seniors. Built using **Next.js** and **Firebase**, the app features a **tag-based collaborative filtering recommendation system** to break the monotony of daily meals and empower users with better choices.

---

## 🧠 Abstract

HomeSpice Bliss aims to solve the problem of bland, unhealthy, and repetitive food choices often faced by hostellers and elderly individuals. It connects users to a curated network of local home chefs based on cuisine and location preferences. The application utilizes a smart recommendation system that tailors meal suggestions based on prior orders—ensuring every user gets a meal that fits their taste, health goals, and budget.

---

## ❓ Problem Statement

Hostel residents frequently face limited, unhealthy, and monotonous food options. Our goal is to provide a web app that offers diverse, nutritious, and cost-effective meals—customized to individual taste profiles—while supporting local home chefs and promoting healthy eating habits.

---

## 🔍 Key Features

- 📍 Cuisine & location-based chef selection  
- 📊 Personalized dish suggestions via **Tag-based Collaborative Filtering**  
- 🍲 Healthy, home-cooked meals from verified local chefs  
- 🔁 Order history-based dish recommendations  
- 📐 Fully responsive UI/UX designed in **Figma**

---

## 🛠️ Tech Stack

| Layer            | Tools / Technologies                      |
|------------------|--------------------------------------------|
| **Frontend**     | Next.js, HTML5, CSS3                      |
| **Backend**      | Firebase (Firestore, Realtime DB)         |
| **Recommendation Engine** | Python, Pandas, Surprise, SVD, One-hot Encoding, Itertools |
| **Design**       | Figma                                     |
| **Data Source**  | CSV files                                 |

---

## 🧠 Recommendation System Logic

We implemented a **Tag-based Collaborative Filtering system** that:
- Uses **One-hot encoding** of dish tags
- Applies **Singular Value Decomposition (SVD)** for latent factor analysis
- Leverages **Surprise** library for collaborative filtering
- Computes similarity between dishes based on tag overlap and user order history

📈 **Achieved 97% accuracy** in internal testing by validating dish recommendations post-order.

<img width="497" height="626" alt="image" src="https://github.com/user-attachments/assets/5dbf306b-5d4c-47f2-9cd6-1b9e84ae986d" />


---

## 🖌️ UI/UX Design (Figma)

The interface was designed to prioritize:
- Simplicity for elderly users  
- Aesthetic appeal for students  
- Responsive layout across devices  

🔗 [View the Figma Prototype](https://www.figma.com/proto/jEsc1AhE3levKp0CgWLBkh/Capstone_Final?node-id=4-6&starting-point-node-id=99%3A87&scaling=scale-down&content-scaling=fixed&t=oe5vYUGEiWBs3zVg-1)

---

## ✅ Results & Analysis

- Successfully built a smart meal recommendation engine using collaborative filtering.
- Achieved **97% accuracy** in predicting user-preferred dishes.
- Improved user satisfaction through more diverse and relevant meal options.
- Designed and deployed a complete frontend with Firebase-based backend.

---

## ➕ Advantages

- Promotes **healthy eating** over fast-food chains  
- Supports **local home chefs** and micro-entrepreneurs  
- Offers **culinary variety** based on regional and personal preferences  
- Encourages **sustainable and home-cooked meals**

---

## ⚠️ Limitations

- Limited availability of meals (home-cooked nature)  
- Quality consistency may vary across chefs  
- Slightly higher cost compared to mass-production food options  
- Scaling data and onboarding new chefs needs manual effort

---

## 🔮 Future Scope

- Expansion to more cities and chef networks  
- Integration of **calendar-based meal planning** (custom weekly plans)  
- Use of advanced algorithms (e.g., Neural Collaborative Filtering)  
- Real-time chef tracking and live availability  
- Mobile app version with push notifications for daily menus

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Contact

Feel free to connect on [LinkedIn](https://www.linkedin.com/in/shubham-pandit-04887822b/) or open an issue for feedback.
