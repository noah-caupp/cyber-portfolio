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
- **Date:** 2/19/2026
- **Domain:** 1.0 General Security Concepts
- **Question topic (1 line):** Which of the following statements accurately describes the root of trust model in a public key infrastructure (PKI)?
- **Why I missed it (concept gap / trick wording / rushed / didn't know term):** Trick wording
- **Correct concept (2–4 lines, plain English):** The root of trust model defines how users and different CAs can trust one another, with each CA issuing itself a root certificate.
- **Action step to lock it in (what I will do tomorrow for 5 minutes):** Review root of trust model

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
