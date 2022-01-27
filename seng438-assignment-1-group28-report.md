>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       |    28    |
|-----------------|---|
| Student Names:  |   |
| Harshit Sharma  | 11311001 |
| Heidi Toews     | 30094995 |
|                 |   |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

# Introduction

The goal of this lab assignment was to learn to use a bug tracking platform and familiarize ourselves with exploratory testing, manual scripted testing, and regression testing. Before this lab, we understood the basics of these types of testing, and this lab has provided us an opportunity to gain more in depth knowledge and practical experience using them. We used the bug tracking platform Backlog, and all logged in to the same account to add bugs. We then split into pairs to perform exploratory testing and manual scripted testing of the system. The plan for exploratory testing is outlined in section 2. The manual scripted testing was performed using the test cases provided in Appendix C of the lab document. The exploratory and manual scripted testing were both performed on version 1.0 of the system. We then performed regression testing on version 1.1 of the system, where we first checked to see if the defects from version 1.0 still existed, and then performed manual scripted testing again, using the same test cases from Appendix C that we used for version 1.0. 

# High-level description of the exploratory testing plan

Text…

# Comparison of exploratory and manual functional testing


Exploratory is a style of software testing that focuses on the users' experience rather than making the system undergo a structured test and a specified process. 

Scripted testing on the other hand follows a well-documented set of test cases and test steps. To ensure that the program is tested correctly, there is no deviation from the script.

When comparing the two, the exploratory testing requires an in-depth knowledge of the system at hand as the tester must understand the requirements of the system while in the scripted test, the tester can overcome the lack of domain knowledge through the use of the well-document test cases and test steps. Documentation in the exploratory testing is sorely lacking as there is only a rough plan in phase while scripted tested has written test that the tester must follow. Exploratory requires little to no time before testing occurs while scripted testing is time-intensive as the tester must perform a rigid set of instructions. Exploratory testing requires no preparation only a rough plan while scripted testing requires significant investment in preparing test scripts and documentation. Exploratory testing is difficult to reproduce due to its unrestricted nature while in scripted testing the bugs are easily reproduced. Exploratory testing focuses on the design of the system while scripted testing focuses on the requirements of the system. 

For comprehensive testing, it is imperative to test the system under both conditions to ensure the system is of the highest quality. 

# Notes and discussion of the peer reviews of defect reports

There was some variation in the bugs found in the different types of testing. Bugs that were found in both types of testing were issues the withdrawal and deposit amounts, and problem with typing an incorrect pin. Many of the other bugs we discovered were only noticed during one type of testing – for example, exploratory testing did not discover that $0.50 is removed from each account when performing a transfer, while manual scripted testing did not discover that the off button is unresponsive during transactions. 
A detailed list of the bugs discovered can be found in the Excel file in the GitHub repository. 

# How the pair testing was managed and team work/effort was divided 

Text…

# Difficulties encountered, challenges overcome, and lessons learned

Through our teamwork we have learned that it is imperative for software testing to be done extensively and for it to be done by multiples groups. As  during the exploratory testing phase, we had realized that the 2 pairs in our group had undertaken completely different strategies while one chose to test out the features collectively the other pair had decided to utilize the app as a consumer would. 

The difficulties on this lab were trying to reproduce the bugs that we had found within the exploratory testing phase as during the test, we were trying to follow the path of a consumer rather than following a rigid path.

During this phase, we had learned that it is important for every step to be documented during each phase as some bugs are harder to reproduce that others and thus documentation will be useful in trying to reproduce the bugs at a later time or in a later version. 

We also had a challenge of trying to schedule a team meeting and testing session as during the week, each of the group member was constantly trying to juggle academics, extracurricular activities and their personal lives. We overcame this hurdle through the use of Google Calendar as we had combined all of our calendars and found time blocks which were available for everyone.


# Comments/feedback on the lab and lab document itself

This lab was a great learning experience for the team as a whole as it allowed us to explore the world of software testing. Backlog was an integral part of the lab but it would have been a smoother experience if there had been a tutorial which outlined the onboarding process for Backlog as for our group it had been a great challenge as the website did not have a clear outline for user onboarding. The lab document had been pivotal to this lab and it had extensive coverage for the pre-requisite  knowledge required for the successful completion of this lab. The lab itself was a very good learning experience and all the notes provided were very helpful and the notes allowed us to stay on track and as they provided a step by step process to completing this lab but a more coverage on the tools section would have made it a more smoothness experience. All in all, the lab was a great first step to introduce the students to software testing requirements.