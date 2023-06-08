# AWS Web Application Firewall (WAF)

Monitor HTTP(S) requests foward to CloudFront, Amazon API gateway API or LoadBalancer;

- Works on Layer 7 (application);
- Works agains SQL injection

AWS Web Application Firewall (AWS WAF) is a web application firewall that helps protect your web applications or APIs against common web exploits that may affect availability, compromise security, or consume excessive resources. AWS Web Application Firewall (AWS WAF) gives you control over how traffic reaches your applications by enabling you to create security rules that block common attack patterns such as SQL injection or cross-site scripting. You can also use rate-based rules to mitigate the Web layer DDoS attack.

WAF cannot be used to improve the performance of a static website.

How AWS Web Application Firewall (AWS WAF) Works:

![img](https://d1.awsstatic.com/products/WAF/product-page-diagram_AWS-WAF_How-it-Works@2x.452efa12b06cb5c87f07550286a771e20ca430b9.png)

An SQL injection attack works by exploiting any one of the known SQL vulnerabilities that allow the SQL server to run malicious code. For example, if a SQL server is vulnerable to an injection attack, it may be possible for an attacker to go to a website's search box and type in code that would force the site's SQL server to dump all of its stored usernames and passwords for the site.

Similar to an SQL injection attack, a cross-site scripting attack also involves injecting malicious code into a website, but in this case, the website itself is not being attacked. Instead, the malicious code the attacker has injected only runs in the user's browser when they visit the attacked website, and it goes after the visitor directly, not the website.

AWS Web Application Firewall (AWS WAF) is a web application firewall that helps protect web applications from attacks by allowing you to configure rules that allow, block, or monitor (count) web requests based on conditions that you define. These conditions include IP addresses, HTTP headers, HTTP body, URI strings, SQL injection, and cross-site scripting. You can use the IP address based match rule to block specific geographies. The accuracy of the IP Address to country lookup database varies by Region. Based on recent tests, AWS mentions that the overall accuracy for the IP address to country mapping is 99.8%.
