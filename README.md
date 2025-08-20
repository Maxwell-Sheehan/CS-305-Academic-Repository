# CS-305-Academic-Repository

Briefly summarize your client, Artemis Financial, and its software requirements. Who was the client? What issue did the company want you to address? In this assignment Artemis Financial was a global financial group trying to modernize it's security in software to meet financial regulatory means. These were the largest issues in the assignment, creating secure code that meets regulatory compliance. 


What did you do well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall well-being? I think something I did well when finding vulnerabilites was assessing the risk of the vulnerabilites. This is a big part of creating secure code, we only have so much time and resources, so choosing to prioritize what matters most is crucial. The value of secure software is almost incalcuable in the modern world as its so important, the entire company could become worthless without secure software especially for financial institutions. If the company was known for being unsecure, or didn't meet security standards it wouldn't be allowed to operate. 


Which part of the vulnerability assessment was challenging or helpful to you? I think assessing false positives was more difficult, I don't have the wealth of experience needed to easily sort these, so put simply when trying to determine these your mostly just going off of first impressions. If googling the issue does not immedietly raise flags,  I isolated it and moved to the next.


How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use? To increase security we added SHA-256 and more complicated ciphers to the internal code. Adding the layer of security of removing plain text data in the code was pivotal, in the future to mitigate further risk you'd want to probably dig deeper into the companys data base and make sure the data at rest in otehr clients and servers is just as secure. 


How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities? To make sure the code was secure we had tests through maven and spring boot to ensure the test casses passed. With maven after refactoring hte code we could also run dependency checks, which showed the vulnerabilites present in the code giving us a better idea of how much we were reducing / or increasing vulnerability.


What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks? Luckily cyber security has alot of amazing resources, I have used coursera, hackthebox, and tryhackme before to become more familar with cyber security. For tools we used keystore, and the existing maven plugs within eclipse to make more secure safe code. I think the implementation of building and compiling with additional existing resources will help with future projects as I'm now familiar with additional tools.


Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment? I would show the work I did of creating the private and public keys for the individual John Smith while refacoring the code. He know has a certificate created. Also the creation of the dependency check and removing false positives and very minor risks I think would be good examples of security auditing professionally. 
