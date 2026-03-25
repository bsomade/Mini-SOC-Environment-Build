# Mini-SOC-Environment-Build

## Objective

The Mini SOC Environment Build is aimed at building a security operations center from scratch utilizing Jira as a customer facing ticketing system and Elastic as a SIEM to ingest Windows logs for endpoint analysis. 

### Skills Learned

- Advanced understanding of SIEM concepts and practical application.
- Ability to generate and recognize attack signatures and patterns.
- Research relevant attack vectors and develop detections to respond to emerging threats.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Ticketing system for workflow manaagement and SIEM integration.
- Used Atomics from Atomic Red Team to test and validate detections.

## Steps
1) Configure customer ticketing system by managing workflow diagram to respond to alerts. <img width="906" height="574" alt="Ticket Settings Workflow with Jira" src="https://github.com/user-attachments/assets/de7016b7-6ff2-4d9c-ac2f-ffed302b1d9b" /> <img width="1903" height="938" alt="Configure Ticket Settings with Jira" src="https://github.com/user-attachments/assets/beee0e2c-4800-4758-b92f-9db92850f8e7" />
2) Use Elastic agent to connect to endpoint for log analysis. <img width="1010" height="551" alt="Script Used to Connect Endpoint to Elastic for log analysis" src="https://github.com/user-attachments/assets/dedeffd1-5249-46b2-a7f4-9a36ff1d81f3" /> <img width="1912" height="958" alt="Used Elastic Agent to Connect to Endpoint for log analysis" src="https://github.com/user-attachments/assets/b59e1d70-351a-4338-a38d-6c84f15cc9ea" />
3) Use KQL to run Net User Discovery detection in Elastic. <img width="1038" height="542" alt="Using KQL to run custom detections in elastic_1" src="https://github.com/user-attachments/assets/a1ea85d0-fb0a-4621-a792-1dff65f18f56" /> <img width="1031" height="690" alt="Using KQL to run custom detections in elastic_2" src="https://github.com/user-attachments/assets/4774331d-5f51-482f-a0f2-9e5c8f150deb" /> <img width="1011" height="541" alt="Using KQL to run custom detections in elastic_3" src="https://github.com/user-attachments/assets/da652538-1bdd-4f53-9849-e2d8c7243147" /> <img width="991" height="652" alt="Using KQL to run custom detections in elastic_4" src="https://github.com/user-attachments/assets/ecbabe4b-d670-43c0-8b8b-8f97e82a5844" />
4) Link Net User Discovery detection in elastic to Jira API. <img width="1030" height="665" alt="Linking custom detections in elastic to Jira API" src="https://github.com/user-attachments/assets/9cb1adb3-3399-4800-810e-22f0498447c5" />
5) Test Net User Discovery detection with Atomic Red Team. <img width="847" height="628" alt="Testing Net User Discovery with Atomic Red Team_1" src="https://github.com/user-attachments/assets/54088de7-1e30-4fc8-b817-6a2e49eaadbb" /> <img width="966" height="630" alt="Testing Net User Discovery with Atomic Red Team_2" src="https://github.com/user-attachments/assets/717fced3-dd14-4433-b15d-ef5a7cfafb09" /> <img width="1537" height="553" alt="Testing Net User Discovery with Atomic Red Team_3" src="https://github.com/user-attachments/assets/ee86e7d9-779f-4a90-a524-147e0b341a33" />
6) Use EQL to run a scheduled task detection in elastic. <img width="752" height="856" alt="Using EQL to run a custom detection in elastic_1" src="https://github.com/user-attachments/assets/2cb0f5c4-a59a-45d2-bc11-90d735c204de" /> <img width="751" height="844" alt="Using EQL to run a custom detection in elastic_2" src="https://github.com/user-attachments/assets/bd3ab5f1-6117-4a1c-8c45-b6eba32e1a0c" /> <img width="1511" height="510" alt="Using EQL to run a custom detection in elastic_2 1" src="https://github.com/user-attachments/assets/0ecccb51-92bc-4fd5-89c6-bdf10a5b16fb" />

















