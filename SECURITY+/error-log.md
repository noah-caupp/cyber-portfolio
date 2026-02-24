# Security+ Error Log

## How to use
Whenever I miss a question, I log it here. The goal is to reduce repeat misses.

---

## Miss Log

### Entryies
- **Date:** 2/18/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** You have transferred an encrypted file across a network using the Server Message Block (SMB) Protocol. What happens to the file's encryption?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap
- **Correct concept (2–4 lines, plain English):** A file is automatically unencrypted when you copy it over a network using the SMB Protocol. The encryption does not carry over to the new location, nor does the file inherit from the new location. A file can be moved using the SMB Protocol.
- **Cue to remember (1 line):** Automatically unendrypted when using SMB
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Study SMB protocol behavior
---
- **Date:** 2/18/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Which of the following database encryption methods encrypts the entire database and all backups?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap
- **Correct concept (2–4 lines, plain English):** Transparent Data Encryption (TDE) encrypts the entire database and all backups. TDE: encrypts data at rest, which is data not being currently used. It's called transparent because when an authorized user needs to access the data, it is automatically decrypted so the user does not see the process or need to do anything extra.
- **Cue to remember (1 line):** TDE encrypts all
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review TDE
---
- **Date:** 2/18/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** You want to protect data on hard drives for users with laptops. You want the drive to be encrypted, and you want to prevent the laptops from booting unless a special USB drive is inserted. In addition, the system should not boot if a change is detected in any of the boot files. What should you do?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap
- **Correct concept (2–4 lines, plain English):** Use BitLocker to encrypt the entire system volume and protect both operating system and user data. Use BitLocker with a Trusted Platform Module (TPM) to protect the boot environment components such as the BIOS, Master Boot Record, Boot Sector, Boot Manager, and Windows Loader. The system is shut down if a boot environment change is detected. Using BitLocker, drives are locked if they are moved to another computer, and you can require a startup key on a USB drive or a PIN before the system boots.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review question again
---
- **Date:** 2/19/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Which of the following statements accurately describes the root of trust model in a public key infrastructure (PKI)?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Trick wording
- **Correct concept (2–4 lines, plain English):** The root of trust model defines how users and different CAs can trust one another, with each CA issuing itself a root certificate.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review root of trust model
---
- **Date:** 2/23/26
- **Domain:** 4.0 Security Operations
- **Question topic (1 line):** Which of the following principles is implemented in a mandatory access control model to determine object access by classification level?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Trick wording
- **Correct concept (2–4 lines, plain English):** Need to know is used with mandatory access control environments to implement granular control over access to segmented and classified data. Clearance is the subject classification label that grants a user access to a specific security domain in a mandatory access control environment.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review difference betwwen Clearance and Need to know.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** A recently breached company tasks the cyber team to further restrict end-user permissions.
What describes the use of an application allow list?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap
- **Correct concept (2–4 lines, plain English):** It enforces various policies in computer systems.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Application allow lists enforce a wide range of policies.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** An information technology manager conducted an audit of the company's support tickets. The manager noticed a trend with the tickets, where the majority were for new computer setups. What security control function would the manager's implementation of a new standard operating procedure have?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Didn't know term.
- **Correct concept (2–4 lines, plain English):** A directive control enforces a rule of behavior, such as a policy, best practice standard, or standard operating procedure (SOP).
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Corrective controls are put into place after an attack and directive controls enforce rules of behavior.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Combining encryption with steganography involves several steps. From the list on the left, drag a description of a step or result in this process to the correct order on the right.
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap.
- **Correct concept (2–4 lines, plain English):**
- 1 - Encrypt plaintext with a private key to generate ciphertext.
- 2 - The ciphertext is hidden inside of a media file, such as an image, using steganography.
- 3 - The recipient extracts the ciphertext and decrypts it using the matching public key.
- 4 - Anyone intercepting the message would have to know its there before being able to decrypt it.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review correct order.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** The IT director at a financial institution focuses on implementing compensating managerial controls to augment the institution's existing security framework. If a mandated control cannot be put into place, which of the following compensating controls should an analyst recommend as a sufficient substitute?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Trick wording
- **Correct concept (2–4 lines, plain English):** While employee training is an important part of any organization's security controls, it classifies as an operational control more than a managerial one. In a scenario where the analyst cannot patch a critical system due to operational reasons, isolating it from the network can serve as a compensating control. This offers an equivalent level of protection by ensuring potential cyber threats cannot reach the system.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review control types.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Which kind of access control technology allows more than just the identity of an individual to be transmitted wirelessly to either allow or deny access?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap.
- **Correct concept (2–4 lines, plain English):** Unlike proximity cards that only transmit the owner's identity, smart cards can contain and transmit many more pieces of information.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review question
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Hashing is the process of converting one value into another using a mathematical algorithm like MD5 or SHA. This fixed length of data is called the hash. Which of the following are true statements about hashing?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Rushed.
- **Correct concept (2–4 lines, plain English):** An encryption key is a string of bits that is randomly generated using a specific cipher, not a hash. Hashing is used on data that does not need to be decrypted, such as a password. Furthermore, A hash cannot be decrypted.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Remember to slow down and think. Review question again.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** An acceptable use policy requires the system to encrypt confidential information while in transit. All employees must use secure email when exchanging proprietary information with external vendors. Which of the following describes this type of acceptable use policy?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap.
- **Correct concept (2–4 lines, plain English):** Operational controls like this acceptable use policy focus on procedures and responsibilities that are well defined and executed by people. They help to ensure the security of an organization's day-to-day operations. Managerial controls establish strategies, goals, and objectives for an organization's overall security program. They often include risk assessment and the review of security controls.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review control types.
---
- **Date:** 2/24/26
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Blockchain order of operations.
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Concept gap.
- **Correct concept (2–4 lines, plain English):**
- 1 - User1 requests a transaction with User2.
- 2 - The transaction is represented online as a block.
- 3 - The block is distributed to everyone on a peer-to-peer network.
- 4 - The network users verify the transaction is valid.
- 5 - The block is added to the chain.
- 6 - The contents of the transaction move to User2.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review order.
## Repeat Misses (Top 10)
1.
2.
3.
4.
5.
6.
7.
8.
9.
10.
