Expense Analyser App – Overview

The Expense Analyser App is a mobile application developed using MIT App Inventor that helps users efficiently record, categorize, and analyze their daily expenses. Users can add daily spending details, track expenses category-wise, and calculate total monthly expenses. The app provides a simple, secure, and user-friendly way to manage personal finances and understand spending patterns.

Features

Add daily expenses with category, amount, and description

Secure user registration and login

Record and categorize expenses

Monthly expense calculation

Category-wise expense analysis

Location-based expense tracking using maps

Share expense reports with others

Chatbot support for expense-related queries

Problem Statement

Managing daily expenses manually is time-consuming and often leads to inaccurate financial tracking. Many individuals struggle to properly categorize expenses, calculate monthly totals, and analyze spending behavior. Traditional methods such as handwritten notes or spreadsheets lack automation, security, and ease of use.

The Expense Analyser App solves this problem by offering a structured, secure, and mobile-based solution that automates expense recording, monthly calculations, and spending analysis, helping users manage their finances more effectively.

Components Used
1. TinyDB

Stores user login and signup details

Saves expense records locally for each user

2. User Interface Components

Labels – Display headings and information

TextBoxes – Input username, password, amount, and descriptions

Buttons – Login, signup, save expenses, calculate totals, and share reports

ListPicker – Select expense categories and daily spending items

3. Sharing Component

Enables users to share expense summaries and reports via messaging apps

4. Web Component

Integrates with Google Sheets

Stores and syncs expense data online

5. Map Component

Displays expense locations using latitude and longitude

Helps users track where expenses are incurred

Chatbot Component 

The app includes a Chatbot component that allows users to interact with the system in a conversational way.

Chatbot Features:

Users can ask questions like:

“How much did I spend this month?”

“Which category has the highest expense?”

“Show my food expenses”

Provides automated answers based on stored expense data

Allows users to share questions and answers with others

Improves user engagement and makes expense analysis easier

Working Flow of the Expense Analyser App
1. User Registration

New users register using the Signup option

User credentials are stored securely in TinyDB

2. User Login

Registered users log in using their username and password

Authentication is verified using TinyDB

Successful login redirects the user to the main dashboard

3 Location Tracking

Entered latitude and longitude are displayed on the Map

Helps visualize where expenses occur

4. Monthly Expense Calculation

Expenses are filtered based on selected month

Category-wise and total monthly expenses are calculated

Results are displayed for analysis

5. Chatbot Interaction

User asks questions related to expenses

Chatbot processes stored data and returns answers

Users can share chatbot responses with others
