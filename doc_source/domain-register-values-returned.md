# Values that Amazon Route 53 Returns When You Register a Domain<a name="domain-register-values-returned"></a>

When you register your domain with Amazon Route 53, Amazon Route 53 returns the following values in addition to the values that you specified\. 

**Registered on**  
The date on which the domain was originally registered with Amazon Route 53\.

**Expires on**  
The date and time on which the current registration period expires, in Greenwich Mean Time \(GMT\)\.  
The registration period is typically one year, although the registries for some top\-level domains \(TLDs\) have longer registration periods\. For the registration and renewal period for your TLD, see [Domains That You Can Register with Amazon Route 53](registrar-tld-list.md)\.  
For most TLDs, you can extend the registration period by up to ten years\. For more information, see [Extending the Registration Period for a Domain](domain-extend.md)\.

**Domain name status code**  
The current status of the domain\.  
ICANN, the organization that maintains a central database of domain names, has developed a set of domain name status codes \(also known as EPP status codes\) that tell you the status of a variety of operations on a domain name, for example, registering a domain name, transferring a domain name to another registrar, renewing the registration for a domain name, and so on\. All registrars use this same set of status codes\.  
For a current list of domain name status codes and an explanation of what each code means, go to the [ICANN website](https://www.icann.org/) and search for **epp status codes**\. \(Search on the ICANN website; web searches sometimes return an old version of the document\.\)

**Transfer lock**  
Whether the domain is locked to reduce the possibility of someone transferring your domain to another registrar without your permission\. If the domain is locked, the value of **Transfer Lock** is **Enabled**\. If the domain is not locked, the value is **Disabled**\.

**Auto renew**  
Whether Amazon Route 53 will automatically renew the registration for this domain shortly before the expiration date\.

**Authorization code**  
The code that is required if you want to transfer registration of this domain to another registrar\. An authorization code is only generated when you request it\. For information about transferring a domain to another registrar, see [Transferring a Domain from Amazon Route 53 to Another Registrar](domain-transfer-from-route-53.md)\.

**Name servers**  
The Amazon Route 53 servers that respond to DNS queries for this domain\. We recommend that you don't delete Amazon Route 53 name servers\.   
For information about adding, changing, or deleting name servers, see [Adding or Changing Name Servers and Glue Records for a Domain](domain-name-servers-glue-records.md)\.