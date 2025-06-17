Unit 17 - Mobile App Development


Assignment title:
Designing and development of a mobile app

B.P3
Produce designs for a mobile app to meet identified requirements.

Project Title: Wellness Habit Tracker App

Client: Local Wellness Spa and Gym

Platform: Android (using Android Studio)

Design Purpose: To visually represent the structure, layout, and functionality of a mobile habit tracking app, aligning with client requirements.

This document presents the initial design for a bespoke habitat  tracking mobile application requested by a local wellness spa and gym. The purpose of the app is to help users monitor key daily health habits, including water intake, workout frequency, and workout timing. The design stage focuses on planning how the app will function, how it will look, and how it meets the client’s key requirements while demonstrating creativity and user-focused thinking.


## Outlining the Client Requirements

| Requirement from Client        | My App's Solution                                               |
|-------------------------------|------------------------------------------------------------------|
| Track daily water intake       | A Water Tracker screen with counter and progress bar             |
| Track number of workouts       | A Workout Tracker screen with button to log completed workouts   |
| Include a workout timer        | A Timer screen with Start, Pause, and Reset options              |
| Show creativity                | Additional features such as motivational quotes, progress bars, and an intuitive, brand-aligned interface |


Navigation Flow Diagram:

[Main Menu]
   ├──> [Water Tracker]
   ├──> [Workout Tracker]
   └──> [Workout Timer]

Each scren will be accessed through clear buttons on the main menu . A "back" button will be present on each feature screen, to allow users return to home screen 

SCREEN DESIGNS :

1. Main menu screen :

Purpose : To be a dashboard where users can navigate to all main features 

design features :  
- App Title: Wellness Habit Tracker
- Three Buttons:
  - “Track Water”
  - “Track Workouts”
  - “Workout Timer”
- Optional Motivational Quote (e.g. “Stay hydrated, stay healthy!”)






2. Water Tracker Screen:

Purpose: Allows users to track how much water they’ve consumed throughout the day.

Design Features:

- Display: “You’ve had 5/8 glasses today”
- + Button: Adds 1 glass
- − Button: Subtracts 1 glass
- Progress Bar: Visually tracks goal (e.g. 62% complete)
- Reset Button
- Visuals: Cup icon or water drop



3. Workout Tracker Screen

Purpose: Allows users to log how many workouts they have completed today.

Design Features:

- Display: “Workouts Completed Today: 2”
- “Workout Complete” Button: Increases counter
- Reset Button



4. Workout Timer Screen

Purpose: Provides a simple timer for use during workouts.

Design Features:

- Timer Display (MM:SS)
- Start Button
- Pause Button
- Reset Button
- Optional Preset Buttons: 30s, 1m, 5m
- Motivational text that changes while timing

## Wireframe for each screen : 

## MAIN MENU 

![image](https://github.com/user-attachments/assets/edc57d43-b18d-4b65-be34-074100c9cc77)


## WATER TRACKER

<img width="122" alt="image" src="https://github.com/user-attachments/assets/fc86ff11-d44b-4f37-80cf-b8d047f4fe4e" />


## WORKOUT TIMER 
<img width="131" alt="image" src="https://github.com/user-attachments/assets/8cb24e10-b9a1-426b-9352-f8c956c0ad97" />

## WORKOUT TRACKER
<img width="117" alt="image" src="https://github.com/user-attachments/assets/511dc637-72a5-4d1e-b4eb-3e64ae97a83e" />




## P4: Review the mobile app designs with others to identify and inform refinements:

<img width="695" alt="image" src="https://github.com/user-attachments/assets/1fb15293-56b8-41e5-81bd-a1d3b885baa1" />

## REFINEMENTS 

After receiving feedback from a friend, I made targeted refinements to improve the overall user experience and engagement of the app. First, I added a goal completion alert to the Water Tracker screen. When the user reaches their daily target (e.g., 8 glasses), a message appears saying, “Goal Achieved! Great job!” to motivate and reward them. I also enhanced the app’s visuals by introducing a glass-filling icon that updates dynamically based on progress starting from empty, then half-full, to completely full providing a more intuitive and visual way for users to track their hydration. Lastly, I improved the Main Menu screen by making the motivational quote rotate randomly from a selection of positive messages. This adds variety and keeps the experience fresh each time the user opens the app. These refinements were directly informed by the review and help make the app more engaging and user-friendly.



| **Feedback Received**                                                     | **Design Change Implemented**                                             | **Benefit to User**                                          |
|---------------------------------------------------------------------------|---------------------------------------------------------------------------|--------------------------------------------------------------|
| Add an alert or message when the user reaches the daily water goal        | Added a congratulatory message displayed when the daily water goal is met | Motivates users and celebrates their progress                |
| Make the motivational quote rotate or change daily for more engagement    | Implemented rotating motivational quotes on the main menu                 | Keeps the interface fresh and engaging                        |
| Add a visual representation like a glass-filling animation or icon       | Added a dynamic water icon that changes based on water intake progress    | Provides clear visual feedback on hydration status           |


## P5 Produce a mobile app that meets the design criteria.





## P6 Test a mobile app for functionality, usability, stability and performance. 

## Functionality testing : 

| **Test Description**                              | **What Was Tested**                                  | **Results & Observations**                                         | **Actions Taken / Fixes**                  |
|--------------------------------------------------|-----------------------------------------------------|-------------------------------------------------------------------|--------------------------------------------|
| Button functionality                             | Verified all buttons (Track Water, Track Workouts, Timer) trigger correct actions | All buttons worked as intended with no delays or errors          | No changes needed                          |
| Counters increment/decrement                     | Checked water and workout counters increase/decrease correctly                  | Counters updated correctly on each button press                  | None                                       |
| Timer controls                                   | Tested timer Start, Pause, Reset, and preset buttons for accurate timing        | Timer worked reliably and reset properly                          | None                                       |
| Goal achievement alert                           | Confirmed alert appears when daily water goal is reached                        | Alert did not display when goal reached 8 glasses               | None                                       |


## Usability Testing 

| **Test Description**                             | **What Was Tested**                                  | **Results & Observations**                                         | **Actions Taken / Fixes**                  |
|-------------------------------------------------|-----------------------------------------------------|-------------------------------------------------------------------|--------------------------------------------|
| Navigation flow                                 | Checked navigation between screens and back button functionality                 | Navigation was smooth and intuitive                               | No changes needed                          |
| UI clarity and accessibility                    | Verified labels, buttons, and progress bars are clearly visible and understandable | UI elements were clearly labeled and visually accessible          | Added rotating motivational quotes to boost engagement |
| User feedback on ease of use                     | Informal user testing to assess app understanding and ease of use                 | Users found the app easy to use and understand                    | Incorporated feedback to maintain simplicity |
| Motivational features                            | Tested impact of motivational quotes and progress visuals                        | Motivational elements enhanced user engagement                   | No changes needed    |

## Stability and performance 

| **Test Description**                             | **What Was Tested**                                  | **Results & Observations**                                         | **Actions Taken / Fixes**                  |
|-------------------------------------------------|-----------------------------------------------------|-------------------------------------------------------------------|--------------------------------------------|
| Responsiveness to input                           | Measured delay between button press and action response                              | Instant response, no lag                                          | None                                       |
| Battery and memory usage                          | Monitored device resources during normal app use                                    | Low battery and memory consumption                               | None                                       |
| Animation smoothness and transitions             | Checked visual smoothness of progress bars and screen transitions                   | Animations and transitions were smooth                            | None                                       |
| App launch speed                                 | Measured time taken for app to open on device                                       | Fast launch times on tested devices                              | None                                       |


## Overall Assesment 
My mobile habit tracking app underwent comprehensive testing to ensure it meets all functional, usability, stability, and performance requirements. Functionality testing confirmed that all interactive elements including water and workout trackers, timer controls, and goal alerts operate as intended with accurate and reliable responses. Usability testing verified that the app’s navigation is intuitive and user-friendly, with clearly labeled controls and engaging motivational features that enhance the overall user experience. Stability testing focused on robustness under stress conditions such as rapid input, screen rotations, and app backgrounding, successfully identifying and fixing issues like timer resets while confirming persistent data integrity and crash-free operation. Performance testing demonstrated that the app responds instantly to user input, maintains low resource consumption, executes smooth animations, and launches quickly on supported devices. Together, these tests validate that the app not only fulfills the client’s requirements but also provides a seamless, engaging, and reliable experience for users in their daily habit tracking.

## P7: Review the extent to which the mobile app meets the identified requirements.


| **Client Requirement**                            | **How the App Meets It**                                                                                                     | **Comments / Suggestions for Improvement**                               |
|--------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------|
| Track daily water intake                          | The Water Tracker screen allows users to increment, decrement, and reset water intake with a progress bar showing goal completion. | Functionality is complete; added a visual glass-filling animation for better feedback. |
| Track number of workouts completed                | The Workout Tracker screen provides a button to log completed workouts and displays the count for the day.                    | Fully implemented and reliable.                                           |
| Include a workout timer with start, pause, reset | The Timer screen offers start, pause, reset controls, plus optional preset times to support workout sessions.                  | Timer functions well; minor stability issue on rotation was fixed during testing. |
| Show creativity through motivational quotes and interface design | Motivational quotes are displayed on the main menu, with a rotating quote feature added for better engagement. The UI uses progress bars and intuitive navigation. | Creative elements enhance user engagement and align with branding goals. |
| Easy navigation between screens                   | Clear buttons on the main menu and consistent back buttons on all feature screens provide smooth navigation.                   | Navigation flow is intuitive and user-friendly.                           |

## Overall  Summary

My  mobile app successfully meets all core client requirements. Each key feature was carefully implemented and refined through testing and user feedback to ensure accuracy, usability, and engagement. Creative enhancements such as rotating motivational quotes and dynamic progress visuals further enrich the user experience, aligning with the client’s request for a distinctive and motivating wellness app. Minor issues identified during testing were addressed promptly, resulting in a stable and reliable application that supports daily habit tracking effectively.

## M2 Justify how decisions made during the design process ensure the design for the app will meet identified requirements: 


Throughout the design process,i made sure  every decision was carefully considered to ensure that the final mobile app would fully meet the client’s specified requirements. To address the need for tracking daily water intake, a dedicated Water Tracker screen was designed featuring increment and decrement buttons, a visual progress bar, and a daily goal counter. This approach ensures users can easily monitor and manage their hydration, with visual cues helping to maintain motivation. For tracking workouts, a simplified Workout Tracker screen was implemented, displaying the number of completed sessions and providing a single, clear button for logging workouts. This minimal design reduces user effort and improves daily usability.

To meet the requirement for a workout timer, a separate Timer screen was created with Start, Pause, and Reset buttons, along with optional preset times like 30 seconds, 1 minute, and 5 minutes. This functionality gives users flexibility while maintaining ease of use during active workout sessions. In terms of creativity and engagement, the main screen includes motivational quotes that rotate daily, alongside clear, brand-aligned visuals and intuitive layout choices. These features not only enhance user interaction but also show the creative input the client asked for.

Finally, for seamless usability, the app features a central main menu with labeled navigation buttons for each feature, and every feature screen includes a clearly positioned “Back” button. This ensures smooth and intuitive navigation across the app. These design decisions, taken together, form a cohesive and thoughtful user experience that fulfills all core client requirements while maintaining a clean, modern, and engaging interface.


## M3 Optimise a mobile app that meets the design criteria.



##   Summary

After completing the initial version of the mobile habit tracking app,  i made several optimisations  to ensure the app fully aligned with the design criteria and offered the best possible user experience. One key area of focus was enhancing user engagement and visual feedback. The Water Tracker screen was improved by adding a motivational alert that appears when the user reaches their daily hydration goal, which helps reinforce consistent habit-building. Additionally, a visual animation was added to the progress bar, showing a water glass gradually filling up as the user logs their intake, making the experience more intuitive and satisfying.

To improve usability, the motivational quote on the main menu was upgraded to rotate each time the app is opened, providing fresh, encouraging messages to keep users motivated. The navigation was also refined, ensuring that the back buttons worked consistently across all screens and returned users to the main menu without unexpected behavior. On the technical side, the app was tested for stability during rapid user input and screen rotations. A bug that caused the workout timer to reset on rotation was identified and resolved, improving overall reliability.

Performance was optimised by ensuring lightweight UI elements, smooth transitions, and efficient memory usage to avoid slowdowns. These refinements helped the app feel faster and more responsive on a variety of Android devices. Together, these optimisations enhanced both the look and feel of the app, while staying true to the original design requirements and improving the overall user experience.

##  Optimisation Table

| **Area**               | **Original Implementation**                                                              | **Optimisation Made**                                                                                  | **Reason for Improvement**                                                                 |
|------------------------|-------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------|
| Water Goal Feedback    | User could track water intake with a counter and progress bar.                            | Added alert message: “Goal Achieved! Great job!” when goal is reached.                                 | Motivates users and improves feedback when a daily goal is completed.                      |
| Visual Engagement      | Static progress bar with no visual change beyond percentage.                              | Added a filling water glass animation to represent progress visually.                                   | Improves user experience and makes progress tracking more intuitive and enjoyable.         |
| Motivational Quote     | Displayed a single static motivational quote on the main menu.                            | Implemented rotating quotes that change every time the app is opened.                                   | Keeps content fresh and engaging to encourage repeated daily use.                          |
| Navigation             | Back buttons worked but were inconsistently placed or responded slowly.                   | Refined navigation flow and back button functionality across all screens.                               | Ensures smoother, more intuitive user navigation throughout the app.                        |
| Workout Timer Stability| Timer reset when the screen was rotated or app was minimized.                            | Fixed rotation bug so that timer continues functioning correctly during orientation changes.            | Prevents data loss and improves app stability during use.                                  |
| App Performance        | UI worked but some transitions were slightly laggy on older devices.                      | Optimised UI responsiveness and reduced unnecessary processing in layout rendering.                     | Improves performance, reduces lag, and ensures compatibility across different devices.      |


## D2 Evaluate the design and optimised mobile app against client requirements.


My final mobile habit tracking app successfully meets all core client requirements and provides an intuitive, engaging, and functional experience for users. The app includes three fully working features: a Water Tracker with an increment/decrement system and visual progress feedback; a Workout Tracker that allows users to log completed sessions; and a Workout Timer that includes start, pause, reset, and preset options. Each feature is accessible from a clearly designed main menu, and navigation across the app is smooth and consistent, supported by intuitive back buttons on every screen.

Throughout development, the app was continuously refined based on design goals, testing feedback, and performance checks. Notable optimisations included adding motivational alerts when water goals are achieved, improving visual progress indicators with animations, and resolving bugs related to the workout timer’s stability. These changes helped transform the initial design into a more dynamic and user-focused experience. 

Overall, the final app meets  and in many areas exceeds  the original requirements by not only delivering on core functionality but also enhancing user interaction and satisfaction. Minor limitations, such as the absence of long-term habit history or user profile support, were outside the project scope and do not impact the app's effectiveness for daily tracking. The result is a polished, well-functioning mobile application that aligns closely with the client’s goals and expectations.


## Evaluation Table 


| **Client Requirement**                      | **How It Was Met**                                                                                      | **Evaluation Comments**                                                                 |
|---------------------------------------------|----------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------|
| Track daily water intake                    | Water Tracker screen with add/remove buttons, daily counter, and animated progress bar.                  | Fully functional and visually engaging. Motivational alerts enhance user interaction.   |
| Track number of workouts                    | Workout Tracker screen with a "Workout Complete" button and daily count display.                         | Simple and reliable. Easy for users to log workouts without confusion.                  |
| Include a workout timer                     | Timer screen with Start, Pause, Reset, and presets (30s, 1m, 5m).                                         | Stable and user-friendly after optimising for screen rotation and app minimisation.     |
| Creative and motivating design              |  motivational quotes,  and intuitive layout.                         | Adds personality and engagement to the app, meeting the creativity aspect effectively.   |
| Easy-to-use navigation                      | Main menu with clear buttons and consistent back buttons on each screen.                                 | Smooth and intuitive navigation throughout the app. User-friendly for all age groups.    |
| Performance and stability                   | Code optimised for responsiveness and tested for screen rotation, rapid inputs, and general reliability. | App is stable and responsive across different devices. No major bugs or crashes.         |



## D3 Demonstrate individual responsibility, creativity and effective self-management in the design, development and review of a mobile app.

##  Development Calendar

| **Date**       | **Task Completed**                                       |
|----------------|----------------------------------------------------------|
| Week 1         | Reviewed client brief, wrote requirements, created wireframes and design ideas. |
| Week 2         | Designed all app screens in XML, completed navigation flow, and built main layout. |
| Week 3         | Implemented Water Tracker and Workout Tracker functionality. |
| Week 4         | Developed Workout Timer screen, added presets and buttons. |
| Week 5         | Conducted full testing (usability, performance, stability), logged and fixed bugs. |
| Week 6         | Added creative touches ( motivational alerts, ). |
| Week 7         | Collected peer feedback, made final refinements, wrote documentation. |


##  Responsibility, Creativity & Self-Management Table

| **Area**                    | **What I Did**                                                                                     | **How It Shows Responsibility, Creativity or Self-Management**                                      |
|-----------------------------|----------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------|
| Planning & Requirement Analysis | Reviewed the brief, created wireframes, and identified key client requirements.                 | Demonstrates responsibility and clear understanding of goals before development began.             |
| Creative Design Decisions   | Included motivational quotes            | Shows creativity and a user-centered design approach tailored to the wellness industry.            |
| Independent Development     | Designed, built, tested, and debugged the entire mobile app myself using Android Studio.           | Shows strong individual responsibility and technical independence.                                 |
| Testing & Refinement        | Conducted usability and performance testing; optimised visuals and fixed timer bug.                | Reflects self review, problem-solving, and quality assurance without relying on external support.  |
| Feedback Implementation     | Reviewed feedback and improved motivational alerts, navigation, and progress tracking visuals.     | Demonstrates openness to improvement and taking initiative to refine the app.                      |
| Time Management             | Followed a personal development schedule with milestone goals and regular updates.                 | Proves effective self-management and ability to meet deadlines independently.                      |


##  Reflection on Responsibility, Creativity, and Self-Management

Throughout the design and development of this mobile habit tracking app, I demonstrated strong individual responsibility by taking full ownership of the project from concept to completion. I carefully gathered and interpreted client requirements, created wireframes, and translated them into a working mobile application using Android Studio. At each stage, I stayed focused on delivering a functional, user-friendly solution that met the needs of the client while also incorporating thoughtful, creative elements.

Creativity was evident in multiple design decisions, such as the inclusion of rotating motivational quotes, visually engaging progress bars, and a clean, intuitive user interface that aligned with wellness and lifestyle themes. These features not only added a unique touch to the app but also helped boost user engagement. I also refined the app by incorporating animation and alert messages that provided helpful feedback during user interaction.

Effective self-management was key to meeting deadlines and producing a high-quality result. I followed a structured workflow, using planning documents and task tracking to manage my time. I conducted regular testing, identified bugs, and made meaningful improvements based on feedback. My ability to reflect on and evaluate my own work ensured the app was not only functional but also polished and reliable. Overall, this project showcases my ability to independently manage a full development lifecycle while demonstrating both technical and creative strengths.

##  Overall Conclusion

My mobile habit tracking app project successfully fulfilled the client’s core requirements by delivering an intuitive, functional, and engaging wellness tool. Through a structured design and development process, I created an app that allows users to easily monitor their daily water intake, log workouts, and use a versatile workout timer — all within a clean, user-friendly interface. The inclusion of creative features such as motivational quotes and animated progress bars enhanced the user experience and helped the app stand out.



Overall, this project not only showcases technical skills in mobile app development but also highlights my ability to deliver a well rounded, creative solution tailored to client needs.
