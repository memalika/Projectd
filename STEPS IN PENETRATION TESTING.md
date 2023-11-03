
                   #STEPS OF PENTESTING (ETHICAL HACKING)

>An ethical hacker’s goal is to analyze the security posture of a network’s or system’s infrastructure in an effort to identify and possibly exploit any security weaknesses found and then determine if a compromise is possible. This process is called security penetration testing or ethical hacking.

           #1.1 Threat Actors
Before you can understand how an ethical hacker or penetration tester can mimic a threat actor (or malicious attacker), you need to understand the different types of threat actors. The following are the most common types of malicious attackers we see today. Select each for more information.

                a)Organized Crime
>Several years ago, the cybercrime industry took over the number-one spot, previously held by the drug trade, for the most profitable illegal industry. As you can imagine, it has attracted a new type of cybercriminal. Just as it did back in the days of Prohibition, organized crime goes where the money is. Organized crime consists of very well-funded and motivated groups that will typically use any and all of the latest attack techniques. Whether that is ransomware or data theft, if it can be monetized, organized crime will use it.


                    b)Hacktivists
>This type of threat actor is not motivated by money. Hacktivists are looking to make a point or to further their beliefs, using cybercrime as their method of attack. These types of attacks are often carried out by stealing sensitive data and then revealing it to the public for the purpose of embarrassing or financially affecting a target.

                c)State-Sponsored Attackers
>Cyber war and cyber espionage are two terms that fit into this category. Many governments around the world today use cyber attacks to steal information from their opponents and cause disruption. Many believe that the next Pearl Harbor will occur in cyberspace. That’s one of the reasons the United States declared cyberspace to be one of the operational domains that U.S. forces would be trained to defend.

                 d)Insider Threats 
>An insider threat is a threat that comes from inside an organization. The motivations of these types of actors are normally different from those of many of the other common threat actors. Insider threats are often normal employees who are tricked into divulging sensitive information or mistakenly clicking on links that allow attackers to gain access to their computers. However, they could also be malicious insiders who are possibly motivated by revenge or money.   

         #DIFFERENT TYPES OF PENTESTING
* Network Infrastructure Tests

   Testing of the network infrastructure can mean a few things. For the purposes of this course, we say it is focused on evaluating the security posture of the actual network infrastructure and how it is able to help defend against attacks. This often includes the switches, routers, firewalls, and supporting resources, such as authentication, authorization, and accounting (AAA) servers and IPSs. A penetration test on wireless infrastructure may sometimes be included in the scope of a network infrastructure test. However, additional types of tests beyond a wired network assessment would be performed. For instance, a wireless security tester would attempt to break into a network via the wireless network either by bypassing security mechanisms or breaking the cryptographic methods used to secure the traffic. Testing the wireless infrastructure helps an organization to determine weaknesses in the wireless deployment as well as the exposure. It often includes a detailed heat map of the signal disbursement.

* Application-Based Tests

  This type of pen testing focuses on testing for security weaknesses in enterprise applications. These weaknesses can include but are not limited to misconfigurations, input validation issues, injection issues, and logic flaws. Because a web application is typically built on a web server with a back-end database, the testing scope normally includes the database as well. However, it focuses on gaining access to that supporting database through the web application compromise. A great resource that we mention a number of times in this book is the Open Web Application Security Project (OWASP).
 
* Pentesting in the cloud

   When performing penetration testing in the cloud, you must understand what you can do and what you cannot do. Most CSPs have detailed guidelines on how to perform security assessments and penetration testing in the cloud. Regardless, there are many potential threats when organizations move to a cloud model. For example, although your data is in the cloud, it must reside in a physical location somewhere. Your cloud provider should agree in writing to provide the level of security required for your customers.

                **BLACK-BOX WHITE-BOX GRAY-BOX **

  When talking about penetration testing methods, you are likely to hear the terms unknown-environment (previously known as black-box), known-environment (previously known as white-box), and partially known environment (previously known as gray-box) testing. These terms are used to describe the perspective from which the testing is performed, as well as the amount of information that is provided to the tester.

            #DIFFERENT STANDARDS AND METHODOLOGIES
  
* The MITRE ATT&CK framework (https://attack.mitre.org) is an amazing resource for learning about an adversary’s tactics, techniques, and procedures (TTPs). Both offensive security professionals (penetration testers, red teamers, bug hunters, and so on) and incident responders and threat hunting teams use the MITRE ATT&CK framework today. The MITRE ATT&CK framework is a collection of different matrices of tactics, techniques, and subtechniques. These matrices–including the Enterprise ATT&CK Matrix, Network, Cloud, ICS, and Mobile–list the tactics and techniques that adversaries use while preparing for an attack, including gathering of information (open-source intelligence [OSINT], technical and people weakness identification, and more) as well as different exploitation and post-exploitation techniques.

* The OWASP Web Security Testing Guide (WSTG) is a comprehensive guide focused on web application testing. It is a compilation of many years of work by OWASP members. OWASP WSTG covers the high-level phases of web application security testing and digs deeper into the testing methods used. For instance, it goes as far as providing attack vectors for testing cross-site scripting (XSS), XML external entity (XXE) attacks, cross-site request forgery (CSRF), and SQL injection attacks; as well as how to prevent and mitigate these attacks. You will learn more about these attacks in Module 6, “Exploiting Application-Based Vulnerabilities.” From a web application security testing perspective, OWASP WSTG is the most detailed and comprehensive guide available. You can find the OWASP WSTG and related project information at https://owasp.org/www-project-web-security-testing-guide/.

* Special Publication (SP) 800-115 is a document created by the National Institute of Standards and Technology (NIST), which is part of the U.S. Department of Commerce. NIST SP 800-115 provides organizations with guidelines on planning and conducting information security testing. It superseded the previous standard document, SP 800-42. SP 800-115 is considered an industry standard for penetration testing guidance and is called out in many other industry standards and documents. You can access NIST SP 800-115 at https://csrc.nist.gov/publications/detail/sp/800-115/final.

* The Open Source Security Testing Methodology Manual (OSSTMM), developed by Pete Herzog, has been around a long time. Distributed by the Institute for Security and Open Methodologies (ISECOM), the OSSTMM is a document that lays out repeatable and consistent security testing (https://www.isecom.org). It is currently in version 3, and version 4 is in draft status. The OSSTMM has the following key sections:

   a)Operational Security Metrics

   b)Trust Analysis

   c)Work Flow

   d)Human Security Testing

   e)Physical Security Testing

   f)Wireless Security Testing

   g)Telecommunications Security Testing

   h)Data Networks Security Testing

   i)Compliance Regulations

   j)Reporting with the Security Test Audit Report (STAR)

* The Penetration Testing Execution Standard (PTES) (http://www.pentest-standard.org) provides information about types of attacks and methods, and it provides information on the latest tools available to accomplish the testing methods outlined. PTES involves seven distinct phases:

  1.Pre-engagement interactions

  2.Intelligence gathering

  3.Threat modeling

  4.Vulnerability analysis

  5.Exploitation
    
  6.Post-exploitation

  7.Reporting


* The Information Systems Security Assessment Framework (ISSAF) is another penetration testing methodology similar to the others on this list with some additional phases. ISSAF covers the following phases:

  1.Information gathering
   
  2.Network mapping

  3.Vulnerability identification

  4.Penetration

  5.Gaining access and privilege escalation

  6.Enumerating further

  7.Compromising remote users/sites

  8.Maintaining access

  9.Covering the tracks
     
                      #STEPS
    

    * Pre-engagement : This is surely the phase that many novices will neglect/forget, wrongly, because it is during this phase that we will define the scope of the test and the methods that will be used for it.

    * Reconnaissance : Collecting as much publically accessible informations about the target as possible.

    * Enumeration/Scanning : Discover the applications and services running on the systems, scan the ports (it's time for nmap).

    * Exploitation : Exploit vulnerabilities discovered on a system or application either via public exploits or via exploitation of the application/system logic.

    * Privilege Escalation : Once you have successfully exploited a system or application, a foothold in the jargon, you need to extend your access to the system. We talk about horizontal and vertical escalation, horizontal escalation corresponds to a transition to another user with the same permissions, vertical escalation corresponds to access to admin permissions.

    * Post-exploitation : This phase is broken down into several sub-steps:

        a)Full privilege collection : Additional information with a high-privileged user.

        b)Pivoting : Check of other potential targets.

        c)Clean-up : Erase the traces of your intrusion.

    * Reporting : Report harvesters, the flaws that have been discovered, the methods used, the paths, the tools, the commands, or any other relevant information that can be used in the last phase.

        Remediation : Fixing and proposing solutions for all vulnerabilities that were identified during the reporting phase.

