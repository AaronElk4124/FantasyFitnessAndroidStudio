# Fantasy Fitness

**Fantasy Fitness** is a fitness-focused Android app designed to enhance users' fitness journeys. The app incorporates Firebase for user authentication and database management, alongside various engaging features for tracking progress and customizing user experiences.

---

## Features

- **User Authentication**: 
  - Secure user login and registration with Firebase Authentication.
  - Handles user sessions seamlessly.

- **Database Management**: 
  - Stores and retrieves user data using Firebase Realtime Database/Firestore.
  - Tracks activity preferences, progress, and other user-specific settings.

- **Fitness Tracking**:
  - Allows users to log activities and monitor progress over time.

- **Intuitive Navigation**: 
  - Utilizes a `BottomNavigationView` for smooth transitions between activities like `MainActivity`, `ExerciseActivity`, and `ProfileActivity`.

- **Permissions**:
  - Requests location and camera permissions to enhance app functionality.
  - Handles permission denial gracefully and ensures the app remains user-friendly.

- **Media Integration**:
  - Blurs and modifies images, providing a unique visual twist to user-uploaded media.

---

## Tech Stack

- **Languages**: Java, XML  
- **Backend**: Firebase Authentication, Firebase Realtime Database/Firestore  
- **UI/UX**: Material Design with customized button styles  
- **Tools**: Android Studio, Gradle  

---

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FantasyFitness.git
   cd FantasyFitness
