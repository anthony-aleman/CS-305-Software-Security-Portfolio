# CS-305-Software-Security-Portfolio


The client Artemis Financial is looking to implement secure communication systems for the RESTful web application giving a guarantee to their international clients that their data is secure.

Doing a manual review of the code base for software vulnerabilities, I identified multiple security risks including hardcoded credentials that were written in the comments of the source code, foregoing SQL parameterization, identified necessary updates needed for dependencies, and lack of validation input from users. I also documented the exact location of the source code that should be refactored to improve security. Overall these security risks needed to be upgraded to have a communication system fortified against cyber attacks from both inside actors and external ones. Effective software security measures reduce the risk of cyber-attacks and data breaches. This risk management is crucial for maintaining the operational integrity of a company's digital infrastructure.

Many industries are subject to strict regulatory requirements regarding data security and privacy (like GDPR, HIPAA, and PCI-DSS) in the financial sector. Software security helps companies meet these legal obligations, avoiding fines and legal repercussions.

Overall one of the increasingly important concerns consumers have online is data protection and security. A company that demonstrates a commitment to software security can earn and retain customer trust, which is vital for long-term business relationships

What was challenging was the setup through Maven to conduct the static testing. While it did not take long for me to understand the structure of the pom.xml file. I only have a shallow understanding of Java and Eclipse is not my preferred IDE but for the assignment I was able to adapt.

The refactored fix was not implemented in this assignment but had I had the chance to implement an actual fix I would need to change the database credentials to ensure it is properly safe, update dependencies to use their newest versions as well as follow any other edge cases as lined out in the static testing section, and finally utilizing parameterized SQL queries to avoid using a hardcoded string for accessing the database.


