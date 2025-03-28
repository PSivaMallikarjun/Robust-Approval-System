# Robust-Approval-System
 Agentic AI Web App in Google Colab using Gradio UI. This app simulates a Robust Approval System for an Online Recruitment System in a Job Portal
# Introducing A AI-Powered Job Application Approval System

## Overview
This is an AI-driven **Robust Approval System** for an **Online Recruitment System in a Job Portal**. It utilizes **machine learning** to evaluate job applications in real time. If an application meets the required criteria, it is automatically approved. Otherwise, the user is prompted to reapply until approval is granted, ensuring no duplicate applications and optimal storage management.

## Features
- **ML-based Approval System**: Uses an AI model to analyze job applications.
- **Gradio UI Integration**: Provides a simple web interface for users to submit applications.
- **Automated Approval Process**: Instantly approves valid applications.
- **Cyclic Reapplication**: Allows users to improve and resubmit applications.
- **Duplicate Prevention**: Ensures only one application per user is processed at a time.
- **Optimized Storage**: Stores only necessary application data, avoiding redundancy.

## Installation & Setup
### Prerequisites
- Python 3.x
- Google Colab (or local Python environment)
- Required libraries: `gradio`, `json`

### Steps to Run
1. **Clone the Repository** (if hosted on GitHub):
   ```bash
   git clone <repository_url>
   cd <project_directory>
   ```
2. **Install dependencies**:
   ```bash
   pip install gradio
   ```
3. **Run the Application**:
   ```bash
   python app.py
   ```
4. **Access the UI**:
   - The Gradio interface will open in your browser.
   - Enter your **User ID** and **Job Application** details.
   - Click "Submit Application" to receive an approval decision.

## Usage Instructions
1. **Enter User ID** (e.g., 2345)
2. **Provide Job Application Details** (mention experience, skills, education, certifications)
3. **Submit the Application**
4. **Approval Status**:
   - ✅ Approved: Proceed with job postings.
   - ❌ Rejected: Modify and resubmit with better details.

## Example Input & Output
### **User Input**
```
User ID: 2345
Application: "I have 5 years of experience in software development, skilled in Python and ML. I hold a Master’s degree in Computer Science and have completed multiple projects in AI. Additionally, I possess AWS and Azure certifications."
```

### **System Output**
```
✅ Application Approved! You are eligible for job postings.
```

## Future Enhancements
- **AI-powered feedback** for rejected applications
- **Integration with external job portals**
- **Cloud-based deployment for scalability**

## License
This project is open-source and available under the [MIT License](LICENSE).



![Screenshot 2025-03-28 221456](https://github.com/user-attachments/assets/81d47a1a-c279-430b-884f-3ac6998c80ce)
![Screenshot 2025-03-28 221421](https://github.com/user-attachments/assets/7a98f7e4-dccb-489b-998d-73466e5f152b)
