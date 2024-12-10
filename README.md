# Automated-Mail

This project is an AI-powered email automation tool designed to simplify and streamline email composition and delivery. It uses the GPT-Neo model for generating professional email content and provides an interactive interface powered by Gradio.

Features
AI-Generated Email Content
Automatically generates email content based on user-provided prompts, ensuring professionalism and personalization.

Secure Email Delivery
Sends emails via SMTP using Gmail with credentials managed securely through environment variables.

User-Friendly Interface
A simple and interactive Gradio-based UI for composing, reviewing, and sending emails.

Tech Stack
Backend: Python, Hugging Face Transformers (GPT-Neo)
Frontend: Gradio
Email Delivery: SMTP
Installation
Prerequisites
Python 3.8+
Gmail account for SMTP (with "App Passwords" enabled or "Less Secure App Access" enabled in account settings)
Steps
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/automated-email-system.git
cd automated-email-system
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Set up environment variables:

Create a .env file in the project directory.
Add the following lines to the file:
env
Copy code
EMAIL_USER=your_email@gmail.com
EMAIL_PASS=your_email_password
Run the application:

bash
Copy code
python your_script_name.py
Usage
Open the Gradio interface in your browser.
Enter the subject prompt for your email and the recipient's email address.
Preview the AI-generated email content.
Click "Send" to deliver the email.
Example

Limitations
Requires a stable internet connection for AI model execution and email delivery.
Gmail account setup may require additional security settings.
Contribution
Contributions are welcome! Feel free to fork the repository, make changes, and submit a pull request.

License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgments
Hugging Face: For the GPT-Neo model.
Gradio: For the intuitive UI framework.
SMTP: For email automation support.
