# Assignment2-coplur
Assignment: Employee Notification System
Use Case:
Your organization wants to implement a Notification System to inform employees about updates, events, or alerts. Notifications can be sent through various channels, such as email, SMS, and push notifications. Each channel has a different implementation, but all follow a common interface.
The system should allow selecting the notification type dynamically and ensure that it can be extended in the future without modifying the existing code.
________________________________________
Task Description:
You are required to implement a Notification System with the following functionality:
1.	Abstraction: Define a common contract for sending notifications through different channels.
2.	Inheritance: Implement specific notification types inheriting from the base class.
3.	Dynamic Selection: The system should allow selecting a notification type (email, SMS, or push notification) at runtime and send messages accordingly.
________________________________________
Scenario:
Imagine a situation where:
1.	New Policy Announcement: HR needs to notify employees about a new policy update.
2.	Event Reminder: The Events team wants to send a reminder for an upcoming office event.
3.	System Alert: IT wants to notify employees about a scheduled server downtime.
Each of these notifications can be sent through email, SMS, or push notifications depending on the employee's preferences.
