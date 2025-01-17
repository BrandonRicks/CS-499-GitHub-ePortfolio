# Table of Contents

[1. Self-Reflection](#self-reflection)<br/>
[2. Code Review](#code-review)<br/>
[3. Enhancements](#enhancements)<br/>
&emsp;[3.1. Software Design & Engineering](#software-design--engineering)<br/>
&emsp;[3.2. Algorithm & Data Structures](#algorithm--data-structures)<br/>
&emsp;[3.3. Databases](#databases)<br/>
[4. Contact](#contact)<br/>
[5. References](#references)<br/>

## Self-Relection

&emsp;&emsp;Prior to starting this Computer Science program, I had very little experience in programming and the intricacies of software engineering and development. I had a lot of interest in technology and computers, and experience with hardware, software, some networking, and what I consider to be basic understanding of computers. But I was always interested in more, and asking questions like how do computers think? How do they decide? How does a program run? How does so much happen with just binary? These curiosities and interests in learning more are what led me to this program. My desire has always been to work in the technology field and be involved in its future. This degree and my experiences in this program are the first step in that direction. This self-reflection will take a look back at some of the experiences I have had over the course of the program. <br/>
&emsp;&emsp;When working in CS-310: Collaboration & Team Project, the goal was for us to gain experience working together in a shared repository. The project was simple: have the entire class finish the semester with a large jukebox of songs and artists of our choosing. We accomplished this collaboration through GitHub, making pull requests on recent branches, making our changes to the code, and then pushing the branch to be reviewed by our peers. Once reviews were complete and the branch looked good, we would have our changes merged into the main branch for the next person to pull from. This class also touched on the importance of version control, which was a big factor in collaborating with so many people and having so many open branches at one time. <br/>
&emsp;&emsp;Security was another important focus in the program. As technology grows and interconnectivity becomes more prevalent between devices and networks, security will continue to grow in tandem, and be a major focus in development. One class in particular that focused on the importance of security was CS-405: Secure Coding. This class covered many of the common issues that may exist when developing, such as numeric overflow, SQL injections, buffer overflows, as example. The course also touched on the importance of regular testing and working with unit testing, as well as many other concepts like Triple A and Defense in Depth, and how to apply these concepts to future projects. I finished out this course by creating a PowerPoint presentation covering all of the different subjects of the course and incorporated all of this into an updated security policy. <br/>
&emsp;&emsp;My experience in CS-260: Data Structures and Algorithms was on exploring the various forms of data structures, as well as their interactions with data and databases. The course went over various forms of data structures, such as vectors, hash tables, and tree structures, and also the organization, management, and storage of data, primarily focusing on efficiency and ease of access. The experience from this class was useful and applicable in future classes, particularly when there was interaction between a program and database. One of these data structures, a binary search tree, has been showcased in the Algorithms and Data Structure portion of this portfolio. <br/>
&emsp;&emsp;Software Design and Engineering was a key focus in many classes of the program. CS-360: Mobile Architecture and Programming focused on applying different design concepts to mobile app development. Mobile apps, by design, focus a lot on UI and user interaction. For this class, I designed a functioning event tracking app, which included a user creation and login feature, forgot password option, and a database for storing both user inputted data for events, and user information for login. This was accomplished using a combination of Java and SQLite. Having concentrated in Software Engineering, I gained further experiences in the engineering aspects of development as well. CS-350: Emerging Systems Architectures & Technologies had me developing using C and embedded systems. For this class, I had to make use of a TI development board, and by using combination of drivers to allow functionality on the board and my written code, turn the board into a functioning thermostat. This project is showcased in the Software Design & Engineering portion of this portfolio. <br/>
&emsp;&emsp;Throughout the program, there were many courses which involved working with large quantities of data, whether by searching with algorithms, or applying CRUD functionality to the data with the use of databases and some form of module for applying this functionality. One example of my experience with databases is CS340: Client/Server Development. For the course, I was assigned to create functionality for a client-side dashboard for a faux company, as well as create a database for storing all of the company’s information, and the means with which to interact and manipulate this information indirectly from the dashboard. In order to accomplish this, there needed to be development in front end, back end, and middleware. The dashboard showcased maps, graphs, and a UI for the user to interact with information, the database housed all of this information, and the middleware was a module I wrote in Python that gave the user CRUD functionality, and also created authorization credentials for different types of access to the database (READ, READ/WRITE, etc.). This required me to use many tools and programs simultaneously: MongoDB for the database, Python coding for the middleware, Jupyter Notebook as a stand in for the dashboard, and Plotly and Dash for the UI elements like maps and graphs. The experience gave me a lot of insight into how each of these parts function together to create a chain for client/server interaction. This project is showcased in the Database portion of this portfolio. <br/>
&emsp;&emsp;In closing, I have thoroughly enjoyed the 4 years I have spent in this program. Each course, from math courses, science courses, and the plethora of IT and CS courses; all have taught me so many new topics and subjects that I had once never even heard of or experienced before. Computer Science is a complicated subject, and it has a knack of never letting you truly feel comfortable as you constantly learn new things or expand on prior information, but the challenge and experience is very rewarding. This has left me with a solid foundation of experiences in many different subjects and I look forward to continuing to expand my knowledge and experience in the field. <br/>


## Code Review

<span style="color:gray">*What is code review?*</span>

&emsp;&emsp;Code review seeks to find issues and security flaws regarding design and features, and the root causes to these issues (Conklin & Robinson, 2017). A common form of this is peer code review, which aims to convene with fellow programmers on checking each other’s code (Best Practices for Code Review, 2021).

<span style="color:gray">*Why is it an important practice for computer science professionals?*</span>

&emsp;&emsp;The act of auditing code periodically helps to verify that the logic and security of code is present and working as intended (Conklin & Robinson, 2017). This practice can also help to detect issues before they grow into a larger problem, as well as ensure consistency in standards, and more robust software (The Importance of Code Reviews, 2021).

<span style="color:gray">*When and how does it occur?*</span>

&emsp;&emsp;How often and to what extent can vary, but in Agile Methodology, this can happen more frequently (The Importance of Code Reviews, 2021), and in more lightweight methods, such as with a tool-assisted process (Best Practices for Code Review, 2021). This can also be done manually with a team, or through an automated tool for code review, purely to find bugs, errors, and improve code quality (Dean, 2019).

<span style="color:gray">*What are some code review best practices that you would advocate?*</span>

&emsp;&emsp;I believe keeping intent positive and doing more lightweight checks of a small number of lines periodically through a SDLC would help to keep the process light, and avoid needless stress, or the “Ego Effect” (Best Practices for Code Review, 2021). Using checklists and keeping realistic and clear goals will also help to make it a normal part of routine and keep the whole process clear and easily understood (Best Practices for Code Review, 2021).

<span style="color:gray">*Are there any practices that may be currently uncommon that you believe would make code reviews more effective?*</span>

&emsp;&emsp;While I wouldn’t say its uncommon, I think integrating checks during the development process helps to find issues quicker and easier, keeping them minimal and overall lessening time and effort required to fix them. Constructive feedback would also be beneficial in this process, not requiring formal meetings (The Importance of Code Reviews, 2021).

## Enhancements
### [Software Design & Engineering]
[Thermostat Project](https://github.com/BrandonRicks/brandonricks.github.io/tree/main/ThermostatProjectUpdated)

<span style="color:gray">*Briefly describe the artifact. What is it? When was it created?*</span>

&emsp;&emsp;For software design and engineering, I selected my thermostat code that I used for CS350: Emerging Systems Architectures & Technologies. This project was created in October of 2021, and its purpose was to create a functional thermostat from the development board I used, which was a CC3220x-LaunchXL Development kit by Texas Instruments (CC3220S-LAUNCHXL Development Kit, 2022).

<span style="color:gray">*Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?*</span>

&emsp;&emsp;I selected this item because I feel that it showcases my ability with embedded systems. By making use of the drivers on the board, I was able to create logic that would make use of buttons, lights, and console outputs, in order to simulate the functionality of a thermostat. Embedded systems need to be clean and efficient, so I attempted to approach enhancing the program with this in mind.
<br/>&emsp;&emsp;For improvements, I chose to look at the flow of the code and make sure that everything made logical sense. I did this by following some guidelines laid out by Barr Group, which is a group that focuses on the structure and functionality of embedded systems (Barr Group, 2016). I also looked to improve the functionality by inserting a cycle timer of 30 seconds that would eliminate the possibility of cycling. This would act as a buffer to prevent the heat from turning on and off quickly if the values for temperature were fluctuating. I also moved the temperature reading to not run every loop, which would be inefficient. Instead, I had the temperature be read every 500ms, as required, when the temperature would need to be checked to see if the heat would need to be on or off. Combined with the timer, this would allow the code to output properly, but still require an elapsed time before running another check for heat.

<span style="color:gray">*Did you meet the course objectives you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?*</span>

&emsp;&emsp;For module one, I had selected a few things that could be improved within the code, primarily changing a few names for variables, and creating a way to buffer cycling of the heat. The variable for thermostat was originally setpoint, which I felt was not informative enough, so I changed this to setThermostat, which better explains its purpose. I also incorporated a buffer for the heater to ensure there wasn’t any cycling. I achieved this by creating a boolean cycleTimer, which was initialized to false. Once heat was turned on or off, it would change this to true, and would only change back to false after the new variable cycleCheckTime was greater to the other new variable cycleCheckPeriod. This would be incremented by the already existing timerPeriod of 100ms, up to a value of 30000, or 30 seconds. This ensured that the code for turning heat on or off would not run for 30 seconds, but temperature would still be updated every 500ms, as intended.

<span style="color:gray">*Reflect on the process of enhancing and/or modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?*</span>
	
&emsp;&emsp;The biggest challenge I faced was setting up Code Composer Studio, the SDK for my board, and all of the functionality required to test the changes. I had removed much of it to save space. This IDE and process has always been a bit difficult and would be finicky with building the project properly. Once I was able to get it all running and properly test my changes, I ran into little issue.
<br/>&emsp;&emsp;In making these adjustments, I learned a lot about the importance of efficient, simple code. Sometimes, the simplest and most straightforward method is the best. When I originally wrote the code, that was my intent, as the code was designed with embedded systems in mind. When improving the code, I focused on the logic, particularly with the loops and considering what would be the most logical or obvious way that it should flow. For example, changing the location of a single portion of the code that reads the temperature off the sensor, and running it somewhere more logical, would lessen the number of times it would run by 5 times.

### [Algorithm & Data Structures]
[Lab 6-2: Binary Search Tree](https://github.com/BrandonRicks/brandonricks.github.io/tree/main/Lab6-2)

<span style="color:gray">*Briefly describe the artifact. What is it? When was it created?*</span>

&emsp;&emsp;For algorithms and data structures, I selected Lab 6-2 from my CS260: Data Structures and Algorithms class. This lab was created June of 2020 and is on binary search trees and the interaction between algorithms and data structures. The artifact I primarily worked on was the file I created, “BinarySearchTree.cpp”, which interacts with the CSV parser.
  
<span style="color:gray">*Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?*</span>

&emsp;&emsp;I selected this item to showcase algorithms and data structures because I feel that it showcases my ability to code and apply the interaction between algorithms and data structures. In this assignment, we were given an Excel sheet with a lot of information and a CSV parser, and the goal was to extract this information by loading the CSV file, and coding in functionality that would allow one to manipulate the information. This artifact was improved by checking over all logic and improving the code structure. There were excess comments and, overall, the code length could be trimmed down to a more reasonable length.

<span style="color:gray">*Did you meet the course objectives you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?*</span>

&emsp;&emsp;In module one, I had stated that I would like to improve readability, as well as commenting and structure, and I feel that I had accomplished this objective. Most methods were needlessly large, and comments were doubled up, explaining portions of code multiple times. There were also portions of code that were commented out without any explanation as to why. I removed any redundant commenting, trimmed down the amount of whitespace, and made sure comments were consistent and gave good explanations. I also made sure that curly braces were consistent in their formatting, as they were in multiple different formats for no particular reason, likely an oversight.

<span style="color:gray">*Reflect on the process of enhancing and/or modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?*</span>

&emsp;&emsp;With this artifact, I focused on readability, as well as keeping code clean and comments informative. Ensuring that code stays consistent in its structure helps to make the code easy to follow and not create undue confusion if style and format changes randomly throughout the code. Something as simple as curly braces being in line and then on their own can add some mental overhead on following code. I also made sure what comments I had kept were useful in explaining what code accomplished, and I made sure to remove any redundancy.
<br/>&emsp;&emsp;I didn’t meet with too many challenges, as the code functioned well originally, and the CRUD functionality was logically sound. However, as this code was written a few years ago, it is interesting to see how one evolves and develops over time, and so going back to older projects has given me some insight into my progress over the years. I learned a lot about my progress and was able to apply knowledge I had learned later into this code, particularly with commenting and structure. I had since considered the importance of coding for other people; the idea that your code could be picked up by someone else and it wouldn’t immediately break or be hard to follow. The code had a lot of redundant commenting and a lot of excess whitespaces, as well as a few instances where curly braces were formatted in two different ways. While it was still working just fine in terms of its ability to run and the logic, it could definitely be slimmed down and cleaned up. Overall, I removed about 10% of the lines from the original that I felt weren’t needed and cleaned up what was there to something that I felt flowed nicely. 

### [Databases]
[Project Two Final](https://github.com/BrandonRicks/brandonricks.github.io/tree/main/CS-340-Client-Server-Development)

<span style="color:gray">*Briefly describe the artifact. What is it? When was it created?*</span>

&emsp;&emsp;For databases, I selected the Project Two final from my CS340: Client/Server Development class. This project was completed August of 2021, and is primarily on the interactions between client, server, and middleware. The database was done through MongoDB, the client-side dashboard was done through Jupyter Notebook, and the middleware was written in Python. Maps, graphs, and UI were created with Plotly and Dash.

<span style="color:gray">*Justify the inclusion of the artifact in your ePortfolio. Why did you select this item? What specific components of the artifact showcase your skills and abilities in software development? How was the artifact improved?*</span>

&emsp;&emsp;I selected this item to showcase my experience with full stack development, and the interactions between client and server using a python module I had written. The python module functions as middleware to allow the user to interact with the database indirectly through the dashboard. This gives the user CRUD capabilities without requiring them to access the database directly, which allows for a simpler and more secure interaction.

<span style="color:gray">*Did you meet the course objectives you planned to meet with this enhancement in Module One? Do you have any updates to your outcome-coverage plans?*</span>

&emsp;&emsp;In module one, I had stated that I would like to improve the structure of the code and ensure the interaction between client and server was consistent. The python module is relatively straightforward: it establishes the connection to the database and holds all of the constructors and methods required to allow CRUD functionality for the user. The user’s privileges are based on their username and password credentials, which are stored server side and determine the user’s level of accessibility. Once connection is established, the user can then interact with the data in the database, based on their privileges.

<span style="color:gray">*Reflect on the process of enhancing and/or modifying the artifact. What did you learn as you were creating it and improving it? What challenges did you face?*</span>

&emsp;&emsp;When creating and improving this artifact, I learned a great deal about how information is accessed in a database indirectly. Allowing a user to interact through a client-side and having middleware control connection and manipulation helps to ensure this interaction is secure and simplified for the user. This interaction can respond dynamically and in real-time, using a simple UI in the dashboard, rather than needing the user to run database commands and directly manipulate data within the database. 
<br/>&emsp;&emsp;The main challenge I faced was in relation to connectivity. As the original project was done through a virtual environment, there were sometimes instances where connection was inconsistent when connecting to the MongoDB. This would sometimes require one to unalias the database and reconnect with the specific port. Connection would also sometimes be an issue if the dashboard and/or the database process did not close successfully. These seemed to mostly be quirks of working within a virtual environment.

## Contact
Name: Brandon Ricks<br/>
Email: [brandon.ricks@snhu.edu](mailto:brandon.ricks@snhu.edu)

## References
[*Best Practices for Code Review.* (2021). Smartbear.com.](https://smartbear.com/learn/code-review/best-practices-for-peer-code-review/)<br/>

[Conklin, L., & Robinson, G. (2017). *CODE REVIEW GUIDE RELEASE Creative Commons (CC) Attribution.*](https://owasp.org/www-project-code-review-guide/assets/OWASP_Code_Review_Guide_v2.pdf)<br/>

[Dean. (2019, July 24). *Best Practices and Techniques For Reviewing Code.* Codegrip.](https://www.codegrip.tech/productivity/best-practices-for-reviewing-code/)<br/>

[*The Importance of Code Reviews.* (2021, February 2). 3Pillar Global.](https://www.3pillarglobal.com/insights/the-importance-of-code-reviews)
