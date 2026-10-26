🔍 Network Port Scanner Using Python

📌 About the Project

The Network Port Scanner is a beginner-friendly cybersecurity project developed using Python. It checks a specified range of ports on a target IP address to identify which ports are open.

Open ports can indicate services running on a system. Understanding port scanning is useful for learning the basics of network security and cybersecurity.

This project was developed as a supplementary practical exercise alongside my cybersecurity learning.

🎯 Objectives

- Understand the basics of computer networks and port numbers.
- Learn how Python socket programming works.
- Identify open ports on a target system.
- Practise basic network scanning and result reporting.
- Develop practical cybersecurity skills.

🛠️ Technologies Used

- Programming Language: Python
- Editor: Visual Studio Code
- Module: Python "socket"
- Operating System: Windows

⚙️ Features

- Scans a specified range of ports.
- Identifies open ports.
- Displays scan results in the terminal.
- Saves scan results to a text file.
- Demonstrates basic socket programming.

🚀 How to Run the Project

1. Install Python

Download Python from "python.org" (https://www.python.org/downloads/) if it is not already installed.

2. Clone the Repository

git clone YOUR_GITHUB_REPOSITORY_URL

3. Open the Project Folder

cd network-port-scanner

4. Run the Python Script

python port_scanner.py

Note: Replace "port_scanner.py" with your actual Python filename if it is different.

🧪 Testing

The project was tested on the local loopback address "127.0.0.1". A temporary local HTTP server was started on port "8080", and the scanner checked ports "8078–8082".

The test demonstrated how a scanner can identify an open port on the local machine.

📂 Project Structure

network-port-scanner/
│
├── port_scanner.py
├── scan_report.txt
└── README.md

The files listed above should match the files you actually upload to the repository.

🔐 Ethical Considerations

This project is intended for educational purposes and authorized security testing only. Scan only your own systems or networks for which you have explicit permission. Do not scan public or third-party systems without authorization.

📚 Learning Outcomes

Through this project, I practised:

- Python programming fundamentals.
- Socket programming and network connections.
- Understanding IP addresses and port numbers.
- Identifying open ports in a controlled environment.
- Recording and documenting scan results.

👩‍💻 Author

Shaifali Upadhyay

BCA Student | Cybersecurity Enthusiast

📄 Disclaimer

This is a basic educational project. It is not a complete vulnerability assessment tool and does not identify every security weakness in a system.
