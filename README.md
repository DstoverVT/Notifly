# Notifly
Note: This project uses Python 3.0+.

To begin adding upcoming rocket launches to your Google Calendar automatically through Notifly, follow these steps: 

1. Travel to Google's Calendar API quickstart website: https://developers.google.com/calendar/quickstart/python
2. Follow steps 1 and 2 and save the credentials.json file in the same directory as the python scripts
3. If your .json file is not named credentials.json, then change the api_credentials_json variable in notifly.py accordingly
4. Install the BeautifulSoup python library according to their website: https://www.crummy.com/software/BeautifulSoup/bs4/doc/#installing-beautiful-soup
5. Install the python Tkinter library using the command:
   sudo apt-get python3-tk
   OR install according to their website: https://tkdocs.com/tutorial/install.html
6. Run main_gui.py and choose one of the dropdown options followed by clicking the corresponding button, which should open your browser for authentication
7. Sign into your Google account, and click "Advanced" and then "go to <whatever the project name is (probably Quickstart)>"
8. Allow permissions and close out of the tab once you get the message saying that you can close the window
9. That's it! Notifly is now at your disposable to help you stay up to date with rocket launches forever

Notifly creates its own secondary calendar within your Google Calendar account and adds event to it. If you choose to "Delete all rocket launches",
the entire Notifly calendar will be deleted along with the events. 
