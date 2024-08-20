**Overview of Online Voting System**
**Objective:**
The objective of this Online Voting System is to provide a simple and user-friendly graphical interface that allows users to cast votes for their preferred candidates securely and efficiently. The system ensures that only eligible voters (aged 18 and above) can participate in the voting process and maintains a tally of votes for each candidate.

**Technologies Used:**
Java Programming Language: The core programming language used to develop the application, known for its portability, robustness, and extensive libraries.
Java Swing Library: A part of Java Foundation Classes (JFC), Swing is used to create the graphical user interface (GUI) components such as frames, buttons, labels, and text fields.

**Application Overview:**
The application follows a straightforward process to facilitate voting:

**User Information Input:**
Name Entry: Users are prompted to enter their names through a text field.
Age Entry: Users input their age, which is used to verify voting eligibility.

**Candidate Selection:**
Users choose their preferred candidate from two options presented as radio buttons:
Jagan Mohan Reddy
Nara Chandrababu Nayudu

**Voting Process:**
Upon clicking the "Vote" button, the application performs the following actions:
Age Verification: Checks if the user is 18 years or older to ensure eligibility.
Vote Recording: Increments the vote count for the selected candidate if the user is eligible.
Feedback Provision: Displays an appropriate message thanking the user for voting or notifying them of ineligibility.
Vote Count Display: Prints the current vote totals for both candidates to the console for tracking purposes.

**User Interface Layout:**
The GUI is arranged using absolute positioning with specified bounds for each component to ensure proper layout and spacing.
The main frame is titled "Online Voting System" and is set to a fixed size, with components such as labels, text fields, radio buttons, and buttons appropriately added.

**Key Features:**
Eligibility Check: Ensures that only users who meet the minimum age requirement can cast a vote.
Simple GUI: Provides an intuitive and easy-to-use interface for users with clear instructions and prompts.
Real-time Vote Tracking: Updates and displays vote counts immediately after each vote is cast.
Error Handling: Includes basic validation to handle incorrect inputs, such as non-numeric age entries.

**Potential Enhancements:**
While the current system serves as a basic prototype, future improvements could include:
Data Persistence: Storing vote counts in a database to maintain records beyond the application's runtime.
Enhanced Security: Implementing user authentication mechanisms to prevent multiple votes from the same user.
Dynamic Candidate Management: Allowing for a flexible number of candidates and dynamic addition or removal of candidate options.
Responsive Design: Adapting the GUI layout to be responsive to different screen sizes and resolutions.

**Conclusion:**
This Online Voting System demonstrates a fundamental implementation of a voting application using Java and Swing. It serves as a foundational model that can be expanded and enhanced to meet more complex and real-world voting requirements.
