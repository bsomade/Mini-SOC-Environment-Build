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
2) Use Elastic agent to connect to Endpoint for log analysis. <img width="1010" height="551" alt="Script Used to Connect Endpoint to Elastic for log analysis" src="https://github.com/user-attachments/assets/dedeffd1-5249-46b2-a7f4-9a36ff1d81f3" /> <img width="1912" height="958" alt="Used Elastic Agent to Connect to Endpoint for log analysis" src="https://github.com/user-attachments/assets/b59e1d70-351a-4338-a38d-6c84f15cc9ea" />
3) Use KQL to run custom detections in Elastic. <img width="1038" height="542" alt="Using KQL to run custom detections in elastic_1" src="https://github.com/user-attachments/assets/a1ea85d0-fb0a-4621-a792-1dff65f18f56" /> <img width="1031" height="690" alt="Using KQL to run custom detections in elastic_2" src="https://github.com/user-attachments/assets/4774331d-5f51-482f-a0f2-9e5c8f150deb" /> <img width="1011" height="541" alt="Using KQL to run custom detections in elastic_3" src="https://github.com/user-attachments/assets/da652538-1bdd-4f53-9849-e2d8c7243147" /> <img width="991" height="652" alt="Using KQL to run custom detections in elastic_4" src="https://github.com/user-attachments/assets/ecbabe4b-d670-43c0-8b8b-8f97e82a5844" />







