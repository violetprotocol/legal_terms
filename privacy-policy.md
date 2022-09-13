Privacy Policy

Last updated: September 11, 2022

DeFi Labs GmbH (“DeFi Labs”) respects your right to privacy. This Privacy Policy explains who we are, how we collect, share, and use personal data about you and how you can exercise your privacy rights. This Privacy Policy only applies to personal data that we collect through our compliance and identity management tool “Violet,” which you are registering or have registered to use. When you register and use Violet, DeFi Labs acts as the data controller under the General Data Protection Regulation.

If you have any questions or concerns about our data protection practices after reading this Notice, then please contact us at: privacy@violet.co. Our physical address is: DeFi Labs GmbH, Torstraße 42, 10119 Berlin, Germany.

**What does Violet do?**

Violet is a highly customizable compliance and identity management tool provided by DeFi Labs. The purpose of Violet is to provide a standardized method to issue compliance credentials and map smart-contract access controls on the Ethereum mainnet as well as some EVM-compatible chains. Violet achieves this purpose in a way intended to fulfill traditional legal compliance requirements like Know Your Customer (KYC), Know Your Business Customer (KYBC), sanctions checks, and anti-money laundering (AML) rules in an on-chain verifiable way while preserving users’ privacy. The specific compliance checks that Violet supports are expected to grow over time and will be updated in this Notice. Before signing up with a new service or engaging in a transaction using a smart contract that requires a Violet credential, you should confirm your understanding of the checks that Violet will be required to perform by that entity or smart contract. 

By registering and receiving a Violet credential, Violet will provide these services, subject to the Terms of Service:

**Identity Management:** enrollment, authentication, and other self-service procedures for managing identity credentials on- and off-chain (forming the VioletID), which allow Violet to verify a user’s real-world identity.

**Compliance Management:** enrollment and ongoing backend procedures for managing compliance credentials (on- and off-chain) to ensure that VioletID holders fulfill the requirements of specific compliance regimes necessary to engage in permissioned transactions.

**Data Management:** encryption and storage of off-chain credentials – in particular, identity and compliance credentials – as well as pseudonymized audit log data.

**Credential Management:** issuing tokens and proofs – on- and off-chain – that allow other components or parties to verify compliance and identity information.

**Access Management:** providing a functional “Access Token” in the form of a signed message that is used to pass trusted compliance information from our off-chain system to on-chain smart contracts as part of your transaction. Access Tokens contain no direct personal information of the user, revealing only that the wallet address has successfully enrolled and authenticated vs. the compliance required by the relevant smart contract.

For more information about DeFi Labs or Violet, please see our documentation at: https://docs.violet.co/general-introduction/about-violet.   

**What personal data does Violet collect and why?**

**Registration**

Violet collects information about you during the registration process. The purpose for collecting information during the registration process is to authenticate your identity, generate your VioletID, and otherwise enroll you in Violet’s compliance and identity management service. Data collected during this process is stored in encrypted, off-chain storage – **which is accessible only by you, Violet, and our Partners in certain, limited circumstances clearly defined in this Policy** – or as part of a pseudonymized audit log.

Violet collects the following data at the registration stage:

**Stage 1**

Description: User connects their wallet and proves ownership by a digital signature

User Data Collected: Wallet address

Stored Personal Data: Wallet address

**Stage 2**

Description: User enrolls 2nd factor (SMS)

User Data Collected: Mobile phone number

Stored Personal Data: Mobile phone number

**Stage 3**

Description: User provides initial data and undergoes the Know Your Customer (KYC) or Know Your Business Customer (KYBC) process (third-party partner)

User Data Collected: Name, Date of birth, Location of birth, Nationality, ID card expiration, ID card issuer, ID card number, Mobile phone number, KYC/KYBC report, Face image (purged after enrollment), KYC/KYBC video file (purged after enrollment), IP address (purged after enrollment), User location (purged after enrollment), Operating System (purged after enrollment), Internet Service Provider (purged after enrollment), Device type (purged after enrollment), and Browser (purged after enrollment)

Stored Personal Data: Name, Date of birth, Nationality, Mobile phone number, ID card expiration, ID card issuer, ID card number, KYC Report, and VioletID

**Stage 4**

Description: Initial sanction list check (third party partner)

User Data Collected: Sanction list result

Stored Personal Data: Latest sanction list result


**Transaction Authorization**

Violet conducts a transaction authorization every time a user wants to perform a compliant, on-chain transaction that requires their Violet credential. The purpose of transaction-authorization-related data collection is to confirm that the entity engaged in the transaction is the same entity that was issued a Violet credential. Data collected during this process is stored in encrypted, off-chain storage – **which is accessible only by you, Violet, and our Partners in certain, limited circumstances clearly defined in this Policy** – or as part of a pseudonymized audit log.

Violet collects the following data at the transaction stage:

**Stage 1**

Description: User starts transaction authorization process and authenticates with SMS 2nd factor

User Data Collected: Transaction information, Wallet Address, SMS log data

Stored Personal Data: Pseudonymized transaction and credential log data

**Stage 2**

Description: Read and validate all user data and sanction list result

User Data Collected: No new data is collected

Stored Personal Data: Pseudonymized transaction and credential log data

**Stage 3**

Description: Create and handover the access token used by the smart contract to validate the transaction

User Data Collected: No new data is collected

Stored Personal Data: Pseudonymized transaction and credential log data

**Daily Sanctions List & AML Checks**

Violet conducts a daily sanctions list, and will soon conduct an AML check, of everyone holding a Violet credential. The purpose of daily-sanctions-related and AML data collection is to fulfill regulatory and contractual compliance requirements by confirming that holders of a Violet credential have not been added to a sanctions list or been identified as engaged in money laundering activities. Data collected during this process is stored in encrypted, off-chain storage – **which is accessible only by you, Violet, and our Partners in certain, limited circumstances clearly defined in this Policy** – or as part of a pseudonymized audit log.
  
Violet collects the following data while performing daily sanctions list and AML checks:

**Stage 1**

Description: Read encrypted user data

User Data Collected: No new data is collected

Stored Personal Data: Pseudonymized compliance check log data

**Stage 2**

Description: Sanction list check

User Data Collected: No new data is collected

Stored Personal Data: Pseudonymized compliance check log data

**Stage 3**

Description: Store sanction list and AML check

User Data Collected: Updated sanctions list and AML result

Stored Personal Data: Latest sanction list and AML result

**Login to the Self-Service Portal**

Violet provides a self-service portal for holders of a Violet credential who want to view their user data. The purpose of self-service-portal, login-related data collection is to confirm that the entity attempting to access a user’s data is the holder of the Violet credential. Data collected during this process is stored in encrypted, off-chain storage – **which is accessible only by you, Violet, and our Partners in certain, limited circumstances clearly defined in this Policy** – or as part of a pseudonymized audit log.

Violet collects the following data during the login process:

**Stage 1**

Description: User connects their wallet and proves ownership by a digital signature

User Data Collected: Wallet address

Stored Personal Data: N/A

**Stage 2**

Description: User authenticates with SMS 2nd factor

User Data Collected: Authentication log data

Stored Personal Data: Authentication log data

**Stage 3**

Description: Validate and create ID token for access to portal

User Data Collected: No new data is collected

Stored Personal Data: Pseudonymized login transaction log data

**Who does Violet share my personal data with?**

Violet uses Partners in issuing, authenticating, compliance checking, and storing a user’s credentials. Our Partners process your data under the limited instructions provided by Violet. Current Partners and their processing activities are listed below and will be updated in the event of future changes:

**Identity Management (currently: Persona):** processes your data during the KYC/KYBC registration process and performs an initial sanctions check. Partners do not retain your personal data after you complete the registration process.

**Compliance Management (currently: ComplyAdvantage):** processes your data during the daily sanctions check process and AML-related processing. Additional processing may occur in the future depending on the type of permissions required to use your Violet credential with a specific product, but any such additional processing will be disclosed to you in advance and, in some cases, will require your consent. Partners do not retain your data after completing the compliance screening processes.

**Data Management (currently: Privy, MongoDB):** stores your encrypted data – including certain information obtained during registration, authentication, and compliance screening – as well as pseudonymized data used for audit and compliance purposes. Partners are not permitted to access your encrypted data.

**Access Management (for SMS, currently: Tyntec, Twilio):** processes your mobile phone number for authentication purposes when a user is using SMS-based authentication. Partners have no access to any other information you provided to Violet.

**What is the legal basis for processing personal data?**

Violet generally processes your information when we need to do so to fulfill our contractual obligation with you (i.e., providing you with the Violet credential) or as required to fulfill our legal obligations (e.g., compliance with a legally binding subpoena). We separately and transparently publish our approach to third-party information requests and how we respond to them.

If we are subject to statutory retention periods for which the storing of your personal data is required, we process your personal data based on those legal obligations.

We may also process your personal information where you have provided your consent. At any time, you have a right to withdraw your consent by changing your communication choices, opting out from our communications or by contacting us.

**International data transfer**

DeFi Labs is based in Germany. As part of the registration and compliance screening, your data will at times be transferred to and processed outside the EEA through agreements with our Partners. Data transfers outside the EEA to or by our Partners are subject to appropriate safeguards including European Commission adequacy decisions, binding corporate rules, standard contractual clauses, and the U.S.-EU Privacy Shield principles, which are expected to be reimplemented through the Trans-Atlantic Data Privacy Framework. 

**Data retention**

We retain your personal data for as long as we are fulfilling our contractual obligations with you. Unless we are subject to statutory retention periods under applicable financial regulations, we will destroy your personal data when you stop using our services. For as long as we store your data, it will be encrypted and our limited-access commitments will remain in force.

**Your data protection rights**

We respect data protection rights and individual privacy no matter where our users are located. Under the General Data Protection Regulation, all of our users have the following data protection rights:

*If you wish to access your personal data, you can do so at any time through our self-service portal.

*If you wish to correct, update or request deletion of your personal data, you can do so at any time by contacting us using the contact details provided at the beginning of this notice.

*You have the right to object to processing of your personal data, ask us to restrict processing of your personal data, or request portability of your personal data. You can exercise these rights by contacting us using the contact details provided at the beginning of this notice. 

*If we have collected and processed your personal information with your consent, then you can withdraw your consent at any time. Please know that withdrawing your consent will not affect the lawfulness of any processing we conducted before your withdrawal, nor will it affect processing of your personal data conducted in reliance on lawful processing grounds other than consent including under the terms of our agreement if you retain your Violet credential.

*You have the right to complain to a data protection authority about our collection and use of your personal data. For more information, please contact your local data protection authority or our data protection regulator, BfDI, https://www.bfdi.bund.de/EN/Service/Kontakt/contact_node.html.

We respond to all requests we receive from people wishing to exercise their data protection rights in accordance with applicable data protection laws. We encourage you to contact us with any concerns, as we would be happy to try to resolve it directly.

**Jurisdiction-specific disclosures**

We apply the General Data Protection Regulation to all users, but recognize there are many other jurisdiction-specific data protection and privacy requirements. We believe in transparency and maximum user knowledge about their rights, even when we do not believe the jurisdiction-specific rules apply or require us to take a different action than the General Data Protection Regulation. Additional jurisdiction-specific information will be added over time.

**Privacy information for California residents**

The California Consumer Privacy Act (CCPA) gives California residents the right to opt out of the sale of personal information. We do not “sell” information that directly identifies you such as your name, telephone number, mailing address or email address – we do not provide user personal information to third parties for monetary or other valuable consideration. It’s your personal information, not ours.

If you are a California resident, the CCPA allows you to make certain requests about your personal information. Specifically, the CCPA allows you to request us to:

  *Inform you about the categories of personal information we collect or disclose about you; the categories of sources of such information; the business or commercial purpose for collecting your personal information; and the categories of third parties with whom we share/disclose personal information.

  *Provide access to and/or a copy of certain personal information we hold about you.

  *Delete certain personal information we have about you.

  *Provide you with information about the financial incentives that we offer to you, if any.
  
Please note that certain information may be exempt from such requests under California law. For example, we need certain information in order to provide and maintain your Violet credential. For any requests that are received, we will take reasonable steps to verify your identity before responding to a request.

You are also permitted to designate an authorized agent to submit certain requests on your behalf. In order for an authorized agent to be verified, you must provide the authorized agent with signed, written permission to make such requests or a power of attorney. We may also follow up with you to verify your identity before processing the authorized agent’s request.

As explained in this Policy, we share certain information with third parties who do work on our behalf. Without being discriminated against for exercising these rights, California residents have the right to request that we disclose what personal information we collect from you, to delete that information, and to opt-out of the sale of your personal information, subject to certain restrictions. You also have the right to designate an agent to exercise these rights on your behalf. This section describes how to exercise those rights and our process for handling those requests. The reporting information required by the California Consumer Privacy Act Regulations § 999.317 is available here.

The California “Shine the Light” law gives residents of California the right under certain circumstances to opt out of the sharing of certain categories of personal information (as defined in the Shine the Light law) with third parties for their direct marketing purposes. We do not provide user personal information to third parties for marketing purposes.

**Privacy information for Nevada residents**

We do not believe that our information sharing as disclosed in this policy would qualify as a sale under Nevada law.
That said, under Nevada law, Nevada residents who have purchased goods or services from us may opt out of the “sale” of “covered information” (as such terms are defined under Nevada law) for monetary consideration to a person for that person to license or sell such information to additional persons. “Covered information” includes first and last name, address, email address, and phone number, or an identifier that allows a specific person to be contacted either physically or online. If you are a Nevada resident who has purchased goods or services from us, you may submit a request to record your preference to opt out by emailing us at privacy@violet.co. Please note we may take reasonable steps to verify your identity and the authenticity of the request.

**Cookie Policy**

Violet uses cookies and may use similar technologies to operate and administer the Service. These cookies are strictly necessary to provide critical features of the Service – these cookies are essential to Violet’s operation, and without these cookies, basic functionalities would not be possible. Because these cookies are strictly necessary, users are unable to refuse them under applicable law. 

Where required by law, we will ask for your consent prior to storing cookies on your computer and will place the cookies only if you consent.

**We do not use cookies for advertising or marketing purposes.**

**Updates to this Privacy Policy**

We may update this Privacy Policy from time to time in response to changing legal, technical, or business developments. When we update our Privacy Policy, we will take appropriate measures to inform you, consistent with the significance of the changes we make. We will obtain your consent to any material Privacy Policy changes if and where this is required by applicable data protection laws. 

You can see when this Privacy Policy was last updated by checking the “last updated” date displayed at the top of this Privacy Policy.
