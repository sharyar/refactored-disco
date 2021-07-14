# refactored-disco
Simple medicine dose tracker


## Requirements:

* Signup page and API: User can sign up for an account.
* Login page and API: After signup, the user can log in to their account.
* Account page: On this page, the user can add and view medicines.
* Input for the new data can be taken via an HTML form which has three fields:
* Medicine Name - String
* Dosage - Quantity (Integer) with units (String) or a freeform text field (String)
* Frequency - Quantity (Integer) with units (String) or freeform text field (String)
* The user can see their data in the form of a list (tracked medicines, dosages, and frequency). They can also update and delete existing data. Update can be done via a similar form as adding new data (with field values already populated with existing data).
* Build/use a cron job or service to send email or text reminders to the user to take the medicine at the right time.
