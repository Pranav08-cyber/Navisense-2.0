# Navisense-2.0
![WhatsApp Image 2025-03-23 at 17 46 59_7f9c35ca](https://github.com/user-attachments/assets/5a002b1d-cc5c-4389-8d58-8ef1bca3d96d)

# 🚦 NaviSense – Smarter, Sustainable Navigation for India

**NaviSense** is an AI-powered navigation and mobility assistant tailored for India’s unique traffic and infrastructure. It combines real-time data, predictive analytics, gamification, and voice control to transform how users travel in cities.

> 🏆 5th Position – SOLVIT 2025 Hackathon | Over 150+ teams  
> 🌱 Finalist – Sustainable Transportation & Infrastructure Ideathon  

---

## 🌟 Key Modules & Tech Stack

| 🔧 Module                  | 💡 Description                                                                 | 🧪 Technologies Used                                                                 |
|---------------------------|---------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| **GreenPath & FlowView**  | Real-time routing with congestion awareness                                    | Google Maps Directions API, Traffic API, Distance Matrix API                         |
| **Mala (LocationIQ)**     | Geocoding, reverse geocoding, and place autocomplete                          | LocationIQ APIs                                                                      |
| **NaviBuddy**             | AI voice assistant for hands-free navigation                                  | OpenAI GPT-4 + Whisper APIs                                                          |
| **Local Pulse**           | Crowdsourced incident reporting and alerts                                    | Firebase Realtime DB, Google Maps, Push Notifications                                |
| **QuestMaster**           | Gamified experience with rewards, streaks, and levels                         | Firebase Auth, Firestore, Firebase Analytics                                         |
| **SpotGuard**             | Smart parking timers and travel reminders                                     | Local Notification APIs, Firebase Cloud Messaging                                    |
| **ParkOracle**            | Predictive parking availability with intelligent recommendations              | Google Places API or ParkWhiz + Firebase ML Kit / TensorFlow Lite                    |
| **UI/UX & Mobile Design** | Clean, animated, intuitive mobile-first design                                | React Native, Tailwind CSS, Lottie, Framer Motion                                    |

---

## 📱 App Highlights

- 🛣️ **GreenPath Navigation:** AI-enhanced traffic-aware route suggestions  
- 🎙️ **Voice-Powered NaviBuddy:** Navigate & ask questions hands-free  
- 📍 **Mala Smart Search:** Seamless location autocomplete & place search  
- 🔔 **Local Pulse Alerts:** Stay informed with real-time, local reports  
- 🧠 **ParkOracle Predictions:** Find parking before you arrive  
- 🕹️ **Gamified Travel (QuestMaster):** Earn rewards as you travel smart  
- ⏰ **SpotGuard Reminders:** Never forget your parked location or meter time  

---

## 🚀 Getting Started

```bash
# Clone the repository
git clone https://github.com/your-username/navisense.git
cd navisense

# Install dependencies
npm install

# Run the app (React Native)
npx react-native run-android   # or run-ios
