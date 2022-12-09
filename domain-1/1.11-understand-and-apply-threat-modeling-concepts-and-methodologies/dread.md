# DREAD

DREAD is a threat modeling method that involves ranking potential threats based on their level of Damage, Reproducibility, Exploitability, Affected users, and Discoverability. Here are some key points about DREAD:

* It is an acronym for Damage, Reproducibility, Exploitability, Affected users, and Discoverability.
* It is a simple, straightforward approach to threat modeling that involves ranking potential threats based on the potential damage they could cause, their likelihood of being exploited, the number of users they could affect, and how easy they are to discover.
* By ranking threats using the DREAD method, it is possible to prioritize the most serious threats and develop strategies to mitigate them.
* DREAD can be used to assess the security of any system, from a single computer to a large network or even an entire organization.
* It is particularly useful for identifying and addressing vulnerabilities in complex, interconnected systems.

**DREAD** was previously used at Microsoft and OpenStack to assess threats against the organization. The mnemonic is to remember the risk rating for security threats using five categories. A score of 0 to 10 is given to each category, then the scores are added and divided by 5 to calculate the final risk score. The categories are:

* **D**amage – how bad would an attack be?
  * **0** = no damage
  * **10** = complete destruction
* **R**eproducibility – how easy is it to reproduce the attack?
  * **0** = impossible
  * **10** = easy and without authentication
* **E**xploitability – how much work is it to launch the attack?
  * **0** = advanced knowledge and tools
  * **10** = little knowledge, a web browser
* **A**ffected users – how many people will be affected?
  * **0** = none
  * **10** = all
* **D**iscoverability – how easy is it to discover the threat?
  * **0** = nearly impossible, source code or administrator access required
  * **10** = visible easily, from a web browser
