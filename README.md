# LittleSteps

![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=android&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

**LittleSteps** is a comprehensive Parenting SuperApp designed to assist parents in every step of their child's growth. Built with modern Android technologies, it integrates AI assistance, telemedicine, e-commerce, and social features into a single, intuitive platform.

---

## App Overview
<img width="1920" height="1080" alt="LittleKids" src="https://github.com/user-attachments/assets/86535b16-0de8-4e78-9d42-3ef743bfdfb6" />

LittleSteps aims to be the ultimate companion for parents by providing:
* **AI Parenting Assistant:** Instant answers to parenting questions.
* **Telemedicine:** Direct consultation with pediatricians and specialists.
* **Marketplace:** A curated shop for baby and mother needs.
* **Services:** Easy booking for Daycare and Babysitters.
* **Social Impact:** A platform to donate to families in need.

---

## Screenshots

| **Home & Dashboard** | **Little AI Chat** | **Shop** |
|:---:|:---:|:---:|
| <img src="docs/home.png" width="250" /> | <img src="docs/ai_chat.png" width="250" /> | <img src="docs/consultation.png" width="250" /> |
| *Central hub for all features* | *Smart AI assistant for parents* | *Book doctors & specialists* |

| **Marketplace** | **Daycare Locator** | **Donation** |
|:---:|:---:|:---:|
| <img src="docs/shop.png" width="250" /> | <img src="docs/daycare.png" width="250" /> | <img src="docs/donation.png" width="250" /> |
| *Buy baby essentials* | *Find trusted daycares nearby* | *Help others in need* |

> *Note: The images above are previews. The actual UI utilizes Material Design 3 components.*

---

## ✨ Key Features

### 1. Little AI
Powered by advanced language models, **Little AI** acts as a 24/7 virtual assistant. Parents can ask questions about nutrition, sleep patterns, or general health and receive instant, empathetic responses.

### 2. Doctor Consultation
* Browse a list of specialists (Pediatricians, OBGYN, Dentists).
* View doctor profiles, experience (years), and ratings.
* Integrated chat system for real-time consultation.

### 3. Baby & Mom Shop
* Complete e-commerce module for purchasing milk, diapers, strollers, and vitamins.
* Secure payment integration and order tracking.

### 4. Service Finder (Daycare & Sitter)
* **Daycare:** Location-based search for daycares with facility details (AC, Meals, etc.).
* **Sitter:** Book experienced babysitters with transparent hourly/daily rates.

### 5. Care & Donate
A dedicated section for social responsibility, allowing users to donate to various campaigns (Education, Health, Disaster Relief) directly from their balance.

---

## 🛠 Tech Stack

* **Language:** [Kotlin](https://kotlinlang.org/)
* **UI Framework:** [Jetpack Compose](https://developer.android.com/jetpack/compose) (Modern, declarative UI)
* **Backend & Database:** [Firebase](https://firebase.google.com/)
    * **Firestore/Realtime DB:** For storing user data, products, and chat history.
    * **Authentication:** User login and management.
    * **Storage:** Managing images for profile pictures and product listings.
* **Architecture:** MVVM (Model-View-ViewModel)
* **Navigation:** Jetpack Navigation Compose

---

## 🚀 Getting Started

To run this project locally, follow these steps:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/yourusername/LittleSteps.git](https://github.com/yourusername/LittleSteps.git)
    ```

2.  **Open in Android Studio**
    Open Android Studio and select `Open an existing Android Studio project`. Navigate to the cloned directory.

3.  **Firebase Setup**
    * Go to the [Firebase Console](https://console.firebase.google.com/).
    * Create a new project.
    * Add an Android app to the project (package name must match the one in `build.gradle`).
    * Download the `google-services.json` file.
    * Place `google-services.json` into the `app/` directory of the project.

4.  **Sync & Run**
    * Click "Sync Project with Gradle Files".
    * Run the app on an Emulator or Physical Device.

---

## 🔮 Future Roadmap

- [ ] Video Call integration for Doctor Consultation.
- [ ] Growth Tracker (Height/Weight charts) for children.
- [ ] Vaccination Reminder & Schedule.
- [ ] Community Forum for parents.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
