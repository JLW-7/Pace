# 💪 Pace — Your Personalized Fitness Companion

A motivational fitness iOS app to track workouts and fuel progress through personalized, workout, recovery, nutrition suggestions and daily inspiration.

---

## Features

### 🏋️ Workout Logging
- Log custom workouts across multiple sports (e.g., swimming, running, gym)
- Track workout duration, intensity, and type
- Visual training calendar with summaries

### 🔁 Recovery Insights
- Weekly workout summaries
- Smart rest tracking and recovery prompts
- Progress charts to avoid burnout and stay balanced

### 🍎 AI-Based Workout/Recovery/Nutrition Suggestions
- GPT-powered post-workout nutrition tips
- Suggestions tailored to workout intensity and recovery needs
- Optional food log for diet reflection

### 💡 Motivation & Reflection
- Daily motivational quotes delivered via notifications
- Journaling space to reflect on workouts and goals
- Milestone tracking to celebrate progress


## Tech Stack

- **Language**: Swift + SwiftUI  
- **Data Storage**: CoreData (or Firebase – optional)  
- **AI Integration**: OpenAI GPT API for smart suggestions  
- **Notifications**: UNUserNotificationCenter  
- **Charts**: Swift Charts (or Charts library)


## Sample GPT Prompt
> “The user completed a 45-minute HIIT workout today and had a heavy swim session yesterday. Suggest a recovery-focused nutrition plan including hydration, carbs, and protein.”


## Setup

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/flowcoach.git
   ```
2. Open `Pace.xcodeproj` in Xcode
3. Add your OpenAI API key in `Secrets.swift` (create if needed)
4. Run on a simulator or physical device (iOS 16+ recommended)


## Contributions

Contributions are welcome! If you want to help improve **Pace**, here’s how you can get involved:

1. Fork this repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to your branch (`git push origin feature/YourFeature`)
5. Open a Pull Request and describe your changes

Please make sure your code follows the app’s existing style and includes tests for any new features. For significant changes, open an issue first to discuss what you’d like to implement!

___

Enjoy using Pace! 

