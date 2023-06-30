Voting System Readme
This is a readme file for a voting system implemented using PHP, HTML, CSS, SQL, MongoDB, and Python. The system allows users to create questions, provide answers, and vote on answers. The data is stored in both SQL and MongoDB databases, providing flexibility and scalability. Additionally, a display module implemented in Python is included for visualizing the voting results.

Features
User Registration and Authentication:

Users can register and create an account to participate in the voting system.
User authentication is implemented to ensure secure access to the system.
Question Creation:

Registered users can create questions by providing a title and description.
Questions may include multiple-choice options or allow users to write their own answers.
Answer Submission:

Users can submit answers to the questions created by other users.
Answers can be selected from predefined options or provided as a custom response.
Voting Mechanism:

Users can vote for their preferred answers to contribute to the voting process.
Each user has a single vote per question to ensure fairness.
Data Storage:

The system stores data in both SQL and MongoDB databases to provide flexibility and support large-scale data management.
SQL databases are used to store user information, questions, answers, and voting details.
MongoDB is utilized to store additional data or provide advanced querying capabilities.
Key-based Access:

Users can access the system using a unique key associated with their account.
This key ensures secure access and prevents unauthorized users from participating in the voting process.
Display Module (Python):

The system includes a display module implemented in Python for visualizing voting results.
Python libraries, such as matplotlib or seaborn, can be used to generate graphs or charts based on the voting data stored in the databases.
System Requirements
To run the voting system, ensure that you have the following components installed:

PHP 7.0 or above
HTML
CSS
SQL database (e.g., MySQL)
MongoDB
Python 3.x with required dependencies (matplotlib, seaborn, etc.)
