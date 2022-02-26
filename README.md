# CS-305
CS-305 Repository
Jeremy Leuck
README

Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial helps people plan financially, whether it is investing, saving or retirement. They want to be able to apply the latest software to increase their security and protect their API.


What did you do particularly well in identifying their software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

In particular I felt very confident in running the dependency checks to identify their issues. I am still learning how to write secure code, and advanced ways to protect data with new tactics, so I still need much improvement on that front. But I now understand how to identify issues in the security and what they mean, which I feel is a great skill to have.


What about the process of working through the vulnerability assessment did you find challenging or helpful?

The most help I found was with all of the provided programs that are out there. When there is an issue or vulnerability identified, you are provided with multiple links to proven sites on how to fix or move around the issue. The challenging part, as I mentioned above, was being able to write the code to protect it.


How did you approach the need to increase layers of security? What techniques or strategies would you use in the future to assess vulnerabilities and determine mitigation techniques?

The code I found most useful and easiest to understand was SHA-225. This is the technique of using Hash Code to encrypt and decrypt the data, with over 128-bit encryption. IT also provides an assymetric key, which means you need seperate keys to encrypt and decrypt, which helps provide even more security.


How did you ensure the code and software application were functional and secure? After refactoring code, how did you check to see whether you introduced new vulnerabilities?

All that was required was to run another dependency check. After using Maven and OWASP, I am able to identify which issues are there that need to be fixed, ans which ones are unable to be fixed at the moment. If that is the case then, like we learned, we need to supress the issues so that it is not a visible issue when running checks and tests.


What resources, tools, or coding practices did you employ that you might find helpful in future assignments or tasks?

As stated above, using Maven dependency checks, manual review, JUnit tests, and all provided links from Maven, you are able to identify and fix any problem that has a fix at that time. 


Employers sometimes ask for examples of work that you have successfully completed to demonstrate your skills, knowledge, and experience. What from this particular assignment might you want to showcase to a future employer?

My best example from this course was my ability to identify problems. Like stated before, I am still learning how to code and develop secure programs, but I am able to know identify these issues. I also am able to understand how to fix them, I just do not know as of right know how to write the code to fix it.
