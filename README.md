# CS360

Mobile Architect & Programming 22EW1

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

The requirements and goals of the Inventory App were two-fold, to have a login system that saved and allowed creating of user credentials and a functional database to store user inventories that consisted of objects and quantities. In addition to these two main features there also exist an alert feature to notify the user via SMS if any of the items in their inventory get low. The app was designed to address users that want a lightweight, easy to use, secure application for keeping themselves organized.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The app consists of three main screens. The login, the inventory, and the permission request. Admittedly on first-concept my designs were not that successful, as they would have employed a much more complicated setup than necessary to accomplish the goals of the app. Specifically I am referring to the inventory screen, where the initial design consisted of a grid where the user would have multiple entry points for adding data to their inventory that would adjust as input was added or removed. In practice however it is far more straightforwards to have a single input section that updates the inventory, rather than have the inventory not only display data but be interactive with the input as well, esspecially in the form of the SQLiteDB. 

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

My first order of business when coding is to keep in mind the goals of the app. No matter how well coded an app may be if it doesn't accomplish the goals it was set out to accomplish then it isn't a very good app. To this end I began by breaking down each goal into actionable tasks. Begin by creating the base UI screen and components, from there I would consider what was needed such as onClick() methods for the various interactable buttons in the app. Once the core of the app existed it was time to implement functionality, by creating a database and connecting it to the necessary components to make the app function. I would say that this strategy is common among computer scientists and will be applied in the future often on any task that is large enough to be broken down.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

Testing. In the case of Android Studio I found running the emulator over and over and clicking everything to make sure that it all worked as intended was the best course of action. This process is so important because it proves the concepts in action. Just because code may look functional you never know how various components may react, what issues might be revealed such as missing strings or improper id usage, and you need to test them in action to find out if changes need to be made. 

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

For the course of the project, and in general I find trial and error to be the best method. When an initial design or implementation failed I would tinker with it, but if it ultimately wasn't going to succeed I would come up with another idea and test it out to see if it worked. There can be a lot to learn from "failed" implementations by identifying the parts that worked, and the parts that didn't work and integrating them into your next iteration. Every attempt is one step towards overcoming said challenge. In the case of the project, my issues that arose with the SQLite DB on the login for instance were adapted by using a HashMap to create a base functionality.

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think the overall form of the app is the most successful component. The object oriented nature of the code, the UI and features are straightforward and easy to intuit. By having each activity clearly seperated and titled to its purpose, as well as the java classes being easily identifiable to what activity they concern themselves with it is a well documented work. 
