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
