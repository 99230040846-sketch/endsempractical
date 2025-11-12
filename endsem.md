# End Sem : Verification and integrity check of hash values through Autopsy

**Course / Lab:** Digital Forensics Lab  
**Title:**   Verification and integrity check of hash values through Autopsy

---

## Aim
To verify the hash values and integrity of 2 forensic images.

---

## Requirements
- Autopsy (latest version)  
- Windows / Linux / macOS operating system  
- Evidence images: 4Dell Latitude CPi.E01, 4Dell Latitude CPi.E02  

---

## Procedure

**Step-1:** Create a new case in Autopsy and add 4Dell Latitude CPi.E01 as base source.
![Step 1](2.png)

**Step-2:** Open terminal and get the hash value of 4Dell Latitude CPi.E02 using  [Get-FileHash "C:\Users\dharu\Downloads\4Dell Latitude CPi.E02" -Algorithm SHA256] command.
![Step 2](exp5/step1.jpg)

**Step-3:** Add the hash values and import as base hash lookup in ingest toolbox.
![Step 3](exp5/step3.jpg)

**Step-4:** Run hash lookup and verification ingest modules to get reported hash verification.
![Step 4](exp5/step10.jpg)

---

## Observation
Autopsy successfully verified and analyzed hash functions and integrity of the forensic images.

---

## Result
Forensic images can be classified as Admissible or inadmissible in court from hash verification report.

---

## Tools Used
- Software: Autopsy  
- Evidence: 4Dell Latitude CPi.E01, 4Dell Latitude CPi.E02  

---

## Conclusion
Autopsy provides a robust suite for digital forensic investigations, combining acquisition, modular analysis, and reporting in a user-friendly workflow.
It also provides for a way to Verify hash values and check integrity of 2 forensic images.

---




