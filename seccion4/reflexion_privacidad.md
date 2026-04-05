What is asymmetric encryption (public/private key) and how does it work in the context of GPG?

Asymmetric encryption, also known as public-key cryptography, uses a pair of keys: a public key and a private key.
The public key is shared openly, while the private key is kept secret. 

In the context of GPG (GNU Privacy Guard), this system is used to securely exchange information.
When someone wants to send a secure message, they encrypt it using the recipient’s public key.
Only the recipient can decrypt it using their private key.

Additionally, GPG allows users to digitally sign messages using their private key.
Others can verify this signature using the sender’s public key, ensuring authenticity and integrity.


 What is the difference between encrypting a message and digitally signing it?

Encrypting a message ensures confidentiality.
The content becomes unreadable to anyone except the intended recipient.

Digitally signing a message ensures authentication and integrity.
It proves who sent the message and that it has not been altered,
but the content remains readable unless it is also encrypted.

b.Compare ProtonMail, Gmail, and Outlook in terms of:
 (a) encryption at rest, (b) encryption in transit, (c)
 end-to-end encryption, (d) privacy policies and provider access to data,
 and (e) legal jurisdiction.

ProtonMail provides high security and privacy. 
Emails are encrypted both at rest and in transit, and its “zero-access”
 architecture prevents even the provider from reading messages. 
End-to-end encryption is enabled by default, so only the sender and
 recipient can access the content. 
ProtonMail operates under Swiss law, offering strong privacy protections
 (Mailbird, 2026; Proton, n.d.).

Gmail also encrypts emails at rest and in transit, but Google
 can access and process content since end-to-end encryption is not available. 
Privacy is lower, and user data is primarily subject to U.S.
 and Irish laws (Mailbird, 2026; Google Privacy & Terms, n.d.).

Outlook encrypts emails at rest and in transit, but Microsoft
 can access content and does not provide end-to-end encryption. 
Privacy is limited, and data access requires a valid legal process
 reviewed under applicable laws (Mailbird, 2026; Microsoft, n.d.).




 
c. What is the PKI model based on Certificate Authorities (CA), and mention 2 advantages and 2 disadvantages compared to the Web of Trust?

The PKI model based on Certificate Authorities (CA) relies on a trusted entity
that verifies identities and issues digital certificates linking users to their public keys.

The Web of Trust (WoT) is a decentralized model where users validate and sign each other's keys,
building trust through a network of relationships.

Advantages of Web of Trust:
- Decentralization: no single point of failure.
- User control: individuals decide whom to trust.

Disadvantages of Web of Trust:
- Difficult for new users to gain trust.
- Requires significant user effort (manual verification, key-signing).


d. GDPR vs Ecuador Personal Data Protection Law (comparison)
Scope / Alcance:

GDPR: Applies to any organization processing EU citizens’ data, even if
 outside the EU.

Ecuador: Applies to public and private entities handling personal
 data in Ecuador.

Rights related to email & digital monitoring / Derechos sobre correo y
 vigilancia digital:

GDPR: Access, rectification, erasure, objection, portability, 
restriction, information, automated decision-making rights.

Ecuador: Access, decide who can receive data,
 authorize collection, protection against unauthorized processing.



Consent requirements / Requisitos de consentimiento:

GDPR: Freely given, informed, specific, revocable;
 under 13 requires parental consent.

Ecuador: Collection and processing require owner’s authorization;
 trust and informed consent emphasized.



Data security obligations / Obligaciones de seguridad:

GDPR: Technical and organizational measures
 (encryption, access control, 2FA, staff training), report breaches in 72h.

Ecuador: Technological and organizational measures; compliance monitored
 by Dinarp.



Enforcement & penalties / Cumplimiento y sanciones:

GDPR: Fines up to €20M or 4% of global revenue; individuals can claim
 compensation.

Ecuador: Dinarp can apply corrective measures;
 strict compliance required, no fixed fines.



Transparency / Transparencia:

GDPR: Clearly explain data processing purposes,
 legal basis, and individual rights.

Ecuador: Inform owners about purpose, use, and sharing of data,
 ensuring legality and proportionality.



e. What is email metadata and what are the privacy implications?

Email metadata is the technical information of a message, including sender,
recipient, date, time, IP address, and the servers used to transmit it.

Encryption protects only the content of the message, not the metadata,
because metadata is necessary for routing the email.

This has privacy implications, since metadata can reveal communication patterns,
relationships, location, and user behavior, enabling profiling or surveillance
without accessing the message content.

Reflection
This project allowed our group to gain hands-on experience with advanced
 Linux security tools, including LUKS, LVM, GPG, and Hashcat. Working
 together, we strengthened our understanding of encryption, password
 management, and system integrity. Collaborating on installations,
 calculations, and Git commits emphasized teamwork and the importance of
 documenting each step meticulously. Overall, the experience highlighted
 both the technical and cooperative skills required for secure system
 administration.

