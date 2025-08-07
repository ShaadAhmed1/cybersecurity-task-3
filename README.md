# cybersecurity-task-3

Objective
The goal of this task was to perform a basic vulnerability scan on my personal computer to identify common security issues using a free tool. This task was part of the CYBER SECURITY INTERNSHIP program offered by ELEVATE Labs.

Tools Used
I used Nessus Essentials, a free vulnerability scanner, to perform the assessment.

Methodology
1.  Installation & Setup: I installed and configured Nessus Essentials on my machine.
2.  Scan Target: I set the scan target to my local machine's IP address, which I identified as `172.26.61.227`.
3.  Scan Execution: I initiated a full vulnerability scan and allowed it to complete, which took approximately 30-60 minutes.
4.  Report Generation: After the scan finished, I generated a report from the Nessus interface. I selected the "Complete List of Vulnerabilities by Host" template to get a detailed overview of the findings for my PC.

Scan Results Summary
The scan successfully completed and identified 5 informational findings on my PC. It is important to note that these are not critical, high, medium, or low-severity vulnerabilities. They are simply pieces of information gathered by the scanner.

The informational findings include:
Ethernet Card Manufacturer Detection: This identified the manufacturer of my network card.
Ethernet MAC Addresses: The MAC address of my network adapter was detected.
Hyper-V Virtual Machine Detection: The scan identified that my system is a Hyper-V virtual machine, which is correct.
Nessus Scan Information: Details about the Nessus scan itself, such as the plugins used, were recorded.
Traceroute Information: The scan gathered network path information from the scanner to the target.



Conclusion
This exercise provided me with an introduction to vulnerability assessment and an understanding of how tools like Nessus identify potential risks and gather system information. The scan on my personal PC did not reveal any critical or high-severity vulnerabilities, which is a good sign. The process of using the tool, interpreting the results, and documenting the findings was a valuable learning experience.
