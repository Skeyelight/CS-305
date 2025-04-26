# CS-305

Q: Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address?

A: Artemis Financial is a financial consulting company. They offer individualized financial plans for the customers.   Artemis came to Global Rain requested assistance with modernizing their operations. They sought out Global Rain for our expertise in protecting data from external threats and upgrading their system’s security. 

Q: What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being?

A: I found success in analyzing the dependency checks and isolating the false positives from the true positives and suspending the false positive vulnerabilities. Coding securely and addressing any vulnerabilities helps protect sensitive data and can prevent malicious actors from intercepting transmissions between the client and the host. When dealing with data as important as financial records, keeping that information safe not only protects the customer, but also is required by many governing bodies. Offering secure services to your clients not only protects you from violating those laws but also can build trust with your clients, which encourages them to continue using your services.

Q: Which part of the vulnerability assessment was challenging or helpful to you?

A: Learning how to differentiate between true positive and false positive vulnerabilities was initially difficult for me to discern. Once I understood which resources provided the most useful information and how to best use those resources the process became much easier. Finding false positives went from being the most challenging aspect of vulnerability assessment to one that I felt very comfortable with.

Q: How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

A: I increased security for Artemis Financial by implementing a cipher algorithm, utilizing a hash function, and incorporating a trusted certificate so the system could utilize HTTPS, and transfer data with encryption. In the future, utilizing dependency checks to help find vulnerabilities will be one of the first steps I take in accessing the security of a system. To help mitigate security risks, I would research to find the best cipher algorithm the system I am working on, ensuring that the system has a trusted certificate, and utilizing a hash algorithm to reassure that the data has not been tampered with. 

Q: How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

A: Once the vulnerabilities were addressed, I utilized AES-256, a cipher algorithm, to protect the data, and SHA-256 to create a hash that can be monitored to watch for data manipulation. A trusted certificate was then put in place so the data being transferred would be encrypted. Once the security was verified, running a test of the software application to verify that the system still performed as expected. Once the software was working as expected, and the necessary security protocols are put in place, I ran another dependency check to verify that my refactored code did not introduce new vulnerabilities. 

Q: What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

A: The dependency checks were a very helpful tool for accessing the vulnerability of the applications. NIST was useful in confirming vulnerabilities and being able to quickly see if there were any patches available that may resolve the issue. A resource that I found when trying to better understand false positives was MVN Repository. This was an invaluable tool when helping to determine if a flagged vulnerability was a false positive.  

Q: Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

A: I would show a future employer my documentation of the dependencies, and the mitigation steps that should be taken to address the vulnerabilities. Having good, clear documentation can is a crucial tool in software development and even more so when dealing with security risks within a system. Not only can concise documentation help you with your own work but sharing it with the other teams could assist them. If a vulnerability was caused because of two different dependencies being used together, someone may find a solution by utilizing a different but comparable set of dependencies. That vulnerability would only be communicated if someone took the time  to create proper documentation. 



