# College Mess Management System

## Overview
The **College Mess Management System** is a **Bash-based command-line application** that automates mess management, allowing students to mark attendance, track meal quotas, generate bills, and submit feedback.

## Features
- 📌 **Student Attendance Tracking** – Records meal consumption.
- 📝 **Billing System** – Calculates individual and collective student bills.
- 🍽️ **Meal Quota Management** – Allocates 90 meals per month and adjusts dynamically.
- 🔄 **Automated Monthly Reset** – Carries over unused meal quotas.
- 🗣️ **Feedback Collection** – Stores student feedback for service improvement.
- 📅 **Weekly Menu Display** – Provides a predefined meal schedule.

## Technologies Used
- **Bash Scripting**
- **File Handling** (text-based data storage)

## Installation & Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/college-mess-management.git
   cd college-mess-management
   ```
2. Run the script:
   ```bash
   chmod +x mess_management.sh
   ./mess_management.sh
   ```

## File Structure
- `attendance.txt` – Stores attendance records.
- `feedback.txt` – Stores student feedback.
- `students.txt` – Maintains student names and meal quotas.
- `current_month.txt` – Tracks the current month for quota resets.

## Future Enhancements
- ✅ Database integration for better scalability.
- ✅ Web-based UI for an improved user experience.

## License
This project is open-source and available under the **MIT License**.

## Author
Developed by Shaik Khaja | [GitHub](https://github.com/yourusername)
