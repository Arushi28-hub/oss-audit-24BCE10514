# oss-audit-24BCE10514
Open Source Software Audit Project
About This Project

Hi, I’m Arushi Bakshi, and this repository is part of my Open Source Software (OSS) Audit coursework.

Instead of just reading theory, I wanted to actually see how things work in a real system. So I created a set of Bash scripts that explore, inspect, and analyze different aspects of an open-source environment.

I chose Mozilla Firefox as my reference software and built small scripts around it to understand how open-source tools behave at the system level.

What This Project Covers

Through this project, I explored:

System-level information and identity
Open-source package inspection
File permissions and disk usage
Log file analysis
The philosophy behind open-source 

 Scripts Included
🔹 Script 1: System Identity Report

Gives a quick overview of the system:

OS distribution
Kernel version
Current user
Uptime
Date
Also connects it to open-source licensing (GPL)


🔹 Script 2: FOSS Package Inspector
Checks if a package (like Firefox) is installed
Displays version, maintainer, and description
Adds a short human-friendly explanation of the software



🔹 Script 3: Disk & Permission Auditor
Scans important directories like /etc, /home, /tmp
Shows:
Permissions
Owner/group
Directory size
Also checks Firefox configuration directory



🔹 Script 4: Log File Analyzer
Takes a log file and a keyword (default: error)
Counts how many times the keyword appears
Shows last 5 matching lines


🔹 Script 5: Open Source Manifesto Generator



Asks you 3 questions
Generates your own open-source manifesto
Saves it in a text file



⚙️ How to Run

Clone the repository:

git clone https://github.com/Arushi28-hub/oss-audit-24BCE10514.git
cd oss-audit-24BCE10514

Make scripts executable:

chmod +x script.sh script2.sh script3.sh script4.sh script5.sh

Run any script:

./script.sh

For log analyzer:

./script4.sh logfile.txt error
What I Learned

Working on this project made me realize that open-source is not just about free software—it’s about:

Transparency → you can actually see what’s happening
Control → you’re not locked into black-box systems
Collaboration → people build together

Also, writing these scripts helped me get more comfortable with:

Bash scripting
Linux commands
Thinking like a system analyst

Final Thoughts

This project is a small step into the world of open-source auditing and system analysis.
There’s a lot more depth to explore, but this gave me a solid starting point.
