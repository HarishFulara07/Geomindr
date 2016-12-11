# Geomindr

This is an android app which gives location based reminders to the user.

<br>

### Motivation
-

* Existing methods for creating reminders are unable to make use of rich contextual information to present a reminder at appropriate times in appropriate locations.

  * A grocery list reminder is more helpful while passing the supermarket en route home from work, rather than while at work or after getting home.
  
* Context-awareness can improve the usefulness of automated reminders.

* Mobile phones provide a convenient and truly ubiquitous platform for the detection of personal context such as location, as well as the delivery of reminders.

<br>

### Project Idea
-

Two types of reminders:

1. **Task Based**: Perform specific tasks at particular locations. For example,
  * **Post on my facebook wall** when I am at a movie theatre.
  * **Message** my parents when I arrive or leave college.
  * **Trigger alarm** when I reach Govindpuri Metro Station.

2. **Entity Based**: Remind user when he is nearby a particular entity. For example,
  * **Remind me to withdraw cash** from ATM whenever I am nearby an ATM.
  * **Remind me to pick food items** whenever I am nearby a grocery store.

<br>

### Implementation
-

* **Post on facebook wall** - Facebook SDK for Android.

* **Message and Trigger Alarm** - Android SDK’s APIs.

* **Entity Based Reminder** - Google Map API.
