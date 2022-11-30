# 1.10 Understand and apply risk management concepts

## Identify threats and vulnerabilities

Threats: any potential occurrence that may cause an undesirable or unwanted outcome for a specific asset; they can be intentional or accidental; loosely think of a threat as a weapon that could cause harm to a target

Vulnerability: the weakness in an asset or absence or weakness of a safeguard or countermeasure; a flaw, limitation, error, frailty, or susceptibility to harm

Threats and vulnerabilities are related: a threat is possible when a vulnerability is present.

* Threats exploit vulnerabilities, which results in exposure. Exposure is a risk, and risk is mitigated by safeguards. Safeguards protect assets that are endangered by threats.
* Threat Agent/Actors: intentionally exploit vulnerabilities
* Threat Events: accidental occurrences and intentional exploitations of vulnerabilities
* Threat Vectors: AKA attack vector is the path or means by which an attack or attacker can gain access to a target in order to cause harm
* Exposure: being susceptible to asset loss because of a threat; the potential for harm to occur; quantitative risk analysis value of exposure factor (EF) is derived from this concept
* Risk: the possibility or likelihood that a threat will exploit a vulnerability to cause harm to an asset and the severity of damage that could result; the > the potential harm, the > the risk

## Risk assessment/analysis

* risk is a threat with a vulnerability
* risk = threat \* vulnerability (or probability of harm \* severity of harm)
* addressing either the threat or threat agent or vulnerability directly results in a reduction of risk (known as threat mitigation)
* Threats exploit vulnerabilities, which results in exposure. Exposure is risk, and risk is mitigated by safeguards. Safeguards protect assets that are endangered by threats.
* All IT systems have risks. All organizations have risks. There is no way to eliminate 100% of all risks. Instead, upper management must decide which risks are acceptable, and which are not. There are two primary risk-assessment methodologies:
  * Quantitative Risk Analysis: assigns real dollar figures to the loss of an asset and is based on mathematical calculations
  * Qualitative Risk Analysis: assigns subjective and intangible values to the loss of an asset and takes into account perspectives, feelings, intuition, preferences, ideas, and gut reactions.
  * Most organizations employ a hybrid of both risk assessment methodologies
  * The goal of risk assessment is to identify risks (based on asset-threat parings) and rank them in order of criticality

## Risk response

Risk Assessment is used to identify the risks and set criticality priorities, and then risk response is used to determine the best defense for each identified risk

* Possible responses to risk:
  * Mitigation or reduction
  * Assignment or transfer
  * Deterrence
  * Avoidance
  * Acceptance
  * Reject or ignore

Risk response formation of a plan for each identified risk. For a given risk, a choice can be made to reduce the risk (risk mitigation), assign the risk to the team for action (risk assignment), acceptance of the risk, or ignore the risk (risk rejection)

Countermeasure selection and implementation:

* A countermeasure sometimes referred to as a “control” or a “safeguard,” can help reduce risk
* For exam preparation, understand how the concepts are integrated into your environment. This is not a step-by-step technical configuration, but the process of the implementation — where you start, in which order it occurs, and how you finish.
* Keep in mind that security should be designed to support and enable business tasks and functions. Security controls, countermeasures, and safeguards can be implemented administratively, logically / technically, or physically. These 3 categories should be implemented in a conceptual layered defense-in-depth manner to provide maximum benefit. This is based on the concept that policies (part of administrative controls) drive all aspects of security and thus form the initial protection layer around assets. Then, logical and technical controls provide protection against logical attacks and exploits. Then, physical controls provide protection against real-world physical attacks against facilities and devices.

## Applicable Types of Controls

Administrative: the policies and procedures defined by an organization's security policy and other regulations or requirements

**Physical:** security mechanisms focused on providing protection to the facility and real-world objects

**Preventive:** A preventive or preventative control is deployed to thwart or stop unwanted or unauthorized activity from occurring

**Deterrent:** A deterrent control is deployed to discourage security policy violations. Deterrent and preventative controls are similar, but deterrent controls often depend on individuals being convinced not to take an unwanted action

**Detective:** Detective control is deployed to discover or detect unwanted or unauthorized activity. Detective controls operate after the fact

**Compensating:** A compensating control is deployed to provide various options to other existing controls to aid in the enforcement and support of security policies. They can be any controls used in addition to, or in place of, another control. They can be a means to improve the effectiveness of a primary control or as the alternative or failover option in the event of a primary control failure

**Corrective**: A corrective control modifies the environment to return systems to normal after an unwanted or unauthorized activity has occurred. It attempts to correct any problems resulting from a security incident

**Recovery:** an extension of corrective controls but have more advanced or complex abilities. A recovery control attempts to repair or restore resources, functions, and capabilities after a security policy violation. Recovery controls typically address more significant damaging events compared to corrective controls, especially when security violations may have occurred

**Directive:** A directive control is deployed to direct, confine, or control the actions of subjects to force or encourage compliance with security policies

## Control assessments (security and privacy)

Periodically assess security and privacy controls. What’s working? What isn’t working? As part of this assessment, the existing documents must be thoroughly reviewed, and some of the controls must be tested at random. A report is typically produced to show the outcomes and enable the organization to remediate deficiencies. Often, security and privacy control assessments are performed and/or validated by different teams, with the privacy team handling the privacy aspects

Monitoring and Measurement

* Monitoring and measurement are closely aligned with identifying risks
* While monitoring is used for more than security purposes, monitoring should be tuned it to ensure the organization is notified about potential security incidents as soon as possible.
* If a security breach occurs, monitored systems and data become valuable from a forensics perspective. From the ability to derive the root cause of an incident to make adjustments to minimize the chances of reoccurrence.

## Reporting

Risk Reporting is a key task to perform at the conclusion of risk analysis (i.e. production and presentation of a summarizing report)

A Risk Register or Risk Log is a document that inventory all identified risks to an organization or system or within an individual project. A risk register is used to record and track the activities of risk management, including:

* identifying risks
* evaluating the severity of, and prioritizing those risks
* prescribing responses to reduce or eliminate the risks
* track the progress of risk mitigation

## Continuous Improvement

Risk analysis is performed to provide upper management with the details necessary to decide which risks should be mitigated, which should be transferred, which should be deterred, which should be avoided, and which should be accepted

An **Enterprise Risk Management** (ERM) program can be evaluated using the Risk Maturity Model (RMM). An RMM assesses the key indicators and activities of a mature, sustainable, and repeatable risk management process, typically relating the assessment of risk maturity against a five-level model such as:

* Ad hoc - a chaotic starting point from which all organizations initiate risk management
* Preliminary - loose attempts are made to follow risk management processes, but each department may perform risk assessment uniquely
* Defined - a common or standardized risk framework is adopted organization-wide
* Integrated - Risk management operations are integrated into business processes, metrics are used to gather effectiveness data, and risk is considered an element in business strategy decisions
* Optimized - risk management focuses on achieving objectives rather than just reacting to external threats; increased strategic planning is geared toward business success rather than just avoiding incidents, and lessons learned are re-integrated into the risk management process.

## Risk Frameworks

A risk framework is a guide or recipe for how risk is to be accessed, resolved, and monitored. NIST established the **Risk Management Framework** (RMF) and the **Cybersecurity Framework** (CSF). The CSF is designed for critical infrastructure and commercial organizations, whereas the RMF establishes mandatory requirements for federal agencies

The RMF, defined by NIST in SP 800-37 Rev 2, establishes mandatory security requirements for federal agencies

There are other risk frameworks, such as the British Standard BS 31100. Be familiar with frameworks and their goals

* The **RMF 7 steps**, and has **six cyclical phases**:
  * **Prepare** to execute the RMF from an organization- and system-level perspective by establishing a context and priorities for managing security and privacy risk.
  * **Categorize** the system and the information processed, stored, and transmitted by the system based on an analysis of the impact of loss.
  * **Select** an initial set of controls for the system and tailor the controls as needed to reduce risk to an acceptable level based on an assessment of risk.
  * **Implement** the controls and describe how the controls are employed within the system and its environment of operation.
  * **Assess** the controls to determine if the controls are implemented correctly, operating as intended, and producing the desired outcomes with respect to satisfying the security and privacy requirements.
  * **Authorize** the system or common controls based on a determination that the risk to organizational operations and assets, individuals, and other organizations, and the nation is acceptable.
  * **Monitor** the system and associated controls on an on-going basis to include assessing control effectiveness, documenting changes to the system and environment of operation, conducting risk assessments and impact analysis, and reporting the security and privacy posture of the system.
