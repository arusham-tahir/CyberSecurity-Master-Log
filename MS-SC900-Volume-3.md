📖 Chapter 3 — Advanced Identity & Access Controls

🔹 1. Identification vs Authentication vs Authorization

📖 Definition

The sequential process of claiming an identity, proving that identity, and granting specific access rights based on verification.

🎯 Purpose

To safely manage a user's entire entry lifecycle into a secure digital system without mixing credentials and permissions.

🌍 Example

In a university portal:
1. Entering your registration number or username (Identification)
2. Scanning your fingerprint or typing your password (Authentication)
3. Getting access to view your semester grades after logging in (Authorization)

🎤 Interview Answer (20–30 sec)

Identification is simply claiming who you are, such as presenting a username. Authentication is the technical process of proving that claim using credentials like passwords or biometrics. Authorization happens last, determining exactly what resources or files that verified user is permitted to access.

⭐ Remember This

Claim Identity ➡️ Prove Identity ➡️ Grant Permissions

⚡ Quick Revision

Identification ➡️ "I am User_Alpha"
Authentication ➡️ "Here is my password/fingerprint"
Authorization ➡️ "Access granted to student dashboard"

________________________________________

🔹 2. Factors of Authentication

📖 Definition

The distinct categories of credentials used to verify a user's identity during the authentication phase.

🎯 Purpose

To implement robust security controls by requiring proofs from entirely different layers of verification.

🌍 Example

A secure military network requires a standard alphanumeric password (Something you know) AND a physical smart card (Something you have).

🎤 Interview Answer (20–30 sec)

Authentication factors are divided into three main categories: something you know, like passwords or PINs; something you have, like mobile devices or hardware tokens; and something you are, which refers to biological characteristics like fingerprints or facial recognition.

⭐ Remember This

Know + Have + Are = Unbreakable Authentication

⚡ Quick Revision

Something You Know ➡️ Passwords & PINs
Something You Have ➡️ Phones & Security Tokens
Something You Are ➡️ Fingerprints & Face ID

________________________________________

🔹 3. Principle of Least Privilege

📖 Definition

A foundational security rule stating that users and applications should only be granted the minimum permissions necessary to perform their specific tasks.

🎯 Purpose

To significantly minimize security risks and limit the damage if a user account is hacked or compromised.

🌍 Example

An enrollment officer can register new students on the portal but cannot change the university's central database configurations.

🎤 Interview Answer (20–30 sec)

The Principle of Least Privilege ensures that individuals or systems have only the exact access required to complete their job roles. This prevents accidental data leaks and strictly limits lateral movement inside a network during a cyber breach.

⭐ Remember This

Minimum Access = Maximum Security

⚡ Quick Revision

Limits user permissions
Prevents unauthorized changes
Reduces internal threat surface

________________________________________

🔹 4. Identity Provider (IdP) & Directory Service

📖 Definition

A system service that securely creates, stores, and manages digital identities while handles their authentication across multiple platforms.

🎯 Purpose

To centralize identity management so organizations do not have to create separate user profiles for every internal application.

🌍 Example

Microsoft Entra ID acts as an IdP, storing employee data and authenticating them for Microsoft 365, Teams, and third-party tools.

🎤 Interview Answer (20–30 sec)

An Identity Provider, or IdP, is a trusted service that creates and manages digital identities. It handles authentication for users, allowing them to access various cloud platforms securely, often utilizing a central Directory Service to map user permissions.

⭐ Remember This

IdP = Central Security Gatekeeper

⚡ Quick Revision

Stores user data
Handles authentications
Examples: Microsoft Entra ID, Google Identity, Okta

________________________________________

🔹 5. Privileged Identity Management (PIM)

📖 Definition

A specialized cloud security service that provides temporary, just-in-time administrative access to sensitive resources.

🎯 Purpose

To eliminate permanent administrator accounts, which are highly targeted by hackers.

🌍 Example

An IT support technician needs admin rights to fix a server, requests access via PIM, and gets admin permissions for exactly one hour.

🎤 Interview Answer (20–30 sec)

Privileged Identity Management, or PIM, allows organizations to manage and monitor access to critical cloud resources. It enforces 'Just-In-Time' access, giving users elevated administrative rights only when needed and automatically revoking them afterwards.

⭐ Remember This

Just-In-Time Admin Access

⚡ Quick Revision

Temporary permissions
Full audit logs generated
Reduces malicious credential abuse

________________________________________

🔹 6. Identity Governance

📖 Definition

The overarching system policies and automated processes that audit, manage, and review user access lifecycles within an organization.

🎯 Purpose

To ensure compliance by verifying that the right people have the right access to resources at the right time.

🌍 Example

When a cyber analyst resigns or leaves a company, Identity Governance systems automatically trigger to revoke all their access accounts instantly.

🎤 Interview Answer (20–30 sec)

Identity Governance ensures operational compliance by managing user access from entry to exit. It automates user onboarding, access reviews, and offboarding, ensuring that permissions do not accumulate over time, a risk known as privilege creep.

⭐ Remember This

Right Access ➡️ Right Person ➡️ Right Time

⚡ Quick Revision

Manages full identity lifecycle
Automates user offboarding
Ensures regulatory compliance

________________________________________

🚀 Chapter 3 — 5 Minute Rapid Revision

✅ Identification ➡️ Claiming an identity (Username).

✅ Authentication ➡️ Proving your identity (Credentials).

✅ Authorization ➡️ Evaluating permissions (Access Rights).

✅ Authentication Factors ➡️ Something you Know, Have, or Are.

✅ Least Privilege ➡️ Granting minimum necessary access.

✅ Identity Provider (IdP) ➡️ System that stores and authenticates users.

✅ PIM ➡️ Temporary, Just-In-Time administrative permissions.

✅ Identity Governance ➡️ Automating and auditing user lifecycles.


