# Prevent-User-Deletion-if-Assigned-to-Incident
📌 About the Project

This project is built using the ServiceNow platform to improve Incident Management and maintain data integrity within an organization.

It prevents accidental deletion of users who are assigned to active incidents, ensuring smooth workflow and system reliability.

The application manages:

• User records
• Incident assignments
• Data validation before deletion
• Workflow protection

🎯 Objective

The goal of this project is to make Incident Management:

• Secure
• Reliable
• Error-free
• Process-oriented
• Data-consistent

🚀 Features

✅ Prevent deletion of users assigned to active incidents
✅ Automatic validation using Business Rule
✅ Real-time error message display
✅ GlideRecord-based incident checking
✅ Workflow continuity protection
✅ Data integrity maintenance

🏗️ Modules Created
👤 User Table (sys_user)

Stores user details and assignment information.

🎫 Incident Table

Stores incident records and assigned users.

⚙️ Business Rule (Before Delete)

Checks whether the user is linked to any active incidents before deletion.

⚙️ Automation Used

• Before Delete Business Rule
• GlideRecord Query to check assigned incidents
• setAbortAction(true) to stop deletion
• Error message display using gs.addErrorMessage()
• Role-based access validation

💡 Business Rule Logic

✔ Check if user is assigned to any active incident
✔ If yes → Block deletion
✔ Show error message
✔ Maintain incident ownership
✔ Prevent broken references

🛠️ Technologies Used

• ServiceNow Platform
• JavaScript (Server-side scripting)
• GlideRecord API
• Business Rules
• Incident Management Module

👥 Team

Team Leader: Pachigolla Devi Likitha
Team Member: Koppaka Gnanendra Chowdary
Team Member: Kurma Jasta Naga Jyoshna
Team Member: K.Akash Babu


✅ Conclusion

This project demonstrates how ServiceNow can ensure system integrity by preventing accidental deletion of users assigned to incidents.
By implementing a Before Delete Business Rule, the system maintains workflow continuity, protects data relationships, and ensures reliable Incident Management within an organization.
