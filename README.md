# salesforce-hospital-management-system

This project is a custom-built Hospital Management System (HMS) developed in a Salesforce Developer Org using Flow Automation. It streamlines hospital workflows such as scheduling appointments, notifying doctors, and creating records without writing code.

## Key Features

-  Automatically create Medical Records when an Appointment is scheduled  
-  Notify the assigned Doctor via email upon Appointment creation  
-  Auto-generate Prescription Templates when Treatment Plans are completed  
-  Auto-create Billing Records upon Treatment completion  
-  Send Email Reminders to Patients before their Appointment time

## Tools & Technologies Used

- Salesforce Developer Org  
- Flow Builder (Record-Triggered Flows, Scheduled Paths)  
- Email Alerts and Templates  
- Custom Objects (Appointment, Medical Record, Prescription, Billing, etc.)

## What I Learned

- Designing real-world hospital workflows using Salesforce Flows  
- Managing object relationships like Patient ↔ Appointment ↔ Doctor  
- Implementing email alerts and flows  
- Debugging flow issues and handling email delivery challenges

## Screenshots

1. **App Launcher – Search Hospital Management System**  
   ![App Launcher](Screenshot 2025-07-03 202850.png)

2. **Custom Objects Included**  
   _(Appointment, Patient, Doctor, Medical Record, Prescription, Billing, etc.)_  
   ![Custom Objects](Screenshot 2025-07-03 195336.png)

3. **Create Appointment Flow (Screen Flow)**  
   ![Create Appointment Flow](Screenshot 2025-07-03 201336.png)

4. **Auto Medical Record Creation Flow**  
   _Triggered when an appointment is scheduled._  
   ![Medical Record Flow](Screenshot 2025-07-03 201555.png)

5. **Notify Doctor via Email Flow**  
   _Email alert sent to the assigned doctor._  
   ![Notify Doctor](Screenshot 2025-07-03 201445.png)

6. **Auto Billing on Treatment Completion**  
   _Billing record automatically created when treatment is completed._  
   ![Auto Billing](Screenshot 2025-07-03 201527.png)

7. **Generate Prescription on Treatment Completion**  
   _Creates a prescription record automatically once treatment is completed._  
   ![Prescription Flow](Screenshot 2025-07-03 201634.png)
