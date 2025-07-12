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
   ![App Launcher](app_launcher.png)

2. **Custom Objects Included**  
   _(Appointment, Patient, Doctor, Medical Record, Prescription, Billing, etc.)_  
   ![Custom Objects](custom_objects.png)

3. **Create Appointment Flow (Screen Flow)**  
   A screen flow that collects patient, doctor, and date inputs to create a new appointment.
   ![Create Appointment Flow](create_appointment_flow.png)

4. **Auto Medical Record Creation Flow**  
   Triggered when an appointment is created, automatically generates a related medical record. 
   ![Medical Record Flow](auto_medical_record.png)

5. **Notify Doctor via Email Flow**  
   Sends an automated email to the assigned doctor with appointment details upon creation.  
   ![Notify Doctor](notify_doctor.png)

6. **Auto Billing on Treatment Completion**  
   When a treatment is marked as completed, this flow creates an unpaid billing record.  
   ![Auto Billing](auto_billing.png)

7. **Generate Prescription on Treatment Completion**  
   Creates a prescription record with medicines and notes when treatment is completed.  
   ![Prescription Flow](generate_prescription.png)

8. **Hospital Admin Dashboard**    
   ![Dashboard](dashboard.png)

9. **Dashboard View**  
   _Displays key metrics and patient insights._  
   ![Dashboard](dashboard_view.png)
