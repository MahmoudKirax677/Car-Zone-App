# CarZone App

**Description**:  
CarZone is a mobile application designed to facilitate communication between car service centers and car owners. The app allows users to easily connect with service providers to inquire about available services, locations, and other details. The app is developed using **Flutter** with a focus on responsive design and high performance. It supports both **Arabic** and **English** languages, ensuring accessibility for a broader user base.

**Technologies Used**:
- **Flutter**: Cross-platform development for Android and iOS.
- **Cubit (Bloc)**: State management for handling UI updates and business logic.
- **Firebase Cloud Messaging (FCM)**: For sending real-time notifications to users.
- **Google Maps API**: For displaying the locations of service centers on the map and helping users navigate.
- **Google Places API**: For managing location input and providing relevant location suggestions.
  
**Key Features**:
- **Service Center Communication**: Users can directly communicate with service providers to get information about car services.
- **Real-time Notifications**: Get notified about updates from service providers or relevant information using FCM.
- **Google Maps Integration**: View nearby car service centers and get directions to them.
- **Responsive Design**: Ensures optimal user experience across various devices.
- **Bilingual Support**: The app fully supports both **Arabic** and **English**.

**Architecture**:
- The app follows a **Clean Architecture** pattern, ensuring maintainability, scalability, and testability.
- **Cubit** is used for state management, allowing efficient data handling and smooth UI interactions.
- **Repository Pattern** is used for managing data sources, ensuring separation of concerns between the business logic and data handling.

**Notification System**:
- Notifications are sent to users for updates or messages from service providers via **Firebase Cloud Messaging (FCM)**.
  
**User Types**:
- **Car Owners**: Can connect with car service centers to inquire about services and locations.
- **Service Providers**: Use a dedicated interface to respond to user inquiries and manage their presence on the platform.

**App Links**:
- [Google Play Store - CarZone](https://play.google.com/store/apps/details?id=com.bold.carzone.carzone)
- [Apple App Store - CarZone](https://apps.apple.com/sa/app/car-zone-community/id6471982862)
- [CarZone Website](https://www.carzone.app/)

**Live Demo**:  
Due to confidentiality, the source code is not available. However, a live demo can be presented using **Android Studio Emulator** or **TestFlight** for iOS. You may request access to a testing environment for further review.

