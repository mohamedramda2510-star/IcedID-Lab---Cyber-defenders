IcedID – CyberDefenders Lab

Lab Overview

- Platform: CyberDefenders
- Lab Name: IcedID
- Category: Threat Intel
- Difficulty: Easy
- Estimated Time: 30 Minutes
- Status: Completed (6/6)

Objective

Investigate IcedID malware using VirusTotal and threat intelligence platforms to identify Indicators of Compromise (IOCs), associated threat actors, and execution mechanisms.

Tools Used

- VirusTotal
- Malpedia
- X
- Triage
- ANY.RUN

---

Investigation & Findings

Q1 – Malware Filename

Question: What is the name of the file associated with the given hash?

Finding: "document-1982481273.xlsm"

Evidence:

<img width="1837" height="188" alt="Screenshot (27)" src="https://github.com/user-attachments/assets/f3fbfb84-e179-4ff7-99b9-b62b5bf22b98" />


---

Q2 – Deployed GIF File

Question: Can you identify the filename of the GIF file that was deployed?

Finding: "3003.gif"

Evidence:

<img width="612" height="293" alt="Screenshot (28)" src="https://github.com/user-attachments/assets/b30233ae-930f-4bc2-8bcf-63d06094537e" />


---

Q3 – Malicious Domains

Question: How many domains does the malware look to download the additional payload file in Q2?

Finding: "5 Domains"

Evidence:

<img width="752" height="391" alt="Screenshot (29)" src="https://github.com/user-attachments/assets/60d1f9c4-821d-42d9-8028-e25836359b99" />


---

Q4 – DNS Registrar

Question: What is the Registrar INC of the domain ending with .com used to host the harmful content?

Finding: "NameCheap"

Evidence:

<img width="1819" height="165" alt="Screenshot (30)" src="https://github.com/user-attachments/assets/36c88c9b-2f95-44e7-a801-b440ae744e38" />


---

Q5 – Threat Actor Attribution

Question: Can you specify the threat actor linked to the sample provided?

Finding: "GOLD CABIN"

Evidence:

<img width="1175" height="940" alt="Screenshot (31)" src="https://github.com/user-attachments/assets/cbff59ae-df6c-4e2f-a8d4-12cd3588b9dc" />


---

Q6 – Payload Download Function

Question: In the Execution phase, what function does the malware employ to fetch extra payloads onto the system?

Finding: "URLDownloadToFileA"

Evidence:

<img width="1591" height="544" alt="Screenshot (32)" src="https://github.com/user-attachments/assets/33824301-b93c-4f31-ba6e-f17c7a274369" />



---

Key Findings

Indicator| Value
Malware Name| IcedID
Initial File| document-1982481273.xlsm
Deployed GIF| 3003.gif
Number of Domains| 5
DNS Registrar| NameCheap
Associated Threat Actor| GOLD CABIN
Download Function| URLDownloadToFileA

Conclusion

Successfully completed the IcedID investigation by analyzing the provided malware sample and using threat intelligence platforms.

The investigation identified the initial XLSM file, deployed GIF payload, associated malicious domains, DNS registrar, threat actor attribution, and the Windows API function used to download additional payloads.

This lab improved practical skills in malware investigation, threat intelligence analysis, IOC identification, and understanding malware execution mechanisms.

Lab Status: 6/6 Questions Completed.
