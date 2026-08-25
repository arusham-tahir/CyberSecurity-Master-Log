📖 Chapter 2 — Identity & Access Management

🔹 1. Identity

📖 Definition

An Identity is a digital representation of a user, device, or application that is used to verify who or what is requesting access.

🎯 Purpose

To uniquely identify users, devices, or applications before granting access to resources.

🌍 Example

When you sign in to your Microsoft account using your email address, that account is your digital identity.

🎤 Interview Answer (20–30 sec)

An identity is a digital representation of a user, device, or application. It allows systems to recognize who is requesting access and apply the appropriate security controls.

⭐ Remember This

Identity = Who are you?

⚡ Quick Revision

Represents a user, device, or app

Used before granting access

Foundation of authentication

🔹 2. Authentication

📖 Definition

Authentication is the process of verifying that a user or device is who they claim to be.

🎯 Purpose

To confirm identity before allowing access.

🌍 Example

Logging in with your email and password verifies your identity.

🎤 Interview Answer (20–30 sec)

Authentication verifies the identity of a user or device before access is granted. Common methods include passwords, biometrics, and security codes.

⭐ Remember This

Authentication = Prove your identity

⚡ Quick Revision

Verifies identity

Happens before authorization

Passwords, biometrics, OTP

🔹 3. Multi-Factor Authentication (MFA)

📖 Definition

MFA requires two or more verification methods to confirm a user's identity.

🎯 Purpose

To provide stronger security than using only a password.

🌍 Example

You enter your password and then approve a notification on your phone.

🎤 Interview Answer (20–30 sec)

Multi-Factor Authentication increases account security by requiring two or more verification methods, reducing the risk of unauthorized access even if a password is stolen.

⭐ Remember This

Two or More = MFA

⚡ Quick Revision

Password + OTP

Password + Fingerprint

Stronger than password alone

🔹 4. Passwordless Authentication

📖 Definition

Passwordless Authentication allows users to sign in without using a traditional password.

🎯 Purpose

To improve both security and user convenience.

🌍 Example

Signing in with Windows Hello using your fingerprint or face recognition.

🎤 Interview Answer (20–30 sec)

Passwordless authentication replaces passwords with secure methods such as biometrics, security keys, or authentication apps, helping reduce password-related attacks.

⭐ Remember This

No Password = Passwordless

⚡ Quick Revision

Uses biometrics or security keys

More secure

Better user experience

🔹 5. Authorization

📖 Definition

Authorization determines what actions or resources a verified user is allowed to access.

🎯 Purpose

To ensure users only access the resources they are permitted to use.

🌍 Example

A teacher can update students' marks, but students can only view their own results.

🎤 Interview Answer (20–30 sec)

Authorization determines what an authenticated user is allowed to access or perform based on assigned permissions.

⭐ Remember This

Authorization = What can you do?

⚡ Quick Revision

Happens after authentication

Controls permissions

Based on roles or policies

🔹 6. Microsoft Entra ID

📖 Definition

Microsoft Entra ID (formerly Azure Active Directory) is Microsoft's cloud-based identity and access management service.

🎯 Purpose

To manage user identities, authentication, and secure access to applications.

🌍 Example

A company uses Microsoft Entra ID so employees can securely sign in to Microsoft 365.

🎤 Interview Answer (20–30 sec)

Microsoft Entra ID is a cloud identity and access management solution that helps organizations manage users, authenticate identities, and secure access to applications.

⭐ Remember This

Entra ID = Identity Management

⚡ Quick Revision

Cloud identity service

Manages users

Supports SSO & MFA

🔹 7. Single Sign-On (SSO)

📖 Definition

Single Sign-On allows users to sign in once and access multiple applications without signing in again.

🎯 Purpose

To improve user convenience and reduce password management.

🌍 Example

After signing in to Microsoft 365, you can access Outlook, Teams, and OneDrive without entering your password again.

🎤 Interview Answer (20–30 sec)

Single Sign-On allows users to authenticate once and securely access multiple applications without repeatedly entering their credentials.

⭐ Remember This

One Login = Many Apps

⚡ Quick Revision

One sign-in

Multiple applications

Better user experience

🔹 8. Conditional Access

📖 Definition

Conditional Access applies security policies based on conditions such as user identity, device, location, or risk level.

🎯 Purpose

To allow or block access based on security requirements.

🌍 Example

A company blocks login attempts from unknown countries unless additional verification is completed.

🎤 Interview Answer (20–30 sec)

Conditional Access uses predefined policies to make access decisions based on factors like user identity, device health, location, and risk.

⭐ Remember This

Right Person + Right Device + Right Conditions

⚡ Quick Revision

Policy-based access

Uses risk evaluation

Can require MFA

🔹 9. Role-Based Access Control (RBAC)

📖 Definition


RBAC assigns permissions based on a user's role within an organization.

🎯 Purpose

To simplify permission management and enforce the principle of least privilege.

🌍 Example

The HR department can access employee records, while the IT department manages servers.

🎤 Interview Answer (20–30 sec)

Role-Based Access Control grants permissions according to a user's job role, ensuring users only have access to the resources they need.

⭐ Remember This

Role Decides Permission

⚡ Quick Revision

Permissions by role

Easier management

Supports least privilege

🔹 10. Identity Protection

📖 Definition

Identity Protection helps detect, monitor, and respond to suspicious sign-in activities and identity-related risks.

🎯 Purpose

To reduce the risk of compromised accounts.

🌍 Example

If someone tries to log in from another country, the system may require MFA or block the sign-in.

🎤 Interview Answer (20–30 sec)

Identity Protection identifies risky sign-in attempts and automatically applies security measures to protect user accounts.

⭐ Remember This

Detect → Protect → Respond

⚡ Quick Revision

Detects risky logins

Protects accounts

Works with Conditional Access

🚀 Chapter 2 — 5 Minute Rapid Revision

✅ Identity → Who are you?

✅ Authentication → Verify identity.

✅ MFA → Two or more verification methods.

✅ Passwordless → No password, use biometrics/security keys.

✅ Authorization → What are you allowed to do?

✅ Microsoft Entra ID → Cloud identity management.

✅ SSO → One login for multiple apps.

✅ Conditional Access → Policy-based access decisions.

✅ RBAC → Permissions based on role.

✅ Identity Protection → Detects and responds to risky sign-ins.
