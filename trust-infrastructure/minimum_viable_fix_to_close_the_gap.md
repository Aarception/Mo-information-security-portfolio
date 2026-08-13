# Universal Candidate Experience Improvement 

***1. Concern***: I hold the CompTIA Security+ SY0-701 certification which cost $500 in exam expenditure, and is mandatory for DoD-adjacent and/or contracted information security roles. Yet, there is often no way to represent the certification in the application interface layer.
| Field                           | Type  |
| -----------------|-------------- | 
| Name                | Security+   |
| Issuer          | CompTIA   | 
| Expiration Date | 01/26/2029 | 


***2. Problem Statement***: Professional certifications and credentials represent a distinct category of applicant qualification that is currently unrepresented. Creating an option would make this representation available to the applicant, alongside education and experience.


***3. Suggestion***: What if there was consideration for adding a **Certifications (or Certifications and Credentials)** section to employment application interfaces, positioned thus:

- ***Education***
- ***Certifications***
  - **Name**
  - **Issuer**
  - **Expiration Date** — if applicable

- ***Experience.***

***4. Specification***: For each credential, at minimum, allow for the voluntary submission of the following 3 fields:

~~~
  Certifications 
├── Credential Name [free text, optional]
├── Issuing Organization [free text, optional]  
└── Expiration Date [date picker, optional]
~~~
***It would be text input. No classification. No drop down.***

***5. Structural Benefit***: Employment-relevant credentials should have a clear point of representation within the employment application through which the applicant seeks consideration. This is a small product improvement that respects the independence of the hiring decision itself.

***6. Privacy***: There is no determination of value or recognition accorded to any particular certification or credential. No changes to hiring qualifications or evaluation standards. No employment outcome is guaranteed by the presence of a credential.

***7. Implementation***: The initial implementation can remain deliberately simple:

**Certifications (or Certifications and Credentials)**


[________________________] **Name**


[________________________] **Issuer**


[________________________] **Expiration Date (if applicable)**

Applicants may add multiple credentials.

***8. Recommendation***: This should be treated as a **forward-looking information architecture improvement** for **universal candidate experience improvement**, that has no bearing on hiring policy.

