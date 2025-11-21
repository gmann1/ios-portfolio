# Gabriel Mann – iOS Engineering Portfolio

Senior iOS Engineer with 10+ years of experience shipping polished, high-performance apps used by millions.  
I specialize in modern Swift, SwiftUI, UIKit, structured concurrency, complex UI/UX, payments, modular architectures, and building reliable, scalable production systems.

Below is a collection of shipped App Store apps and detailed examples of my technical contributions.

---

# 📱 Shipped Apps & Major Contributions

## **Empower Personal Wealth**
**App Store:** [Empower](https://apps.apple.com/us/app/empower/id1001257338)

### **Key Contributions**
- **Login Performance Overhaul (14s → 4s)**  
  - Added Firebase Traces to diagnose slow paths  
  - Implemented caching layers + background processing  
  - Parallelized multiple API calls using Swift concurrency  
  - Eliminated redundant network calls  
  - Added retry/backoff logic with async/await  
  Rolled out improvements safely using feature flags with measurable performance gains.

- **Shared Swift Pod Architecture**  
  Designed and implemented a modular shared pod powering:  
  - analytics  
  - performance monitoring  
  - update prompts  
  - remote configuration  
  This significantly reduced code duplication across teams.

- **UI/UX & Transitions**  
  Created polished SwiftUI & UIKit components, animations, matched-geometry transitions, and adaptive iPhone/iPad layouts.

- **Performance & Reliability**  
  Used Instruments to remove layout jank, reduce main-thread work, and improve overall responsiveness.

---

## **Funraise – Nonprofit Donation Platform**
**App Store:** [Funraise](https://apps.apple.com/us/app/funraise/id1441342210)

### **Key Contributions**
- **End-to-End Ownership**  
  Sole developer and maintainer of the entire iOS app (Swift, MVVM), including architecture, UI, performance, and release processes.

- **Payment Reader Integrations (Stripe + PayPal)**  
  - Integrated Stripe Terminal for in-person payments  
  - Worked directly with Stripe & PayPal engineers on their latest APIs  
  - Built **Auto-Connect** for Bluetooth readers to solve connection issues in field operations

- **Volunteer Mode – Secure Scoped Access**  
  - Designed encrypted access tokens  
  - Shared via QR code  
  - Scoped by time + permissions  
  Eliminated nonprofits’ unsafe practice of sharing login credentials.

- **Push Notifications**  
  Added engagement and task-related alerts to improve user workflows.

- **Custom UI Components**  
  Built reusable UIKit and SwiftUI components, with animated transitions and responsive layouts.

---

## **Giving App (Funraise)**
**App Store:** [Giving by Funraise](https://apps.apple.com/us/app/giving-by-funraise/id1552050104)

### **Key Contributions**
- **AWS Cognito Integration**  
  Added secure authentication and token lifecycle management.

- **Donation & Subscription Management**  
  Built intuitive flows for creating, updating, and managing recurring contributions.

- **Website Management Tools**  
  Allowed nonprofits to edit and manage their websites directly from the app.

- **MVVM Architecture**  
  Modular, testable structures shared across multiple product surfaces.

---

# 🎨 UI / UX Capabilities

Demonstrated across all shipped apps:

- Custom SwiftUI animations & transitions  
- UIKit + Core Animation motion design  
- Matched-geometry effects  
- Reusable component libraries (SwiftUI & UIKit)  
- Adaptive layouts (Dynamic Type, iPad, size classes)  
- Smooth navigation, gestures, and polished transitions  
- Snapshot testing for visual accuracy  
- Strong accessibility (VoiceOver, focus order, labels)  
- Internationalization & localization support  

---

# 🧰 Technical Skills

### **Mobile Development**
- iOS (Swift, SwiftUI, UIKit, Combine, async/await, Actors, Sendable, Structured Concurrency)  
- Android  
- Flutter  
- Xamarin  

### **Architecture & Patterns**
- MVVM  
- Coordinators  
- Modular Architecture  
- Swift Packages  
- SOLID  
- Dependency Injection  
- Clean Architecture  

### **Tooling / DevOps**
- CI/CD (Xcode Cloud, GitHub Actions)  
- Fastlane  
- JIRA  
- Firebase (Crashlytics, Performance, Remote Config)  
- Feature Flags  
- XCTest, UI Tests, Snapshot Tests  
- Xcode Instruments  

### **Networking**
- URLSession + async/await  
- REST  
- SOAP  
- Background tasks  
- Caching layers  
- Parallel network pipelines  
- Retry/backoff logic  
- WebSockets  

### **Programming Languages**
Swift, Objective-C, Java, Kotlin, Dart, JavaScript, C#, Python, PHP, SQL, HTML, XML

### **Other Technology Experience**
- Stripe Terminal  
- PayPal readers  
- AWS Cognito/Auth  
- Blockchain fundamentals  
- Secure QR flows  
- Push Notifications  
- App Extensions  
- watchOS  
- iMessage Apps  

---

If you'd like more details about any specific project, architecture decision, or technical deep dive, feel free to reach out.
