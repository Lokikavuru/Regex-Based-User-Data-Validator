# Regex-Based User Data Validator

A Python project that validates and formats user input (Name, Date of Birth, Email ID, and Mobile Number) using **only regular expressions**. This ensures accurate and structured input for form-style data.

---

## 🚀 Features

- ✅ Validates Name (only letters and spaces)
- ✅ Accepts DOB in `DD-MM-YYYY` format
- ✅ Extracts & prints:
  - `Birth day`
  - `Birth month` (e.g., "August")
  - `Birth year`
- ✅ Validates Gmail address (`yourname123@gmail.com`)
- ✅ Validates Mobile in `XXX-XXX-XXXX` format
- ✅ Removes `-` from mobile number in final output

---

## 💻 How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/regex-user-validator.git
   cd regex-user-validator
Run the script:

bash
Copy
Edit
python validator.py
🔍 Example Session
bash
Copy
Edit
Enter Your Name: Lokesh@123
Enter Name in Correct Format !
Enter Your Name: Lokesh Kumar

Enter Date of Birth (DD-MM-YYYY): 16-08-2002

Enter Email id: lokesh.gmail.com
Enter Mail id in correct format !
Enter Email id: lokesh2002@gmail.com

Enter Mobile Number (XXX-XXX-XXXX): 9876543210
Enter Mobile Number in correct Format !
Enter Mobile Number (XXX-XXX-XXXX): 987-654-3210
✅ Output
kotlin
Copy
Edit
Name : Lokesh Kumar
Birth day is 16
Birth month is August
Birth year is 2002
Mail id: lokesh2002@gmail.com
Mobile : 9876543210
📂 Project Structure
pgsql
Copy
Edit
regex-user-validator/
├── validator.py       # Main Python script
└── README.md          # Documentation
📜 License
This project is open source 
