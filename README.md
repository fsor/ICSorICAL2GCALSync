# ICSorICAL2GCALSync

Enhanced the google apps script to auto sync booking / calendar events from wordpress plugin (https://wordpress.org/plugins/booking/) to a google calendar

"Booking Calendar generates an .ics feed with bookings in real time. But how often some service (like google calendar) access this .ics feed to import the bookings from Booking Calendar, does not depend from Booking Calendar. That means Booking Calendar does not force third party services to start the import when a new booking is created, deleted or changed." This script (file: Code.gs) triggers the google calendar's import process to drop all existing events and re-import them.

Features:
* Set syncing interval manually (wait minutes for the events to appear in your google calendar instead of 48 hours)
* Also sync deleted / changed bookings
