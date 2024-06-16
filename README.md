# html-form-data-connect-with-WhatsApp
A Pen created on CodePen.io. Original URL: https://codepen.io/Ashwini-Sonawane/pen/YzbYxjJ.

![Screenshot (337)](https://github.com/SonawaneAshwini/html-form-data-connect-with-WhatsApp/assets/172588428/9b592d86-63f2-4636-b7eb-f7d6a6f9ee59)



# Introduction
WhatsApp Web is a web-based extension of the popular WhatsApp messaging application. It allows users to access their WhatsApp conversations and send/receive messages directly from their web browsers. Integrating HTML forms with WhatsApp Web can enhance user experience and streamline communication.

# System Architecture
![whatsapp system](https://github.com/SonawaneAshwini/html-form-data-connect-with-WhatsApp/assets/172588428/ff967269-bd8b-4c5f-8f79-e0d495bf80f7)

 
The system comprises three main components:
1.	HTML Form: A simple form collecting user data.
2.	JavaScript: Handles form submission and sends data to WhatsApp.
3.	CSS: Styles the form for a user-friendly interface.
   
# Features
 	User Interface
•	Responsive Design: The form is styled to be visually appealing and user-friendly.
•	Form Fields: Includes fields for Name, Email, and Message.
•	Submission Button: A button to submit the form data.
 	Functionality
•	Data Collection: Collects user input from the form fields.
•	WhatsApp Integration: Uses the WhatsApp API to send data as a message.
•	Dynamic Message Creation: Constructs a message string with the form data.

# Implementation Diagrams
![whatsapp Data Flow](https://github.com/SonawaneAshwini/html-form-data-connect-with-WhatsApp/assets/172588428/90c88e1a-b2d8-4a8c-a5b3-41a00ea7bb6f)


 
# Integration with WhatsApp
How it Works
1.	User Input: The user fills out the form with their name, email, and message.
2.	Form Submission: Upon clicking the submit button, the send To WhatsApp function is invoked.
3.	Message Construction: The function constructs a URL with the form data.
4.	WhatsApp API: The URL is opened in a new tab, redirecting to WhatsApp Web with a pre-filled message.
   
# Advantages
•	Direct Communication: Allows for immediate interaction with users via WhatsApp.
•	Ease of Use: Users can send messages without needing to manually enter details.

# Conclusion
Integrating HTML form data with WhatsApp Web streamlines communication and enhances user engagement. The implementation is straightforward, involving basic HTML, CSS, and JavaScript. This integration provides a seamless way to connect with users and receive their inquiries or feedback directly through WhatsApp.

# References
1.	MDN Web Docs: HTML, CSS, JavaScript
2.	How can I send HTML enquiry form data to multiple WhatsApp contacts

