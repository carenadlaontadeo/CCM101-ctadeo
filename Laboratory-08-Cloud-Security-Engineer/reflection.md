# Mission Reflection

Completing this cloud security laboratory helped me understand why protecting a server is important even when its applications are working properly. A host-based firewall adds another layer of protection directly on the server. Even if the physical network perimeter is breached, the firewall can still block unauthorized incoming connections based on its configured rules.

Managing open network ports is also important because every active port may provide an entry point for attackers. By allowing only the ports required by the application, administrators can reduce the server's attack surface. In this activity, I allowed SSH for remote administration and TCP port 8080 for the Nginx web application while setting incoming traffic to be denied by default.

Leaving a database port such as MySQL's port 3306 open to the public internet is dangerous because unauthorized users may attempt to access the database, guess credentials, or exploit vulnerabilities. If successful, an attacker could expose, modify, or delete sensitive information. Database access should instead be restricted to trusted application servers and authorized administrators.

This mission changed my perspective on how easily a server can become vulnerable when security settings are ignored. Before this activity, I focused more on making an application run successfully. I now understand that deployment must also include checking open ports, setting firewall rules, and verifying which connections are allowed. Even a small configuration mistake can create a security risk.

Having eight completed missions in my GitHub Cloud Computing portfolio gives me a clearer record of the skills I have practiced. The activities helped me build experience in Linux commands, Docker, cloud deployment, monitoring, and security documentation. I can use this portfolio to demonstrate my learning progress and identify areas where I still need to improve.
