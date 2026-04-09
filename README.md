📘 Project Title

Decision-Driven Autonomous Self-Healing Cloud Infrastructure with Blockchain-Based Trust and Recovery Management


---

🚀 Overview

This project implements an autonomous self-healing cloud system that monitors system health (CPU, RAM, Disk), detects failures, classifies them, and automatically performs recovery actions. It also maintains a blockchain-based log for secure and tamper-proof recovery tracking.


---

⚙️ Features

Real-time system monitoring

Failure detection (CPU, RAM, Disk)

Failure classification

Decision-driven recovery engine

Automatic healing (process kill, cleanup, memory release)

Blockchain-based logging

Live dashboard with graphs

AI-based analysis (Neural Insight Engine)

Trust score system

Incident timeline and recovery logs



---

🧠 Technologies Used

Java (Spring Boot)

Maven

HTML, CSS, JavaScript

Chart.js

Linux system commands



---

📊 System Modules

Monitoring Module

Detection Module

Classification Module

Decision Engine

Recovery Module

Blockchain Logging

Dashboard UI



---

🔧 How to Run

mvn clean install
mvn spring-boot:run

Open browser:

http://localhost:8080


---

🧪 Failure Simulation

CPU overload:

yes > /dev/null &

RAM overload:

python3 -c "a=[]; import time; [a.append('A'*10**6) for i in range(5000)]; time.sleep(600)"

Disk overflow:

dd if=/dev/zero of=/tmp/bigfile bs=1M count=5000


---

🔗 Future Scope

Machine learning-based prediction

Kubernetes auto-scaling

Distributed cloud architecture

Real blockchain integration



---

👨‍💻 Author

Pratheesh Kumar
Titu Jeshurun
