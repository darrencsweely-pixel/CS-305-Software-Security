# CS 305 Portfolio Artifact

## Artemis Financial Practices for Secure Software Report

For this course, I chose my Artemis Financial Practices for Secure Software Report as my portfolio artifact. This project gave me experience identifying software security concerns, refactoring an application to improve security, and testing the application afterward to make sure it remained functional.

### Client and Software Requirements

Artemis Financial was a financial consulting company that wanted to improve the security of its software application. Because the company works with sensitive financial information, it needed to make sure that data was protected and that communications between the application and its users were secure. My job was to review the existing application, identify security concerns, and make changes that improved the security of the software.

### Software Security and Vulnerabilities

I think I did well at looking at security from more than one direction instead of focusing on only the source code. I reviewed the code manually and also used OWASP Dependency-Check to identify vulnerabilities associated with the project's dependencies. This showed me that an application can have security problems even when the code I write works correctly because third-party libraries can introduce their own vulnerabilities.

Secure coding is important because a vulnerability can expose sensitive information or allow an attacker to use an application in a way that was never intended. For a company like Artemis Financial, software security also helps protect its customers, reputation, and business operations. Building security into the application is much better than waiting until a vulnerability is exploited.

### Challenges and What I Learned

One of the more challenging parts of the vulnerability assessment was interpreting the Dependency-Check results. The tool can identify a large number of vulnerabilities, but the results still have to be reviewed instead of assuming every finding should be treated the same way. This was also one of the most helpful parts of the project because I learned more about the difference between finding vulnerabilities and deciding what actually needs to be fixed.

### Increasing Layers of Security

I increased the application's security by using SHA-256 to create a checksum, generating a certificate, and configuring the application to communicate over HTTPS. These changes added protection for data integrity and secure communications instead of relying on only one security measure.

In the future, I would continue using tools such as OWASP Dependency-Check along with manual code review and vulnerability databases to assess an application. I would prioritize critical and high-severity vulnerabilities first while also considering how the vulnerable component is actually being used in the application. The mitigation technique should match the vulnerability instead of applying the same solution to every finding.

### Functional and Security Testing

After refactoring the application, I ran it again to make sure it still functioned correctly. I verified that the application started successfully over HTTPS on port 8443 and tested the hash endpoint in the browser. I also verified that the SHA-256 checksum was consistent when the same data was processed again.

I ran OWASP Dependency-Check after the changes to determine whether the refactoring introduced additional dependency vulnerabilities. This was important because fixing one security problem should not create another one somewhere else in the application.

### Resources, Tools, and Coding Practices

Some of the most useful resources and tools from this course were Eclipse, Maven, Java's MessageDigest class, Java keytool, HTTPS and SSL configuration, and OWASP Dependency-Check. I also found that combining automated testing with manual code review was useful. Automated tools can identify issues that would be difficult to find manually, while reviewing the code myself helped me understand why an issue mattered and how it could affect the application.

These are practices I can use again in future programming assignments because security should be considered throughout development instead of only after an application is finished.

### What I Can Show Future Employers

I would show future employers the completed Practices for Secure Software Report because it demonstrates more than just my ability to write Java code. It shows that I can review an existing application, identify security concerns, implement security improvements, configure HTTPS, use hashing for integrity verification, work with certificates, and perform security testing after making changes. It also shows that I understand the importance of verifying that security changes do not interfere with the functionality of an application.
