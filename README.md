# CS-305
# Briefly summarize your client, Artemis Financial, and their software requirements. Who was the client? What issue did they want you to address?

Artemis Financial wanted us to upgrade their software application and make it more secure by adding data verification and ensure secure communications. They wanted this done in the form of a checksum verification, which would utilize 
encryption via an algorthim cypher.

# What did you do very well when you found your client’s software security vulnerabilities? Why is it important to code securely? What value does software security add to a company’s overall wellbeing?

Utilizing a dependency check helps us in learning about vulnerabilities in the current code as it stands. With this we can work to refactor the code whether it be upgrading depencies to the newest version or handling vulnerabilities more carefully. 
By doing this we can ensure that our software is resistant to hacker attacks that can expose customers sensitive information and in turn lose trust between the clients and their users.

# What part of the vulnerability assessment was challenging or helpful to you?

Creating a false positive suppresion was hard to do in the beginning because it can be time consuming going through each vulnerability and getting the code to suppress that result. Its a necessary task however 
since this can save time in the long run when it comes to debugging to focus on the vulnerabilities that actually require attention.

# How did you increase layers of security? In the future, what would you use to assess vulnerabilities and decide which mitigation techniques to use?

One thing we did is create an HTTPS connection to the server by utilizing a java keytool to create a self signed certificate to ensure a secure conection. This also adds some validiation to the website so customers 
get assurance that the website they are visiting is secure. Addionally using Vulnerability Assessment process flow diagram can help in ensuring the rest of the code is utlizing proper techiques to prevent additional vulnerabilties such as input validation

# How did you make certain the code and software application were functional and secure? After refactoring the code, how did you check to see whether you introduced new vulnerabilities?

Running the code and checking the output is one way to ensure we had created the intended result, when it came to the code we made sure we had a secure https connection and made sure we had an unencrypted message and the encyrpted message appear to ensure we achieved
the desired result. Going through the code again we make sure we hadnle any new functinalities properly by introducing techniques such as error validation, encryption, etc. to make the software resistant to attacks.

# What resources, tools, or coding practices did you use that might be helpful in future assignments or tasks?

I think learning about how to create HTTPS connections was an important tool, eseciallly as I try to learn thing like HTML, and CSS its important to learn not only how to create webpages that are easy to navigate 
but secure so other people dont try to take advantage of unsecure connections and vulnerabilities.

# Employers sometimes ask for examples of work that you have successfully completed to show your skills, knowledge, and experience. What might you show future employers from this assignment?

I think knowing how to create a secure server connection is important and having employers know that I keep cyber security in mind when I program future code will be important. Knowing that 
secure code is not just being aware of how to find vulnerabilities but how to mitigate and prevent them from occuring.
