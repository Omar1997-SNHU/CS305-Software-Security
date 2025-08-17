**Artemis Financial – Secure Software Development READ ME**
**Project Summary**
An Artemis Financial organization designs proprietary software to handle private customer information and financial transactions.
The client desired secure programming-web application-without vulnerabilities and with data integrity. They wanted to make sure that,
by secure coding practices, their software had passed a vulnerability scan with no false positives. I was supposed to spot security
vulnerabilities in the existing code, fix them, and redesign the software to meet current security standards. This included putting
mitigation techniques in place and preparing and interpreting vulnerability analysis reports, plus multiple rounds of vulnerability
testing until all vulnerabilities had been removed.

**Software Security Process and Results**
One of this task's strengths was using the OWASP Dependency-Check tool to determine and remedy accurately the client's software 
security vulnerabilities. Working through the report methodically, I corrected the security vulnerabilities in code to ensure the
codebase and dependencies of the application followed a secure development practice. Secure coding-related activities ensure that
the business and the customers are not affected by security breaches, loss of money, or loss of name and fame. A quality software
security helps ensure business sustainability by blocking attacks and earning customer and authorities' trust.

**Challenges and Key Learnings**
The most difficult aspect of vulnerability scanning was making sense of warnings about dependencies as well as threats versus false
positives. As it enhanced my skill in assessing vulnerability severity, relevance, and exploitability, this was also one of the 
learning experiences that was most useful. By updating insecure dependencies, using TLS for secure communication, and checking inputs
to avoid injection attempts, I added more layers of protection. In the future, I would scan for vulnerabilities and choose which
techniques to apply for mitigation through automated tools like OWASP ZAP and Snyk in conjunction with Dependency-Check and manual
code review.


**Additional Layers of Security and Future Vulnerability Scanning**
I also improved the security of Artemis Financial with TLS encryption protecting data in transit, replacing and updating vulnerable
dependencies detected by the OWASP Dependency-Check tool, and restricting suppression rules to confirmed false positives in keeping
code intact. Doing so ensured the underlying libraries and communication channels of the application were guaranteed to meet today's
security standards. I still embarked on using OWASP Dependency-Check along with the various others such as OWASP ZAP for dynamic 
testing and SonarQube for static code analysis as well as the CVSS rating to rate severities of vulnerabilities. This would allow
me to rank various mitigation methods such as patch on time, update dependencies, or apply security settings in countering threats, 
and maintaining a strong security posture long term.

**Verification of Functionality and Secure Code**
After every change, I executed the application to make sure all important features continued to behave as expected and to ensure
that the code was secured. After refactoring, I ran Dependency Check to make sure new vulnerabilities were not introduced into the
application. In this project every fix has greatly improved the application without compromising its function due to this iterative
approach.

**Resources and Tools for Future Application**
The OWASP Dependency-Check Maven plugin, official guidelines for Java and Spring Security, and best practices for TLS set up were 
the top resources and tools for this project. Similarly, other guidelines for secure coding were secured, in particular, those of
dependency management and input validation. The application of these measures raises the security of future development similar to
when security is a priority instead of an afterthought.

**Portfolio Value**
This project demonstrates, in tangible terms, to future employers that I can perform well under time-pressured deadlines. It showcases
my commitment to secure coding standards and ability to compile results into a usable business report. This project also conveys my
technical ability to recognize security weaknesses, manage them in advance and provide a strong response which is appropriate for the
client.
