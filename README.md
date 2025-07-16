![Cover](https://github.com/user-attachments/assets/06413b08-1f7c-47eb-af75-061541b98d55)

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0"><img alt="License" src="https://img.shields.io/badge/License-Apache%202.0-blue.svg"/></a>
  <a href="https://android-arsenal.com/api?level=24"><img alt="API" src="https://img.shields.io/badge/API-24%2B-brightgreen.svg?style=flat"/></a>
  <a href="https://github.com/kamyab9k"><img alt="Profile" src="https://img.shields.io/badge/GitHub-Kamyab%20Khosravi-blue?style=flat&link=https%3A%2F%2Fgithub.com%2Fkamyab9k"/></a>
<a href="https://www.linkedin.com/in/kamyab-khosravi-5214551a4/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white"/></a>
  <a href="https://medium.com/@kamyab9k"><img alt="Medium" src="https://img.shields.io/badge/Medium-12100E?logo=medium&logoColor=white"/></a></p>

**FitCore: Home Workouts & AI Coach** demonstrates the integration of [AI](https://ai.google.dev/) with Fitness on Android 

The primary objective of this application is to showcase the following:

- Demonstrating the integration of AI capabilities for personalized fitness coaching and insights.
- Categorized exercises based on usesr's fitness level and goal.
- Track user steps with phone's sensors and provide weekly data chart.
- calorie counter - distance tracker - dynamic BMI calculater and more

## 📷 Previews

<p align="center">
<img src="previews/preview0.png" alt="drawing" width="270px" />
<img src="previews/preview1.png" alt="drawing" width="270px" />
<img src="previews/preview2.gif" alt="drawing" width="269px" /></br>
</p>

<a href="https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=&utm_term=DevRelOss">
</a>

## 🛥 Download and enjoy!

- [FitCore: Home Workouts & AI coach.apk](www.google.com)


## 💻 Setup 

Experience a seamless and personalized fitness journey starting with our intuitive setup screens, secure user authentication, and smart data-driven personalization.

1. **Amazing UI for Onboarding & setup**: Dive into your fitness journey with a visually stunning and highly intuitive setup process.
2. **Secure User Management**: Secure user authentication, including convenient "Forgot Password" and other account management features.
3. **Deep Personalization**: Every piece of your user information is intelligently leveraged to create a truly personalized fitness experience and workout programs just for you.


## 💻 Personalized workouts

Your ultimate workout companion, offering personalized plans with dynamic exercise difficulty and live instructor-led sessions to help you crush your fitness goals:

1. **"For You" Personalized Program**: Receive a unique workout program specifically designed for you, considering your fitness goals, current level, and other key preferences.
2. **Adaptive Exercise Difficulty**: The difficulty of exercises adjusts dynamically based on your fitness level (captured during setup) to ensure the most effective and engaging experience.
3. **Comprehensive Workout Details**: Every workout program provides a set of exercises, complete with additional information like estimated calorie burn and more
4. **Muscle Group Specific Exercises**: Each muscle group comes with its own dedicated set of exercises, allowing for targeted and effective training.


   
## ⚙️ Step tracker

Your personal health companion, accurately tracking your steps, distance, and calories burned, all visualized in clear daily and weekly charts.

1. **Sensor-Based Tracking**: Utilizes your device's internal sensors for precise step counting.
2. **Progress Charts**: Offers intuitive daily and weekly charts to visualize your step activity and progress over time.
3. **Calorie Expenditure**: Provides an estimate of the calories you've burned through your steps.
4. **Distance Measurement**: Automatically calculates the distance you've walked or run.


##  Live Workout Sessions

Join our live workout sessions for real-time, instructor-led guidance and an immersive fitness experience.

1. **Interactive Live Sessions**: Engage in live workout sessions where you can follow along with an instructor's video, guiding you through each exercise.(Due to Iran's policy of Censoring Youtube Platform, this feature will be impacted with IPs from this region)



## 💻 AI Coach

Your intelligent AI Coach, providing personalized advice and plans across all aspects of health, fitness, and nutrition to guide your wellness journey

1. **Personalized Wellness Partner**: Get smarter about your health with an AI that provides customized advice and actionable plans for fitness, food, and overall well-being.
2. **Your Fitness Q&A Hub**: Instantly get answers to all your fitness questions, empowering you with the knowledge to make informed decisions and overcome challenges.
3. **Multilanguage Model**: Ask your question in ***40*** languages and your AI fitness coach will answer.

### Out of Region(429 Error)
If you encounter this error from the outset, it's likely that your rate limits do not meet the requirements. Please revisit step 16 in the guidelines above for further instructions.

### No network(499 Error)
If you encounter this error from the outset, it's likely that your rate limits do not meet the requirements. Please revisit step 16 in the guidelines above for further instructions.

### unrelated question(555 Error)
If you encounter this error from the outset, it's likely that your rate limits do not meet the requirements. Please revisit step 16 in the guidelines above for further instructions.


## 💻 Fitness Overview and Insights


Track your key health metrics and gain valuable insights into your progress with our dynamic fitness overview
1. **Your Metric Display**: View your current weight, recommended healthy weight, and BMI at a glance.
2. **Dynamic BMI Card**: Your BMI card updates automatically and instantly whenever you log a change in your current weight, keeping your insights always current.


## 💻 theme customization

Track your key health metrics and gain valuable insights into your progress with our dynamic fitness overview
1. **Dark mode**: View your current weight, recommended healthy weight, and BMI at a glance.



## 🛠 Tech Stack & Open Source Libraries
- Minimum SDK level 24.
- 100% [Jetpack Compose](https://developer.android.com/jetpack/compose) based + [Coroutines](https://github.com/Kotlin/kotlinx.coroutines) + [Flow](https://kotlin.github.io/kotlinx.coroutines/kotlinx-coroutines-core/kotlinx.coroutines.flow/) for asynchronous and cold streams.
- [Compose Messaging](https://getstream.io/chat/sdk/compose?utm_source=Github&utm_medium=Jaewoong_OSS&utm_content=Developer&utm_campaign=Github_April2024_Jaewoong_ChatGPT&utm_term=DevRelOss): The Jetpack Compose  is built on a low-level chat client and provides modular, customizable Compose UI components that you can easily drop into your app.
- [Gemini](https://platform.openai.com/docs/api-reference/chat): Given a messages, the model will return a response.
- Jetpack
  - Compose: Android’s modern toolkit for building native UI.
  - ViewModel: UI related data holder and lifecycle aware.
  - App Startup: Provides a straightforward, performant way to initialize components at application startup.
  - Navigation: For navigating screens and [Hilt Navigation Compose](https://developer.android.com/jetpack/compose/libraries#hilt) for injecting dependencies.
  - Room: Constructs Database by providing an abstraction layer over SQLite to allow fluent database access.
  - [Hilt](https://dagger.dev/hilt/): Dependency Injection.
  - [WorkManager](https://developer.android.com/topic/libraries/architecture/workmanager): To achieve background processing with scheduling.
- [Landscapist Glide](https://github.com/skydoves/landscapist#glide), [animation](https://github.com/skydoves/landscapist#animation), [placeholder](https://github.com/skydoves/landscapist#placeholder): Jetpack Compose image loading library that fetches and displays network images with Glide, Coil, and Fresco.
- [Retrofit2 & OkHttp3](https://github.com/square/retrofit): Construct the REST APIs and paging network data.
- [ksp](https://github.com/google/ksp): Kotlin Symbol Processing API.
- [viewmodel-lifecycle](https://github.com/skydoves/viewmodel-lifecycle): ViewModel Lifecycle allows you to track and observe Jetpack's ViewModel lifecycle changes.

## 🏛️ Architecture

**Fitcore** follows the [Google's official architecture guidance](https://developer.android.com/topic/architecture).

![architecture](figures/figure0.png)

**Fitcore** was built with [Guide to app architecture](https://developer.android.com/topic/architecture), so it would be a great sample to show how the architecture works in real-world projects.<br>

The overall architecture is composed of two layers; UI Layer and the data layer. Each layer has dedicated components and they each have different responsibilities.
The arrow means the component has a dependency on the target component following its direction.

### Architecture Overview

![layer](figures/figure1.png)

Each layer has different responsibilities below. Basically, they follow [unidirectional event/data flow](https://developer.android.com/topic/architecture/ui-layer#udf).

### UI Layer

![layer](figures/figure2.png)

The UI Layer consists of UI elements like buttons, menus, tabs that could interact with users and [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) that holds app states and restores data when configuration changes.

### Data Layer

![layer](figures/figure3.png)

The data Layer consists of repositories, which include business logic, such as querying data from the local database and requesting remote data from the network. It is implemented as an offline-first source of business logic and follows the [single source of truth](https://en.wikipedia.org/wiki/Single_source_of_truth) principle.<br>

For more information about the overall architecture, check out **[Clone With Jetpack Compose]()**.

## Fire Base

![modules](figures/figure4.png)

**FitCore** adopted modularization strategies below:

- **Reusability**: Modulizing reusable codes properly enable opportunities for code sharing and limits code accessibility in other modules at the same time.

- **Parallel Building**: Each module can be run in parallel and it reduces the build time.

- **Decentralized focusing**: Each developer team can assign their dedicated module and they can focus on their own modules.




## 🤝 Contribution

Email or contact me on [Linkedin](https://www.linkedin.com/in/kamyab-khosravi-5214551a4/) for collaboration

## Find this app exciting? 💙
Support it by following __[follow me](https://www.linkedin.com/in/kamyab-khosravi-5214551a4/)__ on Linkedin! 🤩

# License
```xml

```
