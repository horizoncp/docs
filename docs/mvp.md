# Scope for MVP (Minimum Viable Product)

The MVP should include **essential features** to manage a web server without needing direct SSH access.

🔑 **Core Features (High Priority)**

✅ **User & Access Management**

- Role-based access (Admin, Reseller, User)
- Authentication (2FA, Password Reset)

✅ **Web Hosting Management**

- Domain & subdomain management
- Virtual Hosts (Apache/Nginx)
- SSL certificate integration (Let's Encrypt)

✅ **Database Management**

- MySQL/MariaDB database creation & management
- User management for databases

✅ **DNS Management**

- A, CNAME, MX, TXT record management
- Custom nameservers

✅ **Security & Monitoring**

- Firewall management (UFW/CSF integration)
- System resource monitoring (CPU, RAM, Disk)
- Logs & event history

✅ **Backup & Restore**

- Scheduled and manual backups
- One-click restore option

✅ **File Management**

- Web-based file manager
- FTP & SFTP support

✅ **Basic API & CLI Support**

- REST API for automation
- CLI for power users

🚀 **Future Features (Beyond MVP)**

🔹 One-click app installations (WordPress, Nextcloud, etc.)  
🔹 Docker & Kubernetes support  
🔹 Advanced email hosting (Postfix, Dovecot)  
🔹 More integrations (Cloudflare, WHMCS)  
🔹 Reseller & billing system

🚫 **Out of Scope (For Now)**

To **stay focused**, we'll exclude **complex or enterprise-only** features for the first release:  
❌ **Windows support** (focus on Linux)  
❌ **Multi-server cluster management**  
❌ **Built-in load balancing**
