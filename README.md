# Timetable website

This website fetches timetable data from "Trafiklab" (trafiklab.se - a free swedish national website with APIs for swedish public transport).
It then presents data for departures relevant to me.
If you want to use the data yourself, getting keys for the APIs is free, play around with it. They have good documentation.

Potential future updates:
- Make API requests from my own server and serve the data from there so less requests are made to the API (since there is a limit)
- Make it easier to add stops or remove stops to be shown. (at the moment, hard-coded)
