# Sensitive Information / Media Security

### Sensitive information&#x20;

Any organization has data that is considered sensitive for a variety of reasons. We want to protect the data from Disclosure, Alteration and Destruction (DAD)\


### Data has 3 States:&#x20;

We want to protect it as well as we can in each state

<figure><img src="../../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

Data at Rest (Stored data): This is data on disks, tapes, CDs/DVDs, USB sticks.&#x20;

* We use disk encryption (full/partial), USB encryption, tape encryption (avoid CDs/DVDs).
* Encryption can be hardware or software encryption.

Data in Motion (Data being transferred on a network

* We encrypt our network traffic, end to end encryption, this is both on internal and external networks

Data in Use: (We are actively using the files/data, it can’t be encrypted)

* We are actively using the files/data, it can’t be encrypted).  Use good practices: clean desk policy, print policy, allow no ‘shoulder surfing’, may be the use of view angle privacy screen for monitors, locking computer screen when leaving workstation

### Storage/Handling

Where do we keep our sensitive data? It should be kept in a secure, climate-controlled facility, preferably geographically distant or at least far enough away that potential incidents will not affect that facility too.&#x20;

* Many older breaches were from bad policies around tape backups.&#x20;
* Tapes were kept at the homes of employees instead of at a proper storage facility or in a storage room with no access logs and no access restrictions (often unencrypted).&#x20;

### Data retention

* Data should not be kept beyond the period of usefulness or beyond the legal requirements (whichever is greater).&#x20;
* Regulation (HIPAA or PCI-DSS) may require a certain retention of the data (1, 3, 7 years, or infinity).&#x20;
* Each industry has its own regulations and company policies may differ from the statutory requirements.&#x20;
* Know your retention requirements!
