The Principle of Confidentiality
================================

Confidentiality prevents the disclosure of information to unauthorized people, resources and processes. Another term for confidentiality is privacy. Organizations restrict access to ensure that only authorized operators can use data or other network resources. For example, a programmer should not have access to the personal information of all employees.

Organizations need to train employees about best practices in safeguarding sensitive information to protect themselves and the organization from attacks. Methods used to ensure confidentiality include data encryption, authentication, and access control.

Protecting Data Privacy
=======================

Organizations collect a large amount of data. Much of this data is not sensitive because it is publicly available, like names and telephone numbers. Other data collected, though, is sensitive. Sensitive information is data protected from unauthorized access to safeguard an individual or an organization. There are three types of sensitive information:

*   Personal information is personally identifiable information (PII) that traces back to an individual. Figure 2 lists this category of data.

*   Business information is information that includes anything that poses a risk to the organization if discovered by the public or a competitor. Figure 3 lists this category of data.

*   Classified information is information belonging to a government body classified by its level of sensitivity. Figure 4 lists this category of data.

Controlling Access
==================

Access control defines a number of protection schemes that prevent unauthorized access to a computer, network, database, or other data resources. The concepts of AAA involve three security services: Authentication, Authorization and Accounting. These services provide the primary framework to control access.

The first “A” in AAA represents authentication. **_Authentication_** verifies the identity of a user to prevent unauthorized access. Users prove their identity with a username or ID. In addition, users need to verify their identity by providing one of the following as shown in Figure 1:

*   Something they know (such as a password)

*   Something they have (such as a token or card)

*   Something they are (such a fingerprint)

For example, if you go to an ATM for cash, you need your bankcard (something you have) and you need to know the PIN. This is also an example of multifactor authentication. Multifactor authentication requires more than one type of authentication. The most popular form of authentication is the use of passwords.

**_Authorization_** services determine which resources users can access, along with the operations that users can perform, as shown in Figure 2. Some systems accomplish this by using an access control list, or an ACL. An ACL determines whether a user has certain access privileges once the user authenticates. Just because you can log onto the corporate network does not mean that you have permission to use the high-speed color printer. Authorization can also control when a user has access to a specific resource. For example, employees may have access to a sales database during work hours, but the system locks them out after hours.

**_Accounting_** keeps track of what users do, including what they access, the amount of time they access resources, and any changes made. For example, a bank keeps track of each customer account. An audit of that system can reveal the time and amount of all transactions and the employee or system that executed the transactions. Cybersecurity accounting services work the same way. The system tracks each data transaction and provides auditing results. An administrator can set up computer policies as shown in Figure 3 to enable system auditing.

The concept of AAA is similar to using a credit card, as indicated by Figure 4. The credit card identifies who can use it, how much that user can spend, and accounts for items or services the user purchased.

Cybersecurity accounting tracks and monitors in real time. Websites, like Norse, show attacks in real-time based on data collected as part of an accounting or tracking system. Click [here](https://norse-corp.com/map/) to visit the Norse list of attack maps.

Laws and Liability
==================

Confidentiality and privacy seem interchangeable, but from a legal standpoint, they mean different things. Most privacy data is confidential, but not all confidential data is private. Access to confidential information occurs after confirming proper authorization. Financial institutions, hospitals, medical professionals, law firms, and businesses handle confidential information. Confidential information has a non-public status. Maintaining confidentiality is more of an ethical duty.

Privacy is the appropriate use of data. When organizations collect information provided by customers or employees, they should only use that data for its intended purpose. Most organizations will require the customer or employee to sign a release form giving the organization permission to use the data.

All of the laws listed in the figure include a provision for dealing with privacy starting with U.S. laws in Figure 1. Figure 2 lists a sampling of international efforts. Most of these laws are a response to the massive growth in data collection.

The growing number of privacy related statutes create a tremendous burden on organizations that collect and analyze data. Policies are the best way for an organization to comply with the growing number of privacy related laws. Policies enable organizations to enforce specific rules, procedures, and processes when collecting, storing, and sharing data.

Principle of Data Integrity
===========================

Integrity is the accuracy, consistency, and trustworthiness of data during its entire life cycle. Another term for integrity is quality. Data undergoes a number of operations such as capture, storage, retrieval, update, and transfer. Data must remain unaltered during all of these operations by unauthorized entities.

Methods used to ensure data integrity include hashing, data validation checks, data consistency checks, and access controls. Data integrity systems can include one or more of the methods listed above.

Need for Data Integrity
=======================

Data integrity is a fundamental component of information security. The need for data integrity varies based on how an organization uses data. For example, Facebook does not verify the data that a user posts in a profile. A bank or financial organization assigns a higher importance to data integrity than Facebook does. Transactions and customer accounts must be accurate. In a healthcare organization, data integrity might be a matter of life or death. Prescription information must be accurate.

Protecting data integrity is a constant challenge for most organizations. Loss of data integrity can render entire data resources unreliable or unusable.

Integrity Checks
================

An integrity check is a way to measure the consistency of a collection of data (a file, a picture, or a record). The integrity check performs a process called a hash function to take a snapshot of data at an instant in time. The integrity check uses the snapshot to ensure data remains unchanged.

A checksum is one example of a hash function. A checksum verifies the integrity of files, or strings of characters, before and after they transfer from one device to another across a local network or the Internet. Checksums simply convert each piece of information to a value and sum the total. To test the data integrity, a receiving system just repeats the process. If the two sums are equal, the data is valid (Figure 1). If they are not equal, a change occurred somewhere along the line (Figure 2).

Common hash functions include MD5, SHA-1, SHA-256, and SHA-512. These hash functions use complex mathematical algorithms. The hashed value is simply there for comparison. For example, after downloading a file, the user can verify the integrity of the file by comparing the hash values from the source with the one generated by any hash calculator.

Organizations use version control to prevent accidental changes by authorized users. Two users cannot update the same object. Objects can be files, database records, or transactions. For example, the first user to open a document has the permission to change that document; the second person has a read-only version.

Accurate backups help to maintain data integrity if data becomes corrupted. An organization needs to verify its backup process to ensure the integrity of the backup before data loss occurs.

Authorization determines who has access to an organization’s resources based on their need to know. For example, file permissions and user access controls ensure that only certain users can modify data. An administrator can set permissions for a file to read-only. As a result, a user accessing that file cannot make any changes.

The Principle of Availability
=============================

Data availability is the principle used to describe the need to maintain availability of information systems and services at all times. Cyberattacks and system failures can prevent access to information systems and services. For example, interrupting the availability of the website of a competitor by bringing it down may provide an advantage to its rival. These denial-of-service (DoS) attacks threaten system availability and prevent legitimate users from accessing and using information systems when needed.

Methods used to ensure availability include system redundancy, system backups, increased system resiliency, equipment maintenance, up-to-date operating systems and software, and plans in place to recover quickly from unforeseen disasters.

Five Nines
==========

People use various information systems in their day-to-day lives. Computers and information systems control communications, transportation and the manufacturing of products. The continuous availability of information systems is imperative to modern life. The term high availability, describes systems designed to avoid downtime. High availability ensures a level of performance for a higher than normal period. High availability systems typically include three design principles (Figure 1):

*   Eliminate single points of failure

*   Provide for reliable crossover

*   Detect failures as they occur

The goal is the ability to continue to operate under extreme conditions, such as during an attack. One of the most popular high availability practices is five nines. The five nines refer to 99.999%. This means that downtime is less than 5.26 minutes per year. Figure 2 provides three approaches to five nines.

Ensuring Availability
=====================

Organizations can ensure availability by implementing the following:

*   Equipment maintenance

*   OS and system updates

*   Backup testing

*   Disaster planning

*   New technology implementations

*   Unusual activity monitoring

*   Availability testing
