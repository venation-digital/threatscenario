<!---
VERSION: 0.14
AUTHOR: Venation, Gert-Jan Bruggink
RIGHTS reserved:
-->

# Title, detailing what happens in this scenario, by whom, and directed by what objective

## Overview 
---
**Identifier:** YEARMONTH-NAME (e.g. 202110-SCENARIO_HAPPENS_ABC)

**Created:** {{date}} {{time}}

**Latest update:** YEAR-MONTH-DAY (e.g. 2021-11-11, 10:00)

**Status:** #Status/Open

**Author(s):** [Venation](https://venation.digital/)

**Category:**
#Category/Example

<!---
Tag all items that would be relevant for the scenario on a high level. Usecase is sorting and structuring content.
-->

**Tags:**
#Tags/Example

<!---
Tag all items that would be relevant for the scenario on a low level. Usecase is performing deeper research between different scenarios.
-->

**Priority Intelligence Requirement(s):**
<!---
Describe any relevant (priority) intelligence requirements that link to this scenario.

Preferably standardise on Intel471's 'General Intelligence Requirements Handbook'.
-->

<br>


## Scenario breakdown
---

**Objective(s):**

Any_relevant_input_is_detailed_here

<!---
Detailing the most-likely objective(s) of the scenario. Should there be more than one objective, items shall be listed through numbering and ordered from most-likely to least likely. 
-->

**Summary:**

Any_relevant_input_is_detailed_here

<!---
The summary describes the why, how, what for each scenario. The text shall be 3 paragraphs, aligned with the why-how-what, and should consist of 2 rows of text per paragraph. Rows of text written shall follow BLUF writing and active voice.
-->

**Industry Tagging:**
#Industry/Example


**Functions and/or systems targeted:**

Any_relevant_input_is_detailed_here

<!---
If specific functions or systems are targeted, they are broken down here.
-->

**Scenario sequence:**

1. Step - Reconnaissance
2. Step - Initial access
3. Step - Lateral movement

<!---
Providing a listed sequencing of events, describing how it happens, what we know and what we don't know.
-->

**Considerations:**

Any_relevant_input_is_detailed_here

<!---
Annotate all relevant considerations for this particular scenario.
-->


## Adversary playbook
---
**Associated threat actor profile:**

| Name    | Tag | Category | Capability  | Intent | Comments |
| --------| --- |-------------| -----| -----| --- |
| APT28 | #Actor/Example | State-sponsored entity | High | High | TBD |


**TTP breakdown:**

| Tactic_ID | Tactic_ID | Technique_ID | Technique | Procedure(s) | Detection Opportunity | Comments 
| --------|-------------| -----|-----| -----|-----|-----|
| TA0043 | Reconnaissance | T1589 | Gather Victim Identity Information  | Acquired mobile phone numbers of potential targets, possibly for mobile malware or additional phishing operations. | Detection_tagging | TBD | 
| TA0001 | Initial Access  | T1189 | Drive-by Compromise | Use watering hole attack to gain initial access to victims within a specific IP range. | Detection_tagging | TBD | 
| TA0008 | Lateral Movement | T1550.001 | Use Alternate Authentication Material: Application Access Token  | Use several malicious applications that abused OAuth access tokens to gain access to target email accounts. | Detection_tagging | TBD | 
<!---
Based on the listed scenario sequence, describing what actually happened or is forecasted to happen in the event.

More details on tactic & technique referencing, please visit: [https://attack.mitre.org/](https://attack.mitre.org/)
-->

## Other
---
**Wrap-up:**

Any_relevant_input_is_detailed_here

**Sources:**

* LINKED_URL

<!---
List all relevant and available OPEN-SOURCE source references.
-->


**JSON:**

```{toggle}
{
  "firstName": "John",
  "lastName": "Smith",
  "age": 25
}
```
