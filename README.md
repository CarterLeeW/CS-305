# CS-305

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?
 \nThe client was a global banking/finance service that required secure transactions and file transfers. They specifically wished for us to perform encryption and checksum verification for their file transfers.
  
What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?
  When performing manual review of the code, I was able to catch vulnerabilities such as revealing paths or using root access for the server by default. Coding securely from the beginning will stop issues from unearthing later in the SDLC. This will result in cost saving and will prevent trust issues or legal action in the result of a breach.
  
What part of the vulnerability assessment was challenging or helpful to you?
  The challenging part for me was looking up the mitigation techniques for each vulnerability as well as suppressing false positives.
  
How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?
  I increased layers of security by adding RSA encryption to the file transfer system. the OWASP vulnerability check works very well for open-source libraries and can be used each time you commit code to check if you introduced additional vulnerabilities to the code.
  
How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?
  I ran another OWASP dependency check to be sure I did not add any vulnerabilities to the code. I also performed code review on my own code.
  
What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?
  I learned how to use the OWASP dependency check, and to put secure coding at the front of the development process.
  
Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?
  I would show the employer my vulnerability report and my code review to show that I put security first when coding.
