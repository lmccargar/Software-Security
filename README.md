# Software-Security
**Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?**

Artemis Financial is a money management service providing financial services to their customers. The company needed a way to ensure their customers information is secure with data encryption and decryption.

**What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?**

Working with the POM.xml setting up the Maven dependency checker and suppression xml is where I felt I did well. This is an important aspect of identifying false positives, as well as discoverying vulnerabilities with the different systems and supporting systems. In today's digital world, there is so much important information to secure from the want-to-be hackers up to state sponsered actors to contend with. Software security has become just as essential as the machines our code runs on. Using industry standards in security while developing mission critical applications for companies, governements is paramount. Everyone one of us needs to do our part with security. Meaning, the software development teams to the end user needs to play their part in providing secure digital systems. The end user needs to keep important user authentication/authorization from leaking outside the systems security archtecture. Developer need to keep up with known vulnerabilites in comtemporary times. The business units being part of the development process along with the developer and end users. This is a big part of ensuring the company's overall wellbeing.  

**What about the process of working through the vulnerability assessment did you find challenging or helpful?**

I discovered the vulnerability assessment was very helpful in planning for a development cycle. Here is where we can find vulnerabilities and make the apporiate plans to deal with the vulnerabilities. 

**How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?**

I would diffinetly use the vulnerability assessment process flow as part of the security layering process. I would follow processes layed out during this course with doing the vulneraility assessment and report. Keep up with the current trends when it comes to security in software development. 

**How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?**

While refactoring the code, the first step is to determine what vulnerabilies were false positives. Secondly, rerun the dependency check after suppressing the false positives. And then run a functional check of the listed vulnerabilities at the National Vulerability database (NVD).

**What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?**

The National Vulerability database (NVD) is an important resourse to have as part of development effort. Maven dependency checker is a very useful tool to use. Input validation is a good coding practice to use as well. Using the practice of least privileges with my coding. 

**Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?**

Conducting a vulerability assessment as learned through this course. The checksum coding using hash tables with chaining. And the vulnerability reporting processes too.
