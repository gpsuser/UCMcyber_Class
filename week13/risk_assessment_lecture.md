# Risk Assessments in Cybersecurity
## Cyber Security Protection Plan

**Level 3 BTEC Cybersecurity**  
**Lecture Duration: 60 minutes**

---

## Table of Contents

| Section | Topic | Time Allocation | Learning Outcomes |
|---------|-------|----------------|-------------------|
| 1 | Introduction and Context | 5 minutes | LO1 |
| 2 | Understanding Risk Assessment Fundamentals | 10 minutes | LO1, LO2 |
| 3 | When Risk Assessments Are Required | 5 minutes | LO1 |
| 4 | The Five-Step Risk Assessment Process | 20 minutes | LO2, LO3 |
| 5 | Risk Severity Matrix Application | 10 minutes | LO3 |
| 6 | Documentation and Templates | 8 minutes | LO4 |
| 7 | Conclusion and Review | 2 minutes | All LOs |

---

## Lesson Objectives

By the end of this lesson, learners will be able to:

1. Describe when and why organisations need risk assessments
2. List and explain the five steps of the risk assessment process
3. Apply risk assessment methodologies to practical scenarios
4. Document risk assessments using appropriate templates and formats

---

## Learning Outcomes

**LO1:** Demonstrate understanding of the purpose and context of cybersecurity risk assessments within organisational security planning

**LO2:** Identify and evaluate when risk assessments are required throughout the system lifecycle

**LO3:** Apply the five-step risk assessment methodology to identify, analyse and evaluate cybersecurity threats

**LO4:** Create appropriate documentation for risk assessments using industry-standard templates and formats

---

## 1. Introduction and Context

### The Need for Constant Vigilance

In the contemporary digital landscape, organisations face an ever-evolving array of cybersecurity threats that require systematic and ongoing evaluation. Risk assessments serve as a fundamental component of any robust cybersecurity protection plan, enabling organisations to identify vulnerabilities, understand potential impacts, and implement appropriate mitigation strategies (National Cyber Security Centre, 2024).

The cybersecurity threat landscape is characterised by continuous change. New vulnerabilities emerge daily, attack methodologies evolve, and threat actors become increasingly sophisticated. This dynamic environment necessitates a proactive approach to security management, where risk assessment becomes not a one-time activity, but rather an integral part of organisational culture and operational practice (Leszczyna, 2021).

### Why Risk Assessments Matter

Risk assessments provide organisations with a structured methodology to understand their security posture. They enable decision-makers to allocate resources effectively, prioritise security investments, and make informed choices about risk treatment options. According to the UK Government's Secure by Design principles, conducting regular security risk assessments allows organisations to understand and prioritise inherent security risks prior to making risk management decisions (UK Government Security, 2025).

The consequences of inadequate risk assessment can be severe. Organisations that fail to systematically identify and evaluate risks may find themselves unprepared for security incidents, resulting in data breaches, financial losses, reputational damage, and regulatory penalties. Conversely, organisations that embrace systematic risk assessment are better positioned to anticipate threats, implement proportionate controls, and maintain resilience in the face of cyber attacks.

---

## 2. Understanding Risk Assessment Fundamentals

### Defining Cybersecurity Risk

Before examining the risk assessment process in detail, it is essential to establish a clear understanding of what constitutes 'risk' in the cybersecurity context. The National Institute of Standards and Technology (NIST) defines risk as "a measure of the extent to which an entity is threatened by a potential circumstance or event, and typically a function of: (i) the adverse impacts that would arise if the circumstance or event occurs; and (ii) the likelihood of occurrence" (NIST, 2012, p. B-2).

In practical terms, cybersecurity risk represents the potential for loss, damage, or destruction of organisational assets as a result of cyber threats exploiting vulnerabilities. This definition encompasses three critical components:

1. **Assets:** The valuable resources that require protection (data, systems, reputation)
2. **Threats:** The potential causes of unwanted incidents (hackers, malware, natural disasters)
3. **Vulnerabilities:** Weaknesses that can be exploited by threats (software flaws, weak passwords, misconfiguration)

### Recap: Assessing Risk Probability

Risk assessments require evaluators to consider multiple factors when determining the likelihood of a threat occurring. The probability assessment takes into account several key considerations:

**Ease of Execution:** How technically difficult is the attack to perform? Threats requiring minimal technical knowledge and readily available tools present higher probability than sophisticated attacks requiring advanced capabilities.

**Reward Potential:** What benefits would an attacker gain? High-value targets such as financial systems, intellectual property, or personal data attract more attention from threat actors, increasing the probability of attack attempts.

**Detection Likelihood:** What is the probability that the attacker will be caught? If organisational monitoring and response capabilities are weak, or if attribution is difficult, threat actors may perceive lower risk in attempting attacks.

**Vulnerability Awareness:** How well-known is the vulnerability? Publicly disclosed vulnerabilities with available exploit code present higher probability risks than zero-day vulnerabilities known only to a limited number of individuals (CISA, 2022).

### Recap: Assessing Risk Impact

Impact assessment evaluates the potential consequences should a threat successfully materialise. The following factors inform impact analysis:

| Impact Factor | Considerations |
|--------------|----------------|
| **Data Loss** | Volume of data potentially lost; criticality of affected data; recovery complexity and cost |
| **Operational Disruption** | Duration of system unavailability; impact on essential functions; cascading effects on dependent systems |
| **Data Confidentiality** | Sensitivity classification of exposed data; regulatory implications; competitive disadvantage |
| **Financial Implications** | Direct costs (incident response, recovery); indirect costs (lost productivity, missed opportunities); fines and penalties |
| **Reputational Damage** | Customer trust erosion; media attention; long-term brand impact; competitive positioning |

### The Risk Severity Matrix

The risk severity matrix provides a standardised framework for combining probability and impact assessments to determine overall risk levels. This approach, aligned with frameworks such as the NCSC's Cyber Assessment Framework, enables consistent risk evaluation across different threat scenarios (NCSC, 2024).

```
┌────────────────────┬──────────────┬──────────────┬──────────────┬──────────────┐
│ Probability of     │              │              │              │              │
│ Threat Occurring   │  Very Likely │    Medium    │     High     │   Extreme    │
├────────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│                    │              │              │              │              │
│      Likely        │     Low      │    Medium    │     High     │   Extreme    │
├────────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│                    │              │              │              │              │
│     Unlikely       │     Low      │     Low      │    Medium    │     High     │
├────────────────────┼──────────────┼──────────────┼──────────────┼──────────────┤
│                    │    Minor     │   Moderate   │    Major     │    Major     │
│                    │              │              │              │              │
│                    │         Impact Level / Value of the Loss                  │
└────────────────────┴──────────────┴──────────────┴──────────────┴──────────────┘
```

The matrix demonstrates that risk severity represents the product of probability and impact. For example, a threat that is likely to occur and would have major impact results in a high-risk severity classification, demanding immediate attention and resource allocation.

---

## 3. When Risk Assessments Are Required

### Critical Trigger Points

Organisations must conduct risk assessments at specific points throughout the system lifecycle and in response to particular events. Understanding these trigger points ensures that risk assessment activities occur at the most appropriate times to inform decision-making.

#### System Design Phase

Risk assessment during the system design phase, often conducted through third-party review, enables security to be embedded into systems from the outset rather than retrofitted later. This approach, known as 'secure by design', results in more robust security postures and reduced long-term costs (UK Government Security, 2025). Design-phase assessments examine proposed architectures, identify potential vulnerabilities in planned implementations, and ensure that appropriate security controls are specified before development commences.

#### Regular Intervals

Organisations should conduct risk assessments at regular, predetermined intervals throughout the year. The appropriate frequency depends on several factors, including:

- The criticality of systems and data
- The rate of change in the threat landscape
- Regulatory or contractual obligations
- Organisational risk tolerance
- Previous assessment findings

For many organisations, quarterly or bi-annual assessments provide an appropriate balance between maintaining current risk awareness and avoiding assessment fatigue. However, organisations operating in particularly dynamic or high-risk environments may require more frequent reviews (Leszczyna, 2021).

#### Post-Incident Assessment

Following a security breach or significant incident, organisations must conduct comprehensive risk assessments to understand how the incident occurred, identify systemic weaknesses that enabled the breach, and determine what additional vulnerabilities may exist. Post-incident assessments also inform lessons learned activities and contribute to improved security practices. The UK's Information Commissioner's Office (ICO) often examines organisations' post-breach risk assessment activities when investigating data protection incidents (ICO, 2023).

#### Change-Triggered Assessment

Significant organisational changes such as mergers, acquisitions, deployment of new technologies, or modifications to essential business processes all necessitate risk reassessment. These changes may introduce new vulnerabilities, alter the threat landscape, or impact existing security controls' effectiveness.

---

## 4. The Five-Step Risk Assessment Process

### Overview of the Methodology

The five-step risk assessment process provides a systematic framework for identifying, analysing and evaluating cybersecurity risks. This methodology aligns with both UK government guidance and international standards such as ISO/IEC 27005:2022 (BSI, 2022). Each step builds upon the previous one, creating a comprehensive understanding of the organisation's risk landscape.

### Step 1: Identify Possible Threats

The first and perhaps most critical step involves the comprehensive identification of all potential threats facing organisational systems. Failure to identify threats during this phase means they cannot be subsequently analysed or mitigated, leaving significant gaps in the security posture.

Threat identification requires consideration of multiple threat categories:

**External Malicious Threats:** These include hackers, cybercriminals, hacktivists, nation-state actors, and terrorist organisations seeking to compromise organisational systems for financial gain, espionage, disruption, or ideological purposes.

**Internal Threats:** Disgruntled employees, negligent users, or malicious insiders who have legitimate access to systems but may abuse their privileges represent significant risks. Studies consistently demonstrate that insider threats account for a substantial proportion of security incidents (Ponemon Institute, 2020).

**Environmental Threats:** Natural disasters (floods, fires, earthquakes), power failures, and environmental conditions can impact system availability and integrity.

**Technical Threats:** Hardware failures, software bugs, and technological obsolescence create vulnerabilities that threat actors may exploit.

**Supply Chain Threats:** Third-party suppliers, vendors, and service providers may introduce vulnerabilities through compromised products, services, or access privileges.

The threat identification process should involve:

- Review of threat intelligence sources
- Analysis of previous incidents
- Consultation with security professionals
- Examination of industry-specific threat reports
- Consideration of emerging threats

### Step 2: Identify the Likelihood of Threats

Having identified potential threats, assessors must evaluate the probability of each threat materialising. This step utilises the risk matrix framework discussed earlier, assigning likelihood classifications of unlikely, likely, or very likely to each identified threat.

Likelihood assessment requires consideration of:

**Threat Actor Capability:** Does the threat actor possess the necessary skills, tools, and resources to execute the attack successfully?

**Threat Actor Intent:** Is there motivation for the threat actor to target the organisation specifically?

**Target Attractiveness:** Does the organisation present an appealing target based on potential rewards, reputational impact, or symbolic value?

**Existing Security Controls:** How effective are current security measures at preventing or deterring the threat?

**Historical Data:** Has this threat materialised previously, either within the organisation or across the industry sector?

For example, when assessing the likelihood of ransomware attacks, evaluators would consider the prevalence of ransomware in their industry sector, the sophistication of the organisation's email filtering and endpoint protection, the effectiveness of user awareness training, and the attractiveness of the organisation's data to ransomware operators.

### Step 3: Assess the Vulnerabilities

Vulnerability assessment examines the organisation's susceptibility to each identified threat. This step determines how exposed the organisation is based on current security controls and existing weaknesses in systems, processes, or procedures.

Vulnerability assessment methodologies include:

**Technical Vulnerability Scanning:** Automated tools scan systems to identify missing patches, misconfigurations, and known vulnerabilities. Tools such as Nessus, Qualys, or OpenVAS provide comprehensive vulnerability detection capabilities (Shah and Mehtre, 2015).

**Penetration Testing:** Ethical hackers simulate real-world attacks to identify exploitable vulnerabilities and demonstrate potential attack paths. Penetration testing validates the effectiveness of security controls under adversarial conditions.

**Security Configuration Review:** Assessors examine system configurations against security baselines and best practice standards to identify deviations that create vulnerabilities.

**Process and Procedure Review:** Organisational processes, including access management, change control, and incident response, are evaluated for weaknesses that could be exploited.

**Social Engineering Assessment:** Simulated phishing campaigns and social engineering tests identify vulnerabilities in human behaviour and security awareness.

The vulnerability assessment step should leverage tools and techniques discussed in previous lessons, including network mapping, port scanning, and service enumeration, to build a comprehensive vulnerability profile.

### Step 4: Assess the Impact Level

Impact assessment determines the potential consequences if a threat successfully exploits identified vulnerabilities. Using the risk matrix framework, assessors classify potential impacts as minor, moderate, or major based on the impact factors discussed earlier.

Impact assessment must consider multiple dimensions:

**Operational Impact:** To what extent would essential functions be disrupted? Could the organisation continue to deliver critical services?

**Financial Impact:** What direct and indirect costs would the organisation incur? This includes incident response costs, system recovery expenses, lost revenue, regulatory fines, and legal costs.

**Data Impact:** What data would be compromised? Is the affected data personal data subject to GDPR protections? Does it include intellectual property, trade secrets, or contractually protected client information?

**Reputational Impact:** How would customers, partners, and stakeholders respond to the incident? Would media coverage amplify reputational damage?

**Legal and Regulatory Impact:** What legal obligations exist? Would the incident constitute a data breach requiring notification under GDPR? Could it result in regulatory sanctions?

**Strategic Impact:** Would the incident affect long-term strategic objectives, competitive positioning, or organisational viability?

Impact assessments should be documented with clear justification for assigned impact levels. For instance, impact assessment for a distributed denial of service (DDoS) attack on an e-commerce platform would consider lost sales during the outage, reputational damage from customer inconvenience, and potential migration of customers to competitors.

### Step 5: Determine the Risk Severity

The final step synthesises the likelihood and impact assessments to determine overall risk severity. Using the risk matrix, each identified risk is classified as low, medium, high, or extreme. This classification drives prioritisation decisions and informs resource allocation.

```
Risk Severity = Probability × Impact
```

Risk severity classifications typically translate into the following treatment priorities:

| Risk Level | Treatment Priority | Typical Response |
|-----------|-------------------|------------------|
| **Extreme** | Immediate action required | Deploy emergency controls; escalate to senior management; allocate significant resources |
| **High** | Urgent action required | Implement mitigation controls within defined timeframe; regular monitoring |
| **Medium** | Action required | Plan and implement controls; assign responsibility and deadlines |
| **Low** | Accept or monitor | Document acceptance decision; periodic review |

Organisations must develop risk treatment plans for all risks classified as medium or above, documenting the specific controls to be implemented, responsible parties, implementation timelines, and residual risk levels following control implementation.

---

## 5. Risk Severity Matrix Application

### Practical Application Principles

The effective application of the risk severity matrix requires consistency, transparency, and sound professional judgement. Organisations should establish clear criteria for probability and impact classifications to ensure that different assessors reach similar conclusions when evaluating comparable risks.

### Standardised Approach Requirements

The risk assessment methodology must be standardised across the organisation to ensure consistency and comparability. Without standardisation, risk assessments conducted by different teams or at different times may reach contradictory conclusions, undermining confidence in the process and creating confusion for decision-makers.

Standardisation encompasses:

**Consistent Probability Definitions:** All assessors must apply the same criteria when classifying threats as unlikely, likely, or very likely.

**Uniform Impact Thresholds:** Clear monetary, operational, or reputational thresholds should define the boundaries between minor, moderate, and major impact classifications.

**Common Risk Tolerance:** The organisation's risk appetite should inform treatment decisions consistently across all risk categories.

**Regular Calibration:** Periodic reviews of risk classification decisions ensure that standards remain consistently applied and calibrated against actual incident experiences.

Without this standardised approach, organisations risk making inconsistent security investment decisions, potentially over-investing in lower-priority areas whilst neglecting more significant risks.

---

## 6. Documentation and Templates

### The Importance of Documentation

Comprehensive documentation serves multiple critical purposes within the risk assessment process. Documentation provides:

**Historical Record:** A permanent record enabling future comparison and trend analysis

**Justification for Decisions:** Evidence supporting security investment and resource allocation decisions

**Regulatory Compliance:** Demonstrable compliance with legal and contractual obligations requiring documented risk assessment

**Communication Tool:** A mechanism for conveying risk information to stakeholders at all organisational levels

**Baseline for Future Assessments:** A reference point for subsequent assessments to measure progress and identify emerging risks

The NCSC emphasises that documenting risk management decisions and ensuring visibility to senior leadership remains crucial for accountability and strategic planning (NCSC, 2024).

### Risk Assessment Template Structure

A comprehensive risk assessment template should capture all essential information whilst remaining accessible to both technical and non-technical audiences. The following fields constitute a robust risk assessment template:

| Field | Purpose | Example Content |
|-------|---------|-----------------|
| **Threat Number** | Sequential identifier for tracking and reference | 1, 2, 3, etc. |
| **Threat Title** | Concise description enabling quick identification | "Staff Connecting Own Devices to Network" |
| **Probability** | Likelihood classification based on threat analysis | Unlikely / Likely / Very Likely |
| **Impact Level** | Potential consequences if threat materialises | Minor / Moderate / Major |
| **Risk Severity** | Overall risk classification from matrix | Low / Medium / High / Extreme |
| **Explanation** | Detailed contextualised threat analysis | Comprehensive description linking threat to organisational context |

### Worked Example: BYOD Risk Assessment

The following example demonstrates a completed risk assessment entry:

**Threat Number:** 1

**Threat Title:** Staff Connecting Own Devices to Network

**Probability:** Likely

**Impact Level:** Major

**Risk Severity:** High

**Explanation:** The organisation's Bring Your Own Device (BYOD) policy encourages staff to use personal devices for work purposes, offering flexibility and cost savings. However, this policy introduces significant security risks. Personal devices may be infected with malware before connection to the corporate network, potentially spreading infections to other systems. Staff may install unauthorised applications on personal devices that could intercept or exfiltrate confidential data. Personal devices typically lack enterprise-grade security controls such as full-disk encryption, mobile device management, or regular security updates. Should an employee lose their device or have it stolen, confidential organisational data stored on the device could be exposed, potentially resulting in GDPR violations, competitive disadvantage, and reputational damage. The device may also be used as an entry point for network compromise, particularly if employees use the same credentials across personal and corporate systems.

### Documentation Best Practices

**Plain Language:** Risk documentation should use clear, jargon-free language accessible to non-technical stakeholders whilst retaining sufficient technical detail for security professionals.

**Regular Updates:** Risk registers constitute living documents requiring updates as threats evolve, vulnerabilities are discovered or remediated, and organisational contexts change.

**Version Control:** Maintain version history to track how risk assessments evolve over time and to demonstrate continuous improvement in risk management practices.

**Stakeholder Engagement:** Share risk assessment documentation with appropriate stakeholders, including senior management, IT teams, and business function owners, ensuring all parties understand their responsibilities in risk treatment.

---

## 7. Conclusion and Review

### Summary of Key Concepts

This lecture has explored the fundamental concepts and methodologies underpinning cybersecurity risk assessment. Risk assessment provides organisations with a systematic framework for understanding their security posture, prioritising threats, and allocating resources effectively. The five-step methodology—identifying threats, assessing likelihood, evaluating vulnerabilities, determining impact, and calculating risk severity—creates a comprehensive and defensible approach to risk management.

The dynamic nature of cybersecurity threats demands ongoing risk assessment activities rather than one-time exercises. Organisations must embed risk assessment into their operational culture, conducting assessments at critical points in the system lifecycle, at regular intervals, following security incidents, and in response to significant organisational changes.

### Practical Applications

Learners should recognise that risk assessment constitutes more than an academic exercise—it represents a critical practical skill applicable across diverse organisational contexts. Whether assessing risks to educational institution networks, e-commerce platforms, healthcare systems, or critical national infrastructure, the fundamental principles remain consistent. The ability to systematically identify threats, evaluate their significance, and communicate findings to diverse stakeholders represents a highly valued skill in the cybersecurity profession.

### Next Steps

Having established understanding of risk assessment methodologies, future lessons will explore risk treatment strategies, examining how organisations can accept, mitigate, transfer, or avoid identified risks. Learners will also develop practical skills in implementing security controls, monitoring control effectiveness, and conducting post-implementation reviews to ensure that risk treatment decisions achieve their intended outcomes.

### Review of Learning Outcomes

Learners should now be able to:

- Explain why organisations require ongoing risk assessments and identify appropriate trigger points
- Describe the five-step risk assessment process in detail
- Apply the risk severity matrix to classify risks appropriately
- Create comprehensive risk assessment documentation using industry-standard templates

---

## References

British Standards Institution (2022) *ISO/IEC 27005:2022 Information security, cybersecurity and privacy protection — Guidance on managing information security risks*. London: BSI.

Cybersecurity and Infrastructure Security Agency (2022) *Guide to getting started with a cybersecurity risk assessment*. Available at: https://www.cisa.gov/sites/default/files/2024-09/24_0828_safecom_guide_getting_started_cybersecurity_assessment_2022_final_508C.pdf (Accessed: 7 December 2024).

Information Commissioner's Office (2023) *Data security incident trends*. Available at: https://ico.org.uk/about-the-ico/research-and-reports/data-security-incident-trends/ (Accessed: 7 December 2024).

Leszczyna, R. (2021) 'Review of cybersecurity assessment methods: Applicability perspective', *Computers & Security*, 108, p. 102376. doi: 10.1016/j.cose.2021.102376.

National Cyber Security Centre (2024) *Cyber Assessment Framework V3.2*. Available at: https://www.ncsc.gov.uk/collection/cyber-assessment-framework (Accessed: 7 December 2024).

National Institute of Standards and Technology (2012) *Guide for conducting risk assessments*. NIST Special Publication 800-30 Revision 1. Gaithersburg, MD: NIST. Available at: https://nvlpubs.nist.gov/nistpubs/legacy/sp/nistspecialpublication800-30r1.pdf (Accessed: 7 December 2024).

Ponemon Institute (2020) *Cost of insider threats: Global report*. Traverse City, MI: Ponemon Institute.

Shah, S. and Mehtre, B.M. (2015) 'An overview of vulnerability assessment and penetration testing techniques', *Journal of Computer Virology and Hacking Techniques*, 11(1), pp. 27-49. doi: 10.1007/s11416-014-0231-x.

UK Government Security (2025) *Performing a security risk assessment*. Available at: https://www.security.gov.uk/policy-and-guidance/secure-by-design/activities/performing-a-security-risk-assessment/ (Accessed: 7 December 2024).

---

## Bibliography

Bertoglio, D.D. and Zorzo, A.F. (2017) 'Overview and open issues on penetration test', *Journal of the Brazilian Computer Society*, 23(1), pp. 1-16.

Cherdantseva, Y. et al. (2016) 'A review of cyber security risk assessment methods for SCADA systems', *Computers & Security*, 56, pp. 1-27.

Leszczyna, R. (2024) 'Cybersecurity assessment methods—Why aren't they used?', *IT Professional*, 26(4), pp. 14-21.

National Cyber Security Centre (2024) *Risk management for cyber security*. Available at: https://www.ncsc.gov.uk/collection/risk-management (Accessed: 7 December 2024).

Peltier, T. (2010) *Information security risk analysis*. 3rd edn. Boca Raton, FL: Auerbach Publications.

Shedden, P., Ruighaver, A.B. and Ahmad, A. (2010) 'Risk management standards – the perception of ease of use', in *Proceedings of the 5th International Conference on Availability, Reliability and Security*. Krakow, Poland, 15-18 February. Los Alamitos, CA: IEEE Computer Society, pp. 546-553.

Stoneburner, G., Goguen, A. and Feringa, A. (2002) *Risk management guide for information technology systems*. NIST Special Publication 800-30. Gaithersburg, MD: NIST.

---

## Word Count

**Total Word Count:** 4,847 words (excluding title page, table of contents, references, and bibliography)

---

*End of Lecture Document*