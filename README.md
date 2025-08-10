Getting Started with eMASS 🛡️

Disclaimer: eMASS (Enterprise Mission Assurance Support Service) is a DoD system used for managing RMF packages and system accreditations. Access requires authorization — there’s no legal public sandbox. This guide is for understanding the workflow and practicing with publicly available RMF tools.

⸻

1. What is eMASS? 📄
	•	Web-based DoD application that supports RMF Step 1–6 for system authorization.
	•	Used to document security controls, manage POA&Ms, track risk, and process ATO packages.
	•	Interfaces with NIST standards, DoD policies, and FedRAMP controls for cloud systems.

⸻

2. Core eMASS Workflow 🔄
	1.	Create / Access System Package – AO or ISSM creates the package in eMASS.
	2.	Populate System Details – Pull info from your System Security Plan (SSP).
	3.	Implement Controls – Mark as implemented, inherited, or not applicable.
	4.	Upload Artifacts – Attach evidence (STIG checklists, vulnerability scans, policies).
	5.	Conduct Self-Assessment – Run internal validation.
	6.	Submit for Validation – Send to Validator/SCA for review.
	7.	ATO Decision – AO grants ATO, IATT, or denies authorization.
	8.	Continuous Monitoring – Keep vulnerabilities, POA&Ms, and control statuses current.

⸻

3. How to Get Familiar Without Live eMASS Access 🧩

Since real eMASS is on SIPR/NIPR, you can:
	•	Simulate the process with RMF Knowledge Service (rmfks.osd.mil – CAC required).
	•	Practice with NIST 800-53 Rev 5 controls using spreadsheets or a GRC tool like OpenRMF (github.com/CMSC-OpenRMF).
	•	Use DISA STIG Viewer (disa.mil) to work through STIG checklists.
	•	Download free NIST RMF templates (SSP, POA&M, Continuous Monitoring Plan) from nist.gov.

⸻

4. Learning Resources 📚
	•	DAU Online (Free) –
	•	CS130 – RMF for DoD IT Fundamentals
	•	CS150 – RMF Practitioner
	•	DISA’s eMASS User Guide – (Requires DoD access)
	•	BAI RMF Resource Center – Paid RMF/eMASS training with mock exercises (rmf.org)
	•	NIST 800-37 & 800-53 Rev 5 – Core docs behind eMASS workflows
	•	YouTube – Search RMF eMASS demo for safe, non-classified walkthroughs

⸻

5. Example Practice Scenario 🛠️

Try a mock ATO build:
	•	Pick a fictional system (e.g., “Shipboard Communications Node”)
	•	Fill out a fake SSP using NIST controls
	•	Map DISA STIG checklist results to those controls
	•	Create a mock POA&M in Excel
	•	“Submit” to a peer acting as the SCA for review
