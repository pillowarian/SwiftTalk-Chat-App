# SwiftTalk Chat App 🗨️

A real-time mobile chat application built with **Kotlin** and **Firebase**, designed to offer a clean messaging experience with smooth UX and scalable architecture.

---

## 🚀 Features

- Real-time messaging using **Firebase Firestore**
- MVVM architecture with **ViewModel** and **LiveData**
- Background operations with **Kotlin Coroutines**
- **Dependency injection** using Hilt
- Push notifications via **Firebase Cloud Messaging**
- User authentication and profile support

---

## 📂 Project Structure

SwiftTalk-Chat-App/  
├── app/                    # Android app module  
│   ├── src/  
│   │   ├── main/  
│   │   │   ├── java/...    # Kotlin source code  
│   │   │   ├── res/...     # Layouts, drawables, strings, etc.  
│   │   └── AndroidManifest.xml  
├── build.gradle            # Module Gradle config  
├── settings.gradle         # Settings for Gradle  
└── README.md               # Project documentation  


---

## 🔧 Tech Stack

- **Kotlin**
- **Firebase Firestore** + **Firebase Cloud Messaging**
- **Android Jetpack**: ViewModel, LiveData
- **Hilt** for dependency injection
- **Coroutines** for async tasks
- **Material Design** components

---

## ⚙️ Getting Started

**Prerequisites:**
- Android Studio Bumblebee or later
- Android SDK and emulator/device
- A Firebase project (configured for Firestore and FCM)

**Steps:**
1. **Clone the repo**  
   `git clone https://github.com/pillowarian/SwiftTalk-Chat-App.git`  
   `cd SwiftTalk-Chat-App`
2. **Open in Android Studio**  
   - Use “Open an Existing Project” and select the root.
3. **Configure Firebase:**  
   - Add your `google-services.json` under `app/`.
   - Enable Firestore & Cloud Messaging in Firebase Console.
4. **Build & Run**  
   - Let Gradle sync, then install on a device/emulator.

---

## 🧠 What I Learned

- Integrating Firebase for messaging and notifications  
- Structuring an app with **MVVM** + **Hilt**  
- Handling asynchronous data with **Coroutines**
- Managing lifecycle-aware components via LiveData & ViewModel  
- Deploying a functional chat app with modern Android practices

---

## 🛠️ Future Improvements

- Implement private & group chats
- Add **end-to-end encryption**
- Store user avatars/images
- Create polished UI themes and animations
- Improve offline support with Firestore persistence

---

## 📬 Contact Me

- 📧 Email: pillowtalkerarian@gmail.com  
- 💼 LinkedIn: [md-hasin-anjum-arian](https://www.linkedin.com/in/md-hasin-anjum-arian-6820a92a9)  
- 🧑‍💻 GitHub: [pillowarian](https://github.com/pillowarian)

---

## 📄 License

Licensed under the **MIT License**. See [LICENSE](LICENSE) for details.
