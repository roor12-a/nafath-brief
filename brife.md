Version:  NAFATH-V1
Track: Softwaer 

## overview 
software engineering are deeply interconnected within the software supply chain.Requirements lay the foundation, defining what needs to be built.Development translates these requirements into code. Continuous Integration and Delivery (CI/CD) automates the building and merging of code. Testing ensures the code meets quality standards and functions correctly. Deployment releases the verified software to end-users.Finally, Maintenance and Monitoring ensure the software remains secure and operational post-release. A vulnerability in any single field can compromise the entire lifecycle, making an integrated security approach essential for protecting software, AI models, and internet routes.

## Softwaer
The system shall be implemented using a microservices architecture, with the exception of isolation components. Application Programming Interfaces (APIs) must be exposed via an API Gateway, incorporating rate limiting.
## Mobile 
Sensitive data should be stored in secure, system-managed areas (such as Keychain on iOS or Keystore on Android). Screen capturing (including screen recording) must be prevented while sensitive data is being displayed. Code obfuscation should be implemented to hinder reverse engineering, and application integrity checks—such as detecting if a device is rooted or jailbroken—must be performed to prevent the app from running on such devices.
##  AI
Artificial intelligence is used to analyze behavioral biometrics and monitor user activity for suspicious attempts. Models must be trained on data and governed in their decision-making capabilities. Furthermore, these systems must be explainable—minimizing the risk of erroneously rejecting legitimate users—with human oversight provided for cases that require it
Resource: OWASP Mobile Application Security Testing Guide - https://owasp.org/ www-project-mobile-app-security/

## Network 
All communications must be enforced using TLS 1.3 with strong encryption (AES-256-GCM).Mutual TLS (mTLS) for server and client identity verification must be implemented. Legacy protocols (e.g., SSLv3 1.0/1.1, TLS) must be blocked. Firewalls (WAFs) must be used to protect APIs from DDoS and injection attacks.
Resource: NIST SP 800-52 Rev. 2-Guidelines for TLS - https://csrc.nist.gov/ publications/detail/sp/800-52/rev-2/final
## Date
 principle of data minimization must be applied, so that only what is necessary for verification is collected. Data must be encrypted during transit and at rest. Compliance with the Saudi Personal Data Protection Law (PDPL) is required, and the user's right to access or delete their data must be guaranteed

