# DDoS Attack Using LOIC 

## Introduction
This project demonstrates a Distributed Denial of Service (DDoS) attack using the LOIC tool on Kali Linux. The primary goal is to understand the risks associated with DDoS attacks and explore the defensive measures that can be implemented.

## What is a DDoS Attack?
A Distributed Denial of Service (DDoS) attack is a cyber attack where multiple compromised systems are used to flood a target with excessive traffic, causing it to become slow or unresponsive.

## What is LOIC?
LOIC (Low Orbit Ion Cannon) is a network stress testing tool commonly used to perform Distributed Denial of Service (DDoS) attacks. It was initially developed for stress testing and debugging network services but has also been widely used for malicious purposes.

## Key Features
User-Friendly Interface: LOIC provides a graphical user interface (GUI) that makes it accessible for users with limited command-line experience.
Multiple Attack Methods: It supports various types of attack methods including TCP, UDP, and HTTP floods, allowing users to overwhelm a target with high volumes of traffic.
Customizable Parameters: Users can configure attack parameters such as the target IP address, port, and the number of threads used to generate traffic.
How LOIC Works
LOIC operates by sending a large volume of requests to a target server. The traffic generated can exceed the capacity of the server or network, causing it to become slow or unresponsive. The tool allows for coordinated attacks from multiple sources, often by leveraging botnets or multiple instances of LOIC running simultaneously.

## Usage
LOIC can be used to simulate DDoS attacks in a controlled environment for educational purposes or stress testing. It is important to note that unauthorized use of LOIC for attacking external networks or servers is illegal and unethical.

## Ethical Considerations
This project focuses on using LOIC for educational purposes within a controlled environment. Always ensure you have explicit permission before conducting any network stress tests or attacks. Unauthorized DDoS attacks can result in serious legal consequences and ethical violati


## Installation
Prerequisites
- Kali Linux
- LOIC tool
- Git

## Installation Steps
sudo apt-get update
sudo apt-get install git
git clone https://github.com/NewEraCracker/LOIC.git


## STEPS TO PERFORM ATTACK
cd LOIC
mono LOIC.exe

<img width="663" alt="image" src="https://github.com/user-attachments/assets/ab81c420-25e1-4c10-a66d-15bc4f409fff">

in the url enter testphp.vulnweb.com
under target testphp.vulnweb.com
select TCP under methods and set threads to 10000000
click Ready(IMMA CHARGIN MAH LAZER)

<img width="664" alt="image" src="https://github.com/user-attachments/assets/ff48b7c2-3e1e-4d98-b5b7-bfe583f15ee9">

## OBSEVATIONS
The target system displayed various timeout errors and resource exhaustion messages.
LOIC successfully overwhelmed the target system, causing it to become unresponsive.
The LOIC tool generated approximately 5,000 requests per second, leading to a substantial increase in bandwidth usage.
Traffic volume peaked during the first 10 minutes of the attack and then stabilized at a high level.


## Results and Analysis
The DDoS attack caused a significant delay in the target server's response time.

Legal and Ethical Disclaimer
This project is intended for educational purposes only. Unauthorized use of DDoS attacks is illegal and unethical. Always perform tests in a controlled environment with proper authorization.

## License
This project is licensed under the MIT License.

## Contact
For questions, contact khushijain21200@gmail.com 

## Acknowledgments
Special thanks to the Kali Linux community and the developers of the LOIC tool.
