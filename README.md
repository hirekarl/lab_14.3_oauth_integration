# Lab 14.3: OAuth Integration

[Karl Johnson](https://github.com/hirekarl)  
2025-RTT-30  
<time datetime="2025-08-29">2025-08-29</time>

## Assignment
This lab is a reading and reflection exercise. There is no coding involved. Your task is to carefully read the following article on real-world OAuth vulnerabilities and then answer the reflection questions in a written document.

### Task 1: Reading Assignment
Please read the following article from Doyensec’s blog. It provides a detailed overview of common OAuth flows and, more importantly, common attacks against those flows.

- [**Article**: Common OAuth Vulnerabilities ](https://blog.doyensec.com/2025/01/30/oauth-common-vulnerabilities.html)

Focus on understanding not just what the attacks are, but how they exploit misconfigurations or weaknesses in an OAuth implementation.

### Task 2: Written Reflection
After reading the article, answer the following questions in a clear and concise manner. Your total response should be between 300 and 500 words.

#### 1. CSRF and the `state` Parameter
In your own words, explain how an attacker could perform a Cross-Site Request Forgery (CSRF) attack on an OAuth flow. How does using the `state` parameter, as recommended, prevent this specific attack?
> TODO

#### 2. Redirect URI Attacks
The article mentions that validating a `redirect_uri` by simply checking the domain or allowing subdomains is a common mistake. Describe a hypothetical scenario where a “leaky” `redirect_uri` validation (e.g., one that allows any path on a valid domain) could be exploited to steal an authorization code.
> TODO

#### 3. User Experience vs. Security
Adding a third-party login option like “Login with Google” is a significant user experience improvement. However, it also introduces complexity and new potential security risks. Based on the article and your own thoughts, describe one key trade-off a development team must consider when deciding to implement OAuth. (For example, think about the balance between convenience for the user and the responsibility of the application to protect user data).
> TODO
