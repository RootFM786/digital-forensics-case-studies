# Case Study 2 — Network Evidence, BYOD and Investigative Scope

## Scenario

The second case study involved alleged staff misconduct on social media using personally owned mobile devices permitted under a school BYOD policy.

The exercise required consideration of policy, privacy, evidence handling and the level of investigation justified by the evidence already available.

## Initial Hypothesis

The original investigation considered whether two staff members had used the local network to post the reported social-media comments.

Rather than relying only on the allegation, the case study identified:

- known incident timestamps
- the suspected users
- the devices associated with those users
- victim-provided screenshots / preliminary evidence
- relevant school and BYOD policies
- network communication records

## Correlating Network Evidence

The report described network communication records showing short connections from the two identified mobile devices to Facebook at the same times as the reported incidents.

This is the most directly analyst-relevant part of the case study.

The investigative logic was:

```text
Reported event
     ↓
Known timestamp
     ↓
Network communication record
     ↓
Source device association
     ↓
Compare with policy / known facts
     ↓
Decide whether further evidence is required
```

This resembles the process used in security operations when correlating an alert with firewall, proxy, DNS, authentication or endpoint telemetry.

## Scope and Escalation

The report distinguished between evidence sufficient to indicate a policy breach and evidence sufficient to establish a more serious offence.

Where the available evidence was not enough, the proposed next step was to obtain further authority and escalate rather than simply expanding the investigation without approval.

## Minimising Unnecessary Examination

Another useful decision in the original report was that a full physical examination of the devices was not necessarily required if the available communication data and voluntarily provided access were sufficient for the purpose of the investigation.

From an analyst perspective, this reflects a useful principle: **collect the minimum evidence necessary to answer the investigative question**.

## Analyst-Relevant Lessons

- start with a defined hypothesis
- use timestamps as correlation points
- validate claims against independent telemetry
- separate confirmed facts from assumptions
- know when the evidence is insufficient
- escalate rather than overreach
- document decisions and rationale

## Limitation

This was a theoretical university investigation. Network records and scenario facts were supplied as part of the exercise rather than collected from a live enterprise environment.