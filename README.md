# RideIQ 🚀

RideIQ is a premium Flutter application designed for ride-sharing intelligence and gig worker optimization. It follows a robust architecture to ensure scalability and high performance across iOS, Android, and Web.

## 🛠 Tech Stack

- **Framework:** [Flutter](https://flutter.dev/) (SDK ^3.9.2)
- **State Management:** [Riverpod](https://riverpod.dev/) (with Code Generation)
- **Architecture:** MVVM + Clean Architecture
- **Networking:** [Dio](https://pub.dev/packages/dio)
- **Data Modeling:** [Freezed](https://pub.dev/packages/freezed) & [JSON Serializable](https://pub.dev/packages/json_serializable)
- **Backend Services:** Firebase (Auth, Core)
- **UI & Animations:** 
  - [Flutter Animate](https://pub.dev/packages/flutter_animate)
  - [Flutter SVG](https://pub.dev/packages/flutter_svg)
  - [Elegant Notification](https://pub.dev/packages/elegant_notification)
  - [Figtree Font](https://fonts.google.com/specimen/Figtree)
- **Integration:** [Truv](https://truv.com/) (Payroll & Employment Verification)

## ✨ Key Features

- **Multi-Platform Integration:** Support for Uber, Lyft, and Ayro platform data.
- **Smart Analytics:** Real-time earnings and productivity tracking for gig workers.
- **Secure Authentication:** Firebase-powered secure login and profile management.
- **Income Verification:** Seamless employment and income verification via Truv.
- **Premium UI:** Modern, responsive design with smooth micro-animations and custom typography.

## 🏗 Architecture Overview

The project adheres to **MVVM (Model-View-ViewModel)** combined with **Clean Architecture** principles.

- **View:** UI components using `ConsumerWidget`.
- **ViewModel:** Business logic and state handling using Riverpod Notifiers.
- **Repository:** Data abstraction layer for API and local storage.
- **Model:** Immutable data classes generated with Freezed.

For detailed development guidelines, refer to [ARCHITECTURE_RULES.md](./ARCHITECTURE_RULES.md).

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (^3.9.2)
- Android Studio / VS Code
- Firebase Project setup

### Installation

1. **Clone the repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Install dependencies:**
   ```bash
   flutter pub get
   ```

3. **Generate code (Riverpod, Freezed, etc.):**
   ```bash
   dart run build_runner build --delete-conflicting-outputs
   ```

4. **Run the application:**
   ```bash
   flutter run
   ```

---
Built with ❤️ by the DevelopersAequitas Team.
