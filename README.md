
# General Interview Questions

### Table of Contents


1. ### What is a Proxy Server?

   A proxy server acts as a gateway between you and the internet. It’s an intermediary server separating end users from the websites they browse. Proxy servers provide varying levels of functionality, security, and privacy depending on your use case, needs, or company policy.

   If you’re using a proxy server, internet traffic flows through the proxy server on its way to the address you requested. The request then comes back through that same proxy server (there are exceptions to this rule), and then the proxy server forwards the data received from the website to you.

   If that’s all it does, why bother with a proxy server? Why not just go straight from to the website and back?

   Modern proxy servers do much more than forwarding web requests, all in the name of data security and network performance. Proxy servers act as a firewall and web filter, provide shared network connections, and cache data to speed up common requests. A good proxy server keeps users and the internal network protected from the bad stuff that lives out in the wild internet. Lastly, proxy servers can provide a high level of privacy.


   ## How Does a Proxy Server Operate?
      Every computer on the internet needs to have a unique Internet Protocol (IP) Address. Think of this IP address as your computer’s street address. Just as the post office knows to deliver your mail to your street address, the internet knows how to send the correct data to the correct computer by the IP address.

   A proxy server is basically a computer on the internet with its own IP address that your computer knows. When you send a web request, your request goes to the proxy server first. The proxy server then makes your web request on your behalf, collects the response from the web server, and forwards you the web page data so you can see the page in your browser.

   When the proxy server forwards your web requests, it can make changes to the data you send and still get you the information that you expect to see. A proxy server can change your IP address, so the web server doesn’t know exactly where you are in the world. It can encrypt your data, so your data is unreadable in transit. And lastly, a proxy server can block access to certain web pages, based on IP address.

   ## Why Should You Use a Proxy Server?
      There are several reasons organizations and individuals use a proxy server.
   <details>
   <summary>To control internet usage of employees and children: . </summary> 
    Organizations and parents set up proxy servers to control and monitor how their employees or kids use the internet. Most organizations don’t want you looking at specific websites on company time, and they can configure the proxy server to deny access to specific sites, instead of redirecting you with a nice note asking you to refrain from looking at said sites on the company network. They can also monitor and log all web requests, so even though they might not block the site, they know how much time you spend cyberloafing.
   </details>
   
   <details>
   <summary>Bandwidth savings and improved speeds </summary> 
    Organizations can also get better overall network performance with a good proxy server. Proxy servers can cache (save a copy of the website locally) popular websites – so when you ask for www.varonis.com, the proxy server will check to see if it has the most recent copy of the site, and then send you the saved copy. What this means is that when hundreds of people hit www.varonis.com at the same time from the same proxy server, the proxy server only sends one request to varonis.com. This saves bandwidth for the company and improves the network performance.
   </details>

   <details>
   <summary>Privacy benefits </summary> 
    Individuals and organizations alike use proxy servers to browse the internet more privately. Some proxy servers will change the IP address and other identifying information the web request contains. This means the destination server doesn’t know who actually made the original request, which helps keeps your personal information and browsing habits more private
   </details>
   <details>
   <summary>Improved security </summary> 
    Proxy servers provide security benefits on top of the privacy benefits. You can configure your proxy server to encrypt your web requests to keep prying eyes from reading your transactions. You can also prevent known malware sites from any access through the proxy server. Additionally, organizations can couple their proxy server with a Virtual Private Network (VPN), so remote users always access the internet through the company proxy. A VPN is a direct connection to the company network that companies provide to external or remote users. By using a VPN, the company can control and verify that their users have access to the resources (email, internal data) they need, while also providing a secure connection for the user to protect the company data.
   </details>
   <details>
   <summary> Get access to blocked resources</summary> 
    Proxy servers allow users to circumvent content restrictions imposed by companies or governments. Is the local sportsball team’s game blacked out online? Log into a proxy server on the other side of the country and watch from there. The proxy server makes it look like you are in California, but you actually live in North Carolina. Several governments around the world closely monitor and restrict access to the internet, and proxy servers offer their citizens access to an uncensored internet.
   </details>
   <details>
   <summary> </summary> 
    
   </details>

### SOLID principle
https://www.digitalocean.com/community/conceptual_articles/s-o-l-i-d-the-first-five-principles-of-object-oriented-design
https://www.youtube.com/watch?v=ZUMQEkoF1_c

### Dependency Injection

 **[⬆ Back to Top](#table-of-contents)**
