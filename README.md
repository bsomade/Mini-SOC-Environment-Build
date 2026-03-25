# Mini-SOC-Environment-Build

## Objective

The Mini SOC Environment Build is aimed at building a security operations center from scratch utilizing Jira as a customer facing ticketing system and Elastic as a SIEM to ingest Windows logs for endpoint analysis. 

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Ability to generate and recognize attack signatures and patterns.
- Research relevant attack vectors and develop detections to respond to emerging threats.

### Tools Used

- Elastic SIEM for log ingestion and analysis.
- Jira ticketing system for workflow management and SIEM integration.
- Atomic Red Team to test and validate detections.

## Steps
1) Configure customer ticketing system by managing workflow diagram to respond to alerts. <img width="906" height="574" alt="Ticket Settings Workflow with Jira" src="https://github.com/user-attachments/assets/de7016b7-6ff2-4d9c-ac2f-ffed302b1d9b" /> <img width="1903" height="938" alt="Configure Ticket Settings with Jira" src="https://github.com/user-attachments/assets/beee0e2c-4800-4758-b92f-9db92850f8e7" />
2) Use Elastic agent to connect to endpoint for log analysis. <img width="1010" height="551" alt="Script Used to Connect Endpoint to Elastic for log analysis" src="https://github.com/user-attachments/assets/dedeffd1-5249-46b2-a7f4-9a36ff1d81f3" /> <img width="1912" height="958" alt="Used Elastic Agent to Connect to Endpoint for log analysis" src="https://github.com/user-attachments/assets/b59e1d70-351a-4338-a38d-6c84f15cc9ea" />
3) Use KQL to run net user discovery detection in Elastic. <img width="1038" height="542" alt="Using KQL to run custom detections in elastic_1" src="https://github.com/user-attachments/assets/a1ea85d0-fb0a-4621-a792-1dff65f18f56" /> <img width="1031" height="690" alt="Using KQL to run custom detections in elastic_2" src="https://github.com/user-attachments/assets/4774331d-5f51-482f-a0f2-9e5c8f150deb" /> <img width="1011" height="541" alt="Using KQL to run custom detections in elastic_3" src="https://github.com/user-attachments/assets/da652538-1bdd-4f53-9849-e2d8c7243147" /> <img width="991" height="652" alt="Using KQL to run custom detections in elastic_4" src="https://github.com/user-attachments/assets/ecbabe4b-d670-43c0-8b8b-8f97e82a5844" />
4) Link net user discovery detection in elastic to Jira API. <img width="1030" height="665" alt="Linking custom detections in elastic to Jira API" src="https://github.com/user-attachments/assets/9cb1adb3-3399-4800-810e-22f0498447c5" />
5) Test net user discovery detection with Atomic Red Team. <img width="847" height="628" alt="Testing Net User Discovery with Atomic Red Team_1" src="https://github.com/user-attachments/assets/54088de7-1e30-4fc8-b817-6a2e49eaadbb" /> <img width="966" height="630" alt="Testing Net User Discovery with Atomic Red Team_2" src="https://github.com/user-attachments/assets/717fced3-dd14-4433-b15d-ef5a7cfafb09" /> <img width="1537" height="553" alt="Testing Net User Discovery with Atomic Red Team_3" src="https://github.com/user-attachments/assets/ee86e7d9-779f-4a90-a524-147e0b341a33" />
6) Investigate net user discovery alert in Jira. <img width="1651" height="867" alt="Investigating a Net User Discovery Alert in Jira_1" src="https://github.com/user-attachments/assets/ffe697f2-503a-4a2e-91ff-2be537e8438d" /> <img width="1661" height="579" alt="Investigating a Net User Discovery Alert in Jira_2" src="https://github.com/user-attachments/assets/0e01f753-7e95-479c-a059-cee0d9d6b2d6" />
7) Use EQL to run a scheduled task detection in elastic. <img width="752" height="856" alt="Using EQL to run a custom detection in elastic_1" src="https://github.com/user-attachments/assets/2cb0f5c4-a59a-45d2-bc11-90d735c204de" /> <img width="751" height="844" alt="Using EQL to run a custom detection in elastic_2" src="https://github.com/user-attachments/assets/bd3ab5f1-6117-4a1c-8c45-b6eba32e1a0c" /> <img width="1511" height="510" alt="Using EQL to run a custom detection in elastic_2 1" src="https://github.com/user-attachments/assets/0ecccb51-92bc-4fd5-89c6-bdf10a5b16fb" /> <img width="1545" height="483" alt="EQL custom detection test in elastic" src="https://github.com/user-attachments/assets/c90a1a98-fa6f-402e-929a-0d290efafc2c" /> <img width="1648" height="854" alt="EQL custom detection ticket in Jira" src="https://github.com/user-attachments/assets/c0d5669f-b37d-4583-aecd-71f06e92283b" />
8) Use Elastic to conduct host investigation based on customer alert (re: scheduled task detection and associated atomic). <img width="1798" height="713" alt="Building a Timeline Investigation with Cases in Elastic_3" src="https://github.com/user-attachments/assets/08c04286-309e-448a-95f0-bd4b6ff5f20c" /> <img width="1810" height="905" alt="Host Investigation Initial Access T1566 001" src="https://github.com/user-attachments/assets/f4df783d-d4ad-4bfa-be56-6dabd70e8d4c" /> <img width="1816" height="911" alt="Host Investigation Execution T1059 001" src="https://github.com/user-attachments/assets/ee2268de-6824-4c7b-94dc-fbe516cd3e39" /> <img width="1817" height="909" alt="Host Investigation Persistence T1547 001" src="https://github.com/user-attachments/assets/8784083a-b5e0-4fdd-99ca-34912c395277" /> <img width="1809" height="898" alt="Host Investigation Defense Evasion T1027 10" src="https://github.com/user-attachments/assets/c7de08ad-d305-492e-b95d-4920532e73e5" /> <img width="1816" height="910" alt="Host Investigation Collection T1113" src="https://github.com/user-attachments/assets/106742fe-d6c4-4c99-a377-83b28f2cbcf0" /> <img width="1815" height="904" alt="Host Investigation Exfiltration T1041" src="https://github.com/user-attachments/assets/fa648855-dc9e-4f3f-80fb-38b322cf50d7" /> <img width="1808" height="899" alt="Host Investigation Command and Control T1105" src="https://github.com/user-attachments/assets/2c79f200-990d-4f2e-a4cc-768fa6c0465c" />













   

















