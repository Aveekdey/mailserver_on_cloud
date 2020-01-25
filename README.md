# mailserver_on_cloud
<html>

<body>
<p>
WORKING OF A MAIL SERVER:
o	When we send an email, our computer connects to our email service’s mail server. A server is a centralized computer which manages a specific type of service. An email server for instance, handles emails. The email server responsible for sending emails is called the SMTP (Simple Mail Transfer Protocol) server. One SMTP server can pass on the mail to another SMTP server and relay it to the destination through several hops.
o	Every email has the sender’s address (e.g. sender@sendermail.com) and the recipient’s in the To field (e.g. recipient@recipientmail.com). When an email is sent, the email client connects to the SMTP server of the sender’s email service (e.g. mailserver.sendermail.com). The client transmits the address of the sender, the address of the recipient and the content of the message.
•	The SMTP server goes to work at locating the whereabouts of the recipient. Using the recipient’s mail ID (i.e. recipient@recipientmail.com) it locates the domain name – e.g.recipientmail.com.
•	Note:  If the recipient’s mail ID had the same domain name as the sender, then the process would be simpler. The SMTP server would have transferred the mail to its local outgoing mail server (POP3 or IMAP).
•	Each domain name represents a unique Web address, called an Internet protocol (IP) address. Think of it as postal addresses of the internet. The link between domain names to their IP addresses is stored in the Domain Name Registry. The SMTP server then contacts the server where the registry is kept (The DNS Server). The DNS server sends back the address to the SMTP server.
•	The SMTP server then proceeds to hand over the email to the SMTP server of the recipient’s email service (let’s call it mailserver.recipientmail.com). This SMTP server checks and confirms that the mail addressed to recipient@recipientmail.com belongs to it and hands it over to its counterpart – the POP3 server (or the IMAP server).
•	Post Office Protocol (POP3) servers are the servers that do the job of receiving mails. The number “˜3′ is the version number of the protocol in use. POP3 servers have mail accounts (our email IDs). Each mail account is mapped to a username-password combination. Once the message is handed over to the POP3 server, it is kept and stored in the mail account till the recipient logs in and checks the mail.
•	An email client connects to the POP3 server and tells it to allow download of the email. Once downloaded to the local machine, POP3 mailboxes do not retain a copy of the email. Thus, you cannot check your emails from another PC as it has already been downloaded. To nail this difficulty, IMAP was introduced. IMAP4 (Internet Message Access Protocol version 4) simply retains a copy of the emails on the server. This allows you to access your e-mail from any location with an internet connection.

AWS  AMAZON: 
Amazon Web Services is a subsidiary of Amazon that provides on-demand cloud computing platforms to individuals, companies and governments, on a metered pay-as-you-go basis. 
AMAZON WORKMAIL: 
Amazon WorkMail is a secure, managed business email and calendar service with support for existing desktop and mobile email client applications. Amazon WorkMail gives users the ability to seamlessly access their email, contacts, and calendars using the client application of their choice, including Microsoft Outlook, native iOS and Android email applications, any client application supporting the IMAP protocol, or directly through a web browser. You can integrate Amazon WorkMail with your existing corporate directory, use email journaling to meet compliance requirements, and control both the keys that encrypt your data and the location in which your data is stored. You can also set up interoperability with Microsoft Exchange Server, and programmatically manage users, groups, and resources using the Amazon WorkMail SDK.

BENEFITS:

1.MANAGED  SERVICE
2.ANYWHERE ACCESS
3.LOW COST
4.ENTERPRISE-GRADE SECURITY
5.OUTLOOK COMPATIBILITY

AMAZON WORKMAIL SYSTEM REQUIREMENT:
Amazon WorkMail works with all major mobile devices and operating systems that support the Exchange ActiveSync protocol. These include the iPad, iPhone, Amazon Fire, Android, Windows Phone, and BlackBerry 10. Users of macOS can add their Amazon WorkMail account to their Mail, Calendar, and Contacts apps.
You can access Amazon WorkMail from Microsoft Outlook. You must have a valid Microsoft Outlook license to use it with Amazon WorkMail, which offers native support for the following versions:
•	Outlook 2007, Outlook 2010, Outlook 2013, Outlook 2016, and Outlook 2019
•	Outlook 2010 and Outlook 2013 Click-to-Run
•	Outlook for Mac 2011, Outlook 2016 for Mac, and Outlook 2019 for Mac
Amazon WorkMail supports IMAP clients. For the required configuration, see Connect to your IMAP Client Application. POP3 clients are not currently supported.
You can access Amazon WorkMail using the web application: https://alias.awsapps.com/mail.
AMAZON WORKMAIL CONCEPTS:
Amazon WorkMail works with all major mobile devices and operating systems that support the Exchange ActiveSync protocol. These include the iPad, iPhone, Amazon Fire, Android, Windows Phone, and BlackBerry 10. Users of macOS can add their Amazon WorkMail account to their Mail, Calendar, and Contacts apps.
You can access Amazon WorkMail from Microsoft Outlook. You must have a valid Microsoft Outlook license to use it with Amazon WorkMail, which offers native support for the following versions:
•	Outlook 2007, Outlook 2010, Outlook 2013, Outlook 2016, and Outlook 2019
•	Outlook 2010 and Outlook 2013 Click-to-Run
•	Outlook for Mac 2011, Outlook 2016 for Mac, and Outlook 2019 for Mac
Amazon WorkMail supports IMAP clients. For the required configuration, see Connect to your IMAP Client Application. POP3 clients are not currently supported.
AMAZON WORKMAIL RESOURCES:
The following related resources can help you as you work with this service.
•	Classes & Workshops – Links to role-based and specialty courses as well as self-paced labs to help sharpen your AWS skills and gain practical experience.
•	AWS Developer Tools – Links to developer tools, SDKs, IDE toolkits, and command line tools for developing and managing AWS applications.
•	AWS Whitepapers – Links to a comprehensive list of technical AWS whitepapers, covering topics such as architecture, security, and economics and authored by AWS Solutions Architects or other technical experts.
•	AWS Support Center – The hub for creating and managing your AWS Support cases. Also includes links to other helpful resources, such as forums, technical FAQs, service health status, and AWS Trusted Advisor.
•	AWS Support – The primary web page for information about AWS Support, a one-on-one, fast-response support channel to help you build and run applications in the cloud.
•	Contact Us – A central contact point for inquiries concerning AWS billing, account, events, abuse, and other issues.
•	AWS Site Terms – Detailed information about our copyright and trademark; your account, license, and site access; and other topics.



</p>
</body>

</html>
