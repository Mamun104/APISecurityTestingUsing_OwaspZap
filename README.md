# APISecurityTestingUsing_OwaspZap

## Technology and Tool Used

- Postman
- Owasp Zap
- Json-Server


## Prerequisites

- You must have installed to your system
- Postman
- Owasp Zap
- Json-Server

## Scenario of this project

- The user can create a post
- The user can single and multiple post by post id
- The user can get all post
- The user can update single post
- The user can update multiple post
- The user can delete a post

## API Documents


            https://documenter.getpostman.com/view/16548351/2s93eVWYqH 
            

## How to run this project

- clone this project
- Import the collection in postman or necessary tool

## How to connect the postman with zap 

- Open the postman
- Go to postman file option 
- click the setting option and add Add a custom proxy configuration
- Set the proxy server and it should be similar as zap local proxy server

## How to check zap local proxy server

- Open the zap
- Click the tools menu then click the options
- Then click the local proxy and check the local proxy address


## Introducing ZAP

Zed Attack Proxy (ZAP) is a free, open-source penetration testing tool being maintained under the umbrella of the Open Web Application Security Project (OWASP).
ZAP is designed specifically for testing web applications and is both flexible and extensible. At its core, ZAP is what is known as a “man-in-the-middle proxy.”
It stands between the tester’s browser and the web application so that it can intercept and inspect messages sent between browser and web application, 
modify the contents if needed, and then forward those packets on to the destination. 
It can be used as a stand-alone application, and as a daemon process. If there is another network proxy already in use, as in many corporate environments, ZAP can be configured to connect to that proxy.
ZAP provides functionality for a range of skill levels – from developers, to testers new to security testing, to security testing specialists. 
ZAP has versions for each major OS and Docker, so you are not tied to a single OS. Additional functionality is freely available from a variety of add-ons in the ZAP Marketplace, accessible from within the ZAP client.
Because ZAP is open-source, the source code can be examined to see exactly how the functionality is implemented. Anyone can volunteer to work on ZAP, f
ix bugs, add features, create pull requests to pull fixes into the project, and author add-ons to support specialized situations.


![z1](https://github.com/Mamun104/APISecurityTestingUsing_OwaspZap/assets/78067017/47f491aa-e6c6-4c4f-ad9f-79be16c79692)


## Security Testing Basics

Software security testing is the process of assessing and testing a system to discover security risks and vulnerabilities of the system and its data.
There is no universal terminology but for our purposes, we define assessments as the analysis and discovery of vulnerabilities without attempting to actually exploit those vulnerabilities.
We define testing as the discovery and attempted exploitation of vulnerabilities.

Security testing is often broken out, somewhat arbitrarily, according to either the type of vulnerability being tested or the type of testing being done. A common breakout is:

Vulnerability Assessment – The system is scanned and analyzed for security issues.
Penetration Testing – The system undergoes analysis and attack from simulated malicious attackers.
Runtime Testing – The system undergoes analysis and security testing from an end-user.
Code Review – The system code undergoes a detailed review and analysis looking specifically for security vulnerabilities.
Note that risk assessment, which is commonly listed as part of security testing, is not included in this list. 
That is because a risk assessment is not actually a test but rather the analysis of the perceived severity of different risks (software security, personnel security,
hardware security, etc.) and any mitigation steps for those risks.



![z2](https://github.com/Mamun104/APISecurityTestingUsing_OwaspZap/assets/78067017/fc48a5e7-2780-4337-92be-9748a4a04f33)


## Output:

![Screenshot_11](https://github.com/Mamun104/APISecurityTestingUsing_OwaspZap/assets/78067017/042da636-20c7-4fd5-b81d-74dd8cba1080)


![Screenshot_2](https://github.com/Mamun104/APISecurityTestingUsing_OwaspZap/assets/78067017/578cd28f-f805-4e78-8525-c94c51d2e27b)


![Screenshot_3](https://github.com/Mamun104/APISecurityTestingUsing_OwaspZap/assets/78067017/fe222352-859b-4608-b83a-f11d4279dd8c)

![Screenshot_4](https://github.com/Mamun104/APISecurityTestingUsing_OwaspZap/assets/78067017/d8b72b9b-e530-49e8-9e4a-d18c67d947af)




