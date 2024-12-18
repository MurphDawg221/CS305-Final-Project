Artemis Financial is a consulting company that develops individualized financial plans for its customers. The financial plans include savings, retirement, investments, and insurance.
Artemis Financial wants to modernize its operations. As a crucial part of the success of its custom software, the company also wants to use the latest and most effective software security. 
Artemis Financial has a RESTful web application programming interface (API).The company is seeking Global Rain’s expertise about how to protect the organization from external threats.
Upon my assessment of the files in the software I had noticed some out dated verisions are being used for the dependency checks being done on the program. I also noticed missing certifacates to help 
provide better security to the system and a serious lack of input validation. These few things are very important. Utilizing the latest verisions of any plug in softwares will help make sure you are 
keeping the system protected from threats and fix bugs that may have been found or patched. In this case the dependency check version was out dated so I had to update that to see the most current of potential 
vulnerabilities. Certificates help provide verifaction of the identity of a server application assuring users are communicating with the intended entity and not a milicious imposter. This helps prevent data interception
cerificates are a good way for Artemis Financial to establish trust with there clients and show integrity in the system. The program also had a lack of input validation which isn't good if by any case the user can inject harmful 
code to manipulate data. Input validation helps because it ensures the program only expects valid responses when users interact and rejects anything else. Last main thing missing in the program that is important 
especially since Artemis Financial has an obligation to its clients to pretect their sensitive data, is encryption. The program had no encryption which is a good way to protect data and make it
unreadable to all not who do not possess a decryption key. Encrypting data with the latest and best encryption algorithms is good to ensure that is attackers do get ahold of the data
they can not understand it anyways. Software security will save this company from well potential lawsuits and help it's clients by assuring their data remains secure and 
they do not fall victim to indentity theft. This is beneficial for both and establishes trust between Artemis financial and it's clients. When Identifying vulnerabilities I found it hard to 
honestly indentify what is an actual vulnerability and what is a false positive regarding the dependency report. I increased layers of security by assuring there was input validation, 
the program utilizes ABAC as a form of access control, adding encryption, generating certificates, updating dependencies to review and patch or look into potential vulnerabilities, and ran tests to see if it works.
I decided to go through and find false positives and suppress them that way I can assess the vulnerabilities with the greatest hazards and then read into the vulnerabilities with the highest threat level. 
This will help look into updates for the future to potentially resolve these vulnerabilities. I used Checksum to verify it works and performed a series of static tests as well. I 
also clicked on the webpage to verify my certifactes as well that I generated. The dependency check tool was very useful throughout my assessment. In addition, the CVE and NVD
vulnerability report databases are paramount resources for mitigation of known vulnerabilities. Effectively using these tools and repositories is important for any software developer. 
Reference material such as O’Reilly textbooks that remind me of best practices and common vulnerabilities were extremely helpful when performing this assessment. Lastly, the OWASP 
and SANS top vulnerabilities lists are great for keeping common security issues in mind.In this class, I have learned much about developing secure software. This vulnerability 
assessment exemplifies my knowledge in external security threats, data integrity, data confidentiality, and the seven main security topics that web APIs must be competent in.This 
project shows that I can manually review a Java codebase and explain the vulnerabilities I found with complex security concepts. It also shows that I can use static application 
security testing tools to find known vulnerabilities in dependencies. Finally, it shows that I can devise an action plan to mitigate both the local and dependency-related vulnerabilities.
