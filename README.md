# Birthday Wisher

This Python script automates sending personalized birthday wishes via email to individuals listed in a CSV file, celebrating their birthdays with customized messages.

## Features

- **Automated Wishing:** Utilizes Python to automate the process of sending birthday wishes.
- **CSV Integration:** Reads birthday data from a CSV file to personalize wishes.
- **Email Customization:** Sends unique messages to each recipient based on their birthday.
- **SMTP Integration:** Uses SMTP protocol to send emails via an email service provider.

## Requirements

- Python 3.x
- CSV file containing birthday data
- Email account credentials (for sending emails via SMTP)

## Setup

1. Clone this repository.
2. Install necessary Python libraries: `pip install -r requirements.txt`.
3. Add recipient information in `birthdays.csv`.
4. Update email configurations in `config.py` with your email provider settings.
5. Run the script: `python birthday_wisher.py`.

## Usage

- `main.py`: Main script for sending birthday wishes.
- `birthdays.csv`: CSV file containing recipient details (name, email, birthday).

## Notes

- Ensure proper internet connectivity for sending emails.
- Review and modify email templates/messages in the script based on preferences.
- Handle authentication securely; avoid sharing sensitive information.
