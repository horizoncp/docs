# Roadmap

### `🚀 Phase 1: Plaanning & Foundation`

<br />

#### 1️⃣ Define Goals & Scope

| 🎯 Feature                                                                 | Status        |
| -------------------------------------------------------------------------- | ------------- |
| Identify essential features for **MVP (Minimum Viable Product)**           | ❌ Incomplete |
| Define the **target audience** (individual users, hosting companies, etc.) | ❌ Incomplete |
| Choose an **OS focus** (Ubuntu/Debian for compatibility)                   | ❌ Incomplete |
| Select **web server support** (Apache, Nginx, or both)                     | ❌ Incomplete |

<br />

| 🔍 Deliverables                                                        | Status        |
| ---------------------------------------------------------------------- | ------------- |
| Document core features for the first release                           | ❌ Incomplete |
| List future enhancements (Docker, Kubernetes, WHMCS integration, etc.) | ❌ Incomplete |
| Open GitHub repository with an initial README                          | ✅ Complete   |

<br />

#### 2️⃣ Tech Stack Selection & Environment Setup

| 💻 Backend                                             | Status        |
| ------------------------------------------------------ | ------------- |
| **Laravel (PHP)** - API and server-side logic          | ❌ Incomplete |
| **Shell Scripting (Bash)** - System commands execution | ❌ Incomplete |
| **Redis + Laravel Queues** - Async task processing     | ❌ Incomplete |
| **Supervisor** - Queue worker management               | ❌ Incomplete |

<br />

| 🖥 Frontend                                                 | Status        |
| ---------------------------------------------------------- | ------------- |
| **Vue.js + Inertia.js** - Reactive UI with Laravel backend | ❌ Incomplete |
| **Tailwind CSS** - Modern, clean styling                   | ❌ Incomplete |
| **Alpine.js (optional)** - Lightweight interactivity       | ❌ Incomplete |

<br />

| ☁ DevOps & Infrastructure                                 | Status        |
| --------------------------------------------------------- | ------------- |
| **Ubuntu/Debian Server** - Test environment               | ❌ Incomplete |
| **Docker (Optional)** - Containerized development         | ❌ Incomplete |
| **CI/CD Pipeline** - Github Actions for automated testing | ❌ Incomplete |

<br />

| 🔍 Deliverables                                                   | Status        |
| ----------------------------------------------------------------- | ------------- |
| 📌 Set up **development environment** (local + cloud test server) | ❌ Incomplete |
| 📌 Install & configure Laravel with Inertia.js                    | ❌ Incomplete |
| 📌 Set up **database schema** (users, roles, domains, services)   | ❌ Incomplete |

<br />

#### 3️⃣ System Architecture & UI/UX

| 🏗 System Architecture                                                      | Status        |
| -------------------------------------------------------------------------- | ------------- |
| Define **database schema** (Users, Domains, Services, DNS, Email, Backups) | ❌ Incomplete |
| Design **API structure** (REST or GraphQL)                                 | ❌ Incomplete |
| Identify system commands for **server management (Bash scripts)**          | ❌ Incomplete |

<br />

| 🎨 UI/UX Design                                                              | Status        |
| ---------------------------------------------------------------------------- | ------------- |
| **Dashboard wireframe** (User & Admin views)                                 | ❌ Incomplete |
| **Mockups for key pages** (User Management, Domain Settings, Service Status) | ❌ Incomplete |
| **Navigation & layout structure**                                            | ❌ Incomplete |

<br />

| 🔍 Deliverables                                       | Status        |
| ----------------------------------------------------- | ------------- |
| 📌 **Database schema diagram**                        | ❌ Incomplete |
| 📌 **Initial API endpoints** draft                    | ❌ Incomplete |
| 📌 **UI wireframes** for dashboard and major sections | ❌ Incomplete |

<br />

#### 4️⃣ Server Provisioning & Automation

| ⚙️ Server Management Core                                                      | Status        |
| ------------------------------------------------------------------------------ | ------------- |
| Implement **Bash scripts for system tasks** (creating users,managing services) | ❌ Incomplete |
| Create a **Laravel wrapper** for executing shell commands securely             | ❌ Incomplete |
| Implement **basic logging & error handling**                                   | ❌ Incomplete |

<br />

| 🔐 Security & Authentication                                                | Status        |
| --------------------------------------------------------------------------- | ------------- |
| Set up **Laravel Sanctum or Passport** for API authentication               | ❌ Incomplete |
| Implement **basic role-based access control (RBAC)**                        | ❌ Incomplete |
| Enable **server security basics** (fail2ban, firewall rules, SSH hardening) | ❌ Incomplete |

<br />

| 🔍 Deliverables                                          | Status        |
| -------------------------------------------------------- | ------------- |
| 📌 Working **authentication system**                     | ❌ Incomplete |
| 📌 First **API endpoints** (User login, role management) | ❌ Incomplete |
| 📌 Basic **server commands execution via Laravel**       | ❌ Incomplete |
