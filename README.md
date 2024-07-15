# Blood Glucose Monitoring App

The Blood Glucose Monitoring App is application for tracking and managing blood glucose readings. It supports both mg/dL and mmol/L units and allows users to view their readings for today, yesterday, the past week, and the past month. This app is partially HIPAA-compliant

# Features
	•	Record blood glucose readings
	•	View readings for different time periods
	•	Average blood glucose calculation
	•	Unit conversion between mg/dL and mmol/L
	•	Custom logger for debugging and error tracking
	•	Dependency Injection (DI) for better testability and maintainability

 # Requirements
 	•	iOS 16.0+
	•	Xcode 15.0
	•	Swift 5.0+

 # Architecture
 The app follows the MVVM (Model-View-ViewModel) architecture pattern. It uses Core Data for local storage and implements dependency injection to improve testability and maintainability.

# Core Data Encryption
Core Data encryption is implemented using the NSPersistentStoreFileProtectionKey to ensure data security and HIPAA compliance.

# Future improvement scope
**Must Have(To make it fully HIPAA-compliant application):**
- Custom core data migration
- Face ID/Biometric based authentication

**Need to Have(Feature based improvements):**
- Edit/Delete records
- See all the records
- Add feature of fasting glucose records and after meal separately as well

**May Have:**
- Exports and share records in pdf format

**Good to have:**
- App Analytics
- Push notification for reminder to add the record
- Notify/Alarm care taker person if condition is severe

