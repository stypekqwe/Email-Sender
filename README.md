# Email-Sender
Small application with a GUI making it easier to send out emails asking recipients for information. The application was prepared for
MS Outlook 2013 and may not work newer versions of outlook.

The app enables you to access certain items (UCIs) as well as their features (accounts and contact information)

Once the script is run, it accesses two databases:
- the database with contact information for UCIs
- the archive file that enables tracking and archiving the requests.

Then, the Tkinter GUI opens up asking the user for a UCI. Once the UCI is entered, a new pandastable window appears.
It shows the accounts linked to the UCI as well as their contact information. The user may now send an automated email to
automatically populated receipients.
