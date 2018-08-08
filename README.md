# Event_Fetcher


**FEATURES**
1. Fetche the next Birthday Event from the Calendar.
2. Creates an new event in the Calendar.

**API USED**
Google Calendar API

**ASSUMPTIONS**

1. It is assumed that primary calendar only contains the Birthday Events. Hence, would fetch the next Birthday Event. 

    Alternate approach could be to create a new calendar. Which is only a Birthday Calendar. Get calendar ID for this
    calendar and replace calendarId = 'primary' with the new calendar ID and proceed.


**STEPS TO RUN THE CODE**

1. git clone 
1. Enable the Google Calendar API https://developers.google.com/calendar/quickstart/python
2. Go to above link. Click on enable the calendar API.
3. Create or Select from your existing projects. Click on Next. Select download client configrations. 
4. Credentials.json would be downloaded onto your system. Copy from downloads folder and place credentials.json
   the cloned repository.
5. Go into the cloned repository. Create virtual enviornment.
   On Linux
   
   `virutalenv venv`
   
6. Activate the virtual enviornment

   `source venv/bin/activate`
   
7. Install all the requirements.

   `pip install -r requirements.txt`

8. Run the file. 

   `python credentails.py`

9. It will prompt you and token.json would be installed. Once you give the
   allow the application to access the calendar.

**INFORMATION**

1. credentials.py - Is the main source code 
2. config.py - Contains the JSON which is needed for the event creation.



