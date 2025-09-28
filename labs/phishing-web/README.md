Phishing & Web Attack Labs
Hands‑on analysis of phishing artifacts and common web attack detections with reproducible writeups.

What goes here
Writeups for email header/URL/macro analysis and basic web attack logs (SQLi/XSS).

Indicators, tooling, and step‑by‑step screenshots for reproducibility.

Deliverables checklist()
 []  Phishing analysis lab writeup with IoCs and verdict.

 []  Web attack detection writeup (logs, query, and alert).

 []  ATT&CK mapping for techniques observed.

 Challenges:
 A user has received a phishing email and forwarded it to the SOC. Can you investigate the email and attachment to collect useful artifacts?
 https://blueteamlabs.online/home/challenge/16
 <img width="574" height="338" alt="image" src="https://github.com/user-attachments/assets/5d856fda-58de-4fb6-a679-e3bcbf702182" />
 1. Who is the primary recipient of this email ?
 <img width="1041" height="623" alt="image" src="https://github.com/user-attachments/assets/7a1244ca-e2bd-40ef-8ea7-348db6f872ed" />
 Answer : kinnar1975@yahoo.co.uk

2. What is the subject of this email ?
<img width="1039" height="628" alt="image" src="https://github.com/user-attachments/assets/ea1d287c-83cb-4149-be3f-649b8b4cd80f" />
Answer : Undeliverable: Website contact form submission

3. What is the date and time the email was sent ?
<img width="1039" height="629" alt="image" src="https://github.com/user-attachments/assets/ac64a342-4d8f-4abf-929d-62f5ddeabba7" />
Answer : 18 March 2021 04:14

4. What is the Originating IP?
<img width="1042" height="290" alt="image" src="https://github.com/user-attachments/assets/b4a1166a-04d6-453b-8a06-677401a59f65" />
Answer : 103.9.171.10

5. Perform reverse DNS on this IP address, what is the resolved host? (whois.domaintools.com) ?
<img width="1040" height="466" alt="image" src="https://github.com/user-attachments/assets/eee13d05-dc0f-42d5-a179-b97044e84337" />
Answer : c5s2-1e-syd.hosting-services.net.au

6. What is the name of the attached file ?
<img width="1037" height="591" alt="image" src="https://github.com/user-attachments/assets/0f48fe18-73fa-4513-a729-4aae53d2c5b5" />
Answer : Website contact form submission.eml

7. What is the URL found inside the attachment ?
<img width="1027" height="314" alt="image" src="https://github.com/user-attachments/assets/41ee5b31-8a73-4eab-a2d8-536dd515c17e" />
Answer : https://35000usdperwwekpodf.blogspot.sg?p=9swghttps://35000usdperwwekpodf.blogspot.co.il?o=0hnd

8. What service is this webpage hosted on ?
<img width="1031" height="306" alt="image" src="https://github.com/user-attachments/assets/657d5fef-80a3-4098-bff8-32d1916a1f3e" />
Answer : blogspot

9. Using URL2PNG, what is the heading text on this page? (Doesn't matter if the page has been taken down!)
<img width="911" height="242" alt="image" src="https://github.com/user-attachments/assets/2c59eaf4-6ada-4865-9e78-89863c7c848d" />
Answer : Blog Has been removed

 Phishing Analysis 1(BLTO) ->  https://blueteamlabs.online/home/challenge/phishing-analysis-2-a1091574b8
