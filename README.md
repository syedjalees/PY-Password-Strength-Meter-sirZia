Password Strength Meter
Overview
This app evaluates the strength of your password by checking its length, the presence of uppercase, lowercase, numbers, and special characters. It provides feedback on how to improve password security.

Features
Length Check: Password must be at least 8 characters.

Character Check: Requires both uppercase & lowercase letters.

Number Check: Includes at least one digit.

Special Character: Must contain one of !@#$%^&*.

Feedback: Provides suggestions for improvement.

Prerequisites
Python 3.6 or higher

Streamlit (Install via pip install streamlit)

How to Run
Save the script as password_strength_meter.py.

Run in terminal:

streamlit run password_strength_meter.py
Open the app in your browser and check password strength.

Code Breakdown
Custom Styling: The title and buttons are styled using CSS for better UI.

Password Evaluation: Checks for length, uppercase, lowercase, numbers, and special characters.

Feedback: Displays real-time feedback on password strength and improvements.