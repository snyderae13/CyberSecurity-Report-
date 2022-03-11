# CyberSecurity-Report-

There has been an interesting discovery sent to Bleeping Computer from Security Jones, whose clients in the gambling and gaming industry had been victims of suspected ransomware attacks. The interesting thing about these attacks is that they have been using custom-made tools that are usually used by APT or advanced persistent threat group. In addition to these custom tools, they also take advantage of open-source tools such as modifying a version of Ligolo which is a reverse tunneling utility that’s available for pentesters on GitHub and a custom tool to dump credentials called LSASS. The way the attacked started was via a compromised employee SSL-VPN credentials, that was followed by admin scans and RDP (Remote Desktop Protocol) brute-force. The hackers were then able to harvest the credentials.  Once those credentials were harvested, they continued with accessing additional machines with high privileges, the deployment of a custom proxy tunneling for secure communication amongst themselves and finally a Cobalt Strike. This was the farthest that the hackers got to, but Security Joe believes that their next steps would have been to deploy a ransomware payload, as the methods that they used followed those of typical ransomware gangs. The use of Ligolo was done with meaningful additions that removed the need to use command-line parameters and included several execution checks to avoid running multiple instances. However, this type of customization is not common at all for hackers, apart from the Iranian state sponsored MuddyWater hacking group, who is the only known group to have modified it. Another interesting part of this case was the use of ‘LSASSDumper”, a custom tool used for the automatic exfiltration from the LSASS process to the “transer.sh” service. This LSASSDumper really shows how sophisticated this group was because it is the first time Security Joe has ever seen it in the wild. The Defense against a LSASS Dump is usually done by: decommissioning all end-of-life Windows operating systems, restricting local administrative access as much as possible, disabling WDigest on all windows systems prior to windows 8, and enabling widows defender credential guard. 



In 2022, Vodafone was victim to a source code theft after a cybercrime group claimed to have stolen hundreds of gigabytes of source code from the company which has caused country-wide service outages in Portugal and the disruption of 4/5G data networks, SMS texts, and even television. The attack has severely restricted data usage of the customers of Vodafone, along with many other companies under the Cofina Group, with 3G being the only network available. With over 4 million cell phone and another 3.4 million home and business internet customers, this cyber-attack has almost half of the population of Portugal.  The name of the cybercrime group, "Lapsus$", are claiming that they have stolen up to 200GB , or approximately 5,000 GitHub repositories. However, after Vodafone had made a brief investigation, they concluded that: " generally the types of repositories referenced in the claim contain proprietary source code and do not contain customer data". As of now, the hackers have not leaked any of the Vodafone source code. They have however asked thousands of their subscribers on Telegram in a poll if they should leak the proprietary code or not. This this case happened only a month ago, most of what has been compromised or not has not been disclosed by Vodafone to the media. Another prominent media group, Impresa, was also hit with ransomware in January of this year and their site is still currently offline. When ransomware attacks inflict serious damage on a company, many have to completely redesign in many cases, being that the locked systems are completely unrecoverable. 
