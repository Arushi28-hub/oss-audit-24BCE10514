Open Source Software Audit Project

👋 About This Project

Hi, I’m Arushi Bakshi, and this repository is part of my Open Source Software (OSS) Audit coursework.

Instead of just reading theory, I wanted to actually see how things work in a real system. So I created a set of Bash scripts that explore, inspect, and analyze different aspects of an open-source environment.

I chose Mozilla Firefox as my reference software and built small scripts around it to understand how open-source tools behave at the system level.

🎯 What This Project Covers

Through this project, I explored:

🖥️ System-level information and identity
📦 Open-source package inspection
🔐 File permissions and disk usage
📊 Log file analysis
💡 The philosophy behind open-source
🛠️ Scripts Included
🔹 Script 1: System Identity Report

Gives a quick overview of the system:

OS distribution
Kernel version
Current user
Uptime
Date
Connects it to open-source licensing (GPL)
🔹 Script 2: FOSS Package Inspector
Checks if a package (like Firefox) is installed
Displays version, maintainer, and description
Adds a short human-friendly explanation
🔹 Script 3: Disk & Permission Auditor
Scans important directories like /etc, /home, /tmp
Shows:
Permissions
Owner/group
Directory size
Also checks Firefox configuration directory
🔹 Script 4: Log File Analyzer
Takes a log file and a keyword (default: error)
Counts occurrences of the keyword
Displays last 5 matching lines
🔹 Script 5: Open Source Manifesto Generator
Asks you 3 simple questions
Generates your own open-source manifesto
Saves it as a text file
⚙️ How to Run
1️⃣ Clone the repository
git clone https://github.com/Arushi28-hub/oss-audit-24BCE10514.git
cd oss-audit-24BCE10514
2️⃣ Make scripts executable
chmod +x script.sh script2.sh script3.sh script4.sh script5.sh
3️⃣ Run any script
./script.sh
4️⃣ Run log analyzer
./script4.sh logfile.txt error
💡 What I Learned

This project helped me understand that open-source is not just about free software—it’s about:

Transparency → you can actually see what’s happening
Control → no dependency on black-box systems
Collaboration → people build together

It also improved my skills in:

Bash scripting
Linux commands
System-level thinking
📌 Final Thoughts

This project is a small step into the world of open-source auditing and system analysis.
There’s still a lot to explore, but this gave me a strong practical foundation.
