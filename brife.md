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

