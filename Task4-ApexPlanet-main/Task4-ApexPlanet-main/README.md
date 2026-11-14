# 🍔 Crave – Food Delivery App

### Task 3 | ApexPlanet Internship

Crave is a food delivery application developed as part of Task 3 of the ApexPlanet Internship. The application provides a convenient platform for customers to explore food items, manage their carts, and place orders, while restaurant partners can manage their food listings and customer orders.

## 📱 About the Project

Crave aims to simplify online food ordering through a clean, user-friendly interface and Firebase backend integration.

The application includes two main modules:

* Customer Module
* Restaurant / Seller Module

## ✨ Features

### 👤 Customer Module

* User registration and login.
* Browse food items.
* Search for food.
* View food details.
* Add food items to favourites.
* Add items to cart.
* Manage cart and checkout.
* View order details.
* Manage user profile.
* Manage saved addresses.

### 🏪 Restaurant / Seller Module

* Seller registration and login.
* Seller dashboard.
* Manage restaurant food items.
* Add and update food listings.
* Manage customer orders.
* Update restaurant information.

## 🛠️ Technologies Used

| Technology              | Purpose                 |
| ----------------------- | ----------------------- |
| Flutter                 | Application development |
| Dart                    | Programming language    |
| Firebase Authentication | User authentication     |
| Cloud Firestore         | Database                |
| Kotlin                  | Android native platform |
| Gradle                  | Android build system    |
| Git & GitHub            | Version control         |

## 🔥 Backend Integration

Firebase is used for backend services, including:

* Firebase Authentication for user authentication.
* Cloud Firestore for storing and managing application data.

## 📂 Project Structure

```text
CraveFoodDelivery/
│
├── android/              # Android platform configuration
├── app/                  # Native Android application module
├── lib/                  # Flutter application source code
│   ├── data/
│   ├── models/
│   ├── services/
│   ├── state/
│   └── ui/
│
├── test/                 # Flutter tests
├── web/                  # Web application files
├── firestore.rules       # Firestore security rules
├── firebase.json         # Firebase configuration
├── pubspec.yaml          # Flutter dependencies
└── README.md             # Project documentation
```

## 🚀 How to Run the Project

### Prerequisites

* Flutter SDK
* Dart SDK
* Android Studio or Visual Studio Code
* Firebase project configuration

### Installation

**1. Clone the repository**

```bash
git clone https://github.com/JanakRajpurohit/Task3.-ApexPlanet.git
```

**2. Navigate to the project directory**

```bash
cd CraveFoodDelivery
```

**3. Install dependencies**

```bash
flutter pub get
```

**4. Configure Firebase**

Configure your own Firebase project and generate the required local configuration files:

* `lib/firebase_options.dart`
* `android/app/google-services.json`

These files are excluded from this repository for security and configuration management.

**5. Run the application**

```bash
flutter run
```

## 🎯 Project Objective

The objective of this project is to develop a food delivery application while gaining practical experience in mobile application development, Flutter, Dart, Firebase integration, and version control using Git and GitHub.

## 👨‍💻 Developer

**Janak Rajpurohit**

GitHub: [JanakRajpurohit](https://github.com/JanakRajpurohit)

## 🏢 Internship Details

**Organization:** ApexPlanet Software Pvt. Ltd.

**Task:** Task 3 – Food Delivery Application

---

⭐ Thank you for visiting the Crave project repository!

The previous native Kotlin/Compose project remains under `app/` with its root Gradle files; Flutter uses the root `pubspec.yaml`, `lib/`, and `android/` folders.
=======
# Task3-ApexPlanet
Task 3 in which i have made an resturant food app named ad Crave and in that i have connected the backend of firebase like authentication and the firestore for database 
>>>>>>> 4288f775a85d65d00a7acc6deee40e30d1b420e6
