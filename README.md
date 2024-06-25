# CS-360 Mobile Architecture and Programming Portfolio Submission
<br/>

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
---
This event-tracking app aims to create a secure database of user-created events accessible only through a secure user login. Events will be displayed in a grid layout, and the app will send SMS alerts on days with upcoming events. The app addresses specific user needs related to schedule management, event reminders, and data security.
<br/>
<br/>
<br/>

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
---
The app features several necessary screens: login, user registration, event list view, and dedicated screens for adding, viewing, editing, and deleting events. A settings screen allows users to manage SMS notification permissions. All screens utilize large buttons and clear text entry areas. Event-specific screens, in particular, display all relevant event information for user input. This design prioritizes clear information visibility and easy button interaction. While I believe this approach is effective, further user testing is recommended for confirmation.
<br/>
<br/>
<br/>

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
---
Leveraging an incremental development approach, I prioritized database development first. This enabled the creation of login and registration functionalities for initial testing. Subsequently, I developed the Event class, facilitating the development and testing of individual event methods. This approach resembles assembling building blocks, where each functional component is meticulously designed and tested before integration.
<br/>
<br/>
<br/>

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
---
I opted for manual testing throughout the development process rather than automated testing. This involved launching the emulator within Android Studio and meticulously testing every screen, transition, and user action. Any failure to launch or crash during testing signified a functional issue. Once the app launched successfully, I pushed the boundaries of user input by introducing various scenarios: extra characters, blank fields, and unusual characters.
<br/>
<br/>
Testing is undeniably a critical aspect of development. Code that appears sound on paper can malfunction in practice. Even a poorly written app might launch but be riddled with bugs. Through testing, I discovered areas where input validation needed improvement and identified suboptimal performance in the SMS functionality, necessitating further refinement.
<br/>
<br/>
<br/>

Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
---
Implementing a slider for app permissions presented a unique challenge, as this feature is uncommon in Android development. To overcome this, I consulted the Android Developer website extensively. The slider's functionality works as follows: if the user turns it on and their phone settings lack SMS permission, the app will request the permission. Alternatively, instead of revoking SMS permissions, the SMS sending method checks the slider's state (on or off) before proceeding.
<br/>
<br/>
<br/>

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
---
I believe my greatest success involved implementing a light and dark mode toggle. Although a common feature, it wasn't explicitly covered in the course. This challenged me to leverage the knowledge gained on shared preferences and themes, while independently researching to fill any gaps. Even for a seemingly simple feature, I'm very proud of the outcome.
<br/>
<br/>
<br/>
