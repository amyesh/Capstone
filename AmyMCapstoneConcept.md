# Capstone Concept - Amy Martinsen
****
## Problem Statement #1
Dating apps currently allow users to cast a wide net rather than exhibit selectivity, and unlimited text 
messaging as the main form of communication prolongs often dead-end interactions where compatibility could be more 
quickly determined via phone call. Haunt limits user selection per day, displays (essential!) information about their potential match's birth chart, and sums up compatitiblity in a single emoji. If matched, users can select a time to talk on the phone, and the app then connects them anonymously.
****
## MVP Feature Set
### Login/logut functionality
- OAuth
### User info retrieval
- Users should be able to input certain information that will influence future preferences/browsing.
### User info display
- Photographs, blurb (and astrology info!)
### Scrolliing
- Users should be able to browse all users they're interested in based on preferences.
### Selection/Matching
- Users can select up to (5-10?) potential matches per day, if they've matched, both users will be notified.
### Notifications
- Multiple types of notifications are needed - match notification/call time notification
### Scheduling
- Once matched, users must both select from available call windows.
### Anonymous In-App Voice Calling
- Once a time is agreed upon, the app will automatically connect users at the given time.
- Would love to have this be an anonymous feature in the app, but I'm not sure if that's possible.
****
## Potential Additional Features
### Co-Star-like Astrology Compatibility (https://www.costarastrology.com/)
- include a VERY minimal amount of logic that displays users birth chart via collected user info, and gives also 
minimal (but really fun!) compatibility assessments between users. The Co-Star app uses data from Nasa's API to do
their analysis. This is really cool, but I obviously would do something much simpler!
### Three Strikes Policy
- Users can report other users for ghosting. Three reports and you're off the app.
****
## Draft Technology Choices
- Java
- Android Studio
- OAuth
- Twilio or Google Voice
- Google Firebase