# cs-305-journal8
<ol>
<br><li>Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?</li>
<br>Artemis Financial is a consulting company that develops financial plans. They are wanting their software to be more modern and secure.
  
<br><li>What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?</li>
<br>To find the security vulnerabilities, I used the VAPF to identify areas of security that the application covered. This is important because our client needs a secure, safe application as they handle many sensitive data. It would ensure that their clients don't lose their trust in the organization and being trusthworthy only helps their brand. 

<br><li>What part of the vulnerability assessment was challenging or helpful to you?</li>
<br>This was not as challenging becuase I had the VAPF chart and could easily map out relevant areas of security.

<br><li>How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?</li>
<br>To increase the security in the application, I added a dependency checker to keep the dependencies up-to-date. This is important because it lessens the likilihood of vulnerabilities in the application due to out dated software. In the future, I would do the same, but also look for a service that automatically updates/patches new versions of dependencies.
  
<br><li>How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?</li>

<br>To make certain the application was secure, I did static testing by using the OWASP dependency checker. I found that a lot of the dependencies were false positives, but there was at least one that needed to have a new security patch. I made sure to make note of it in my report. I did not make any major changes to the code so no new vulnerabilities were introduced.

<br><li>What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?</li>
<br>I will definitely be using the OWASP dependency checker again because it was extremely useful. Especially the html report is generated of all the dependencies in the projcet.

<br><li>Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?</li>
<br>I would show my future employer that I understand security concerns and have a good understanding of static testing. I would also want to show them how I analyzed areas of security to determine what vulnerabilities the application might have.

</ol>
