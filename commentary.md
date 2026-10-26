# As Voice Becomes Infrastructure, Workflow Becomes the Differentiator

### What Healthcare AI Reveals About Where Application Value May Be Moving

**Johnny Lai** · Technology & Market Commentary · October 2026 · Version 1.0

<p align="center">
  <img
    src="images/commentary-cover.png"
    alt="Cover image for As Voice Becomes Infrastructure, Workflow Becomes the Differentiator, featuring a telephone in a healthcare office."
  />
</p>

AI can increasingly answer the phone.

It can understand a caller, respond naturally, adjust when interrupted, send a text, and continue the interaction across voice and messaging channels. Some communications platform providers are also making it easier to connect AI applications directly to voice and messaging infrastructure.

As conversational voice AI becomes more accessible, the ability to conduct natural voice conversations may become less of a differentiator. Voice quality, latency, and reliability still matter, but conversational AI is becoming available to a wider range of applications.

The harder question is what an application can actually accomplish once it understands the caller's request.

Consider a patient calling a healthcare practice and saying:

*"I need to move my appointment to Friday afternoon, preferably with the same doctor."*

Understanding that request is one problem. Actually completing it is another.

The application may need to identify the patient and the correct appointment, check the doctor's availability, apply scheduling rules, and consider any relevant clinical or service requirements. It must then update the scheduling system, verify that the change succeeded, and confirm the result to the patient.

If the requested appointment is unavailable or falls outside established rules, the application needs to find an appropriate alternative or involve office staff.

The conversation is the interface. The workflow is where the work gets done.

## A Conversation Is Not a Workflow

Healthcare makes this distinction particularly clear.

Even routine activities such as scheduling can involve complex rules. Talkdesk, for example, describes specialty scheduling as involving rules specific to individual doctors, team-based care models, and clinical protocols that can exceed the capabilities of conventional self-scheduling systems.

Similar complexity appears in patient intake, referrals, prescription requests, billing, and follow-up care. Understanding what a patient wants does not necessarily establish whether the requested action is appropriate, authorized, or operationally possible.

Conversational AI can make it easier for patients to interact with these services. But an AI system may successfully understand and respond to a patient while leaving the underlying task unfinished. Completing that task requires access to the information, rules, and systems that govern the workflow.

## From Systems of Record to Systems of Action

Healthcare organizations already maintain much of the information needed to carry out these workflows.

Electronic Health Records (EHRs), Electronic Medical Records (EMRs), and practice-management systems contain patient information, appointment history, details about doctors and other healthcare professionals, treatment records, and operational data. These systems have traditionally focused on maintaining records and supporting established business processes.

AI-enabled healthcare applications can use this information during a patient interaction to help determine what should happen next.

Notable, for example, builds AI agents that interact with patients through voice, SMS, and web channels while connecting directly to EHR systems for scheduling, referrals, and patient outreach.

PatientNow provides another example in the medical aesthetics and elective-care market. Following its 2025 acquisition of Recura, the company described its evolution from a healthcare "system of record" toward a "system of action," connecting practice-management information with AI-powered communications and appointment booking.

Consider the different roles involved in a patient interaction:

- A communications platform may know that someone called and route the call.
- A conversational AI system may understand that the caller wants to reschedule.
- The healthcare application must determine which appointment is involved, what changes are permitted, and how to complete the transaction.
- The system of record provides the information needed to make those decisions.
- The workflow coordinates the steps needed to carry out the action.
## AI and the Architecture of Action

As AI agents become more capable, another question emerges: How much of the workflow should AI itself handle?

Modern AI systems can do more than interpret language. They can reason about requests, select tools, coordinate operations, and propose or execute actions. These advances are making some workflow orchestration tasks easier to implement.

However, reliable business transactions still require enforceable application controls.

A useful architectural principle is:

**AI handles ambiguity. Application logic governs action.**

AI can interpret requests, evaluate alternatives, and coordinate workflow steps. The application's controls determine which actions are permitted, how changes are committed, and how outcomes are verified.

In the appointment example, AI might identify a suitable alternative and prepare the scheduling change. The application's controls must ensure that the appointment belongs to the correct patient, the doctor and time are appropriate, and the transaction is valid. They must also verify that the appointment change was completed successfully and handle any errors that occur during the scheduling workflow.

These controls may reside in application software, AI services, or external systems, depending on the workflow. Regardless of where they are implemented, they need to be explicit and enforceable rather than relying solely on the AI model's judgment.

This is especially important in healthcare, where routine administrative tasks may involve sensitive information, clinical requirements, or decisions that require human involvement.

## The Technology Layers Are Converging

Several developments suggest that the boundaries among communications infrastructure, AI applications, workflow capabilities, and systems of record are becoming less distinct.

Communications infrastructure providers are extending their platforms toward AI integration and orchestration.

In September 2026, Alianza introduced Crux, which the company describes as an orchestration and intelligence control plane for communications service providers. Crux is designed to connect communications sessions with AI applications while coordinating network context, identity, consent, and policy controls.

Contact-center platforms are also expanding into specialized workflows. In March 2026, Talkdesk announced agentic AI capabilities for complex healthcare scheduling, connecting patient interactions with scheduling requirements specific to individual doctors, clinical protocols, and backend systems.

Meanwhile, healthcare AI application providers such as Notable are combining conversational interfaces with EHR integration and workflow execution. Systems-of-record vendors such as PatientNow are adding AI-driven communications and operational capabilities to their platforms.

These developments do not necessarily mean that the vendors are becoming direct competitors. They may partner, integrate their products, or offer complementary capabilities.

What we are seeing is a growing intersection of four capabilities: communications, AI interpretation, workflow control, and authoritative business systems.

As these technologies converge, the boundaries of responsibility are changing as well.

Communications infrastructure can provide capabilities such as caller identity, consent, and session-level policy enforcement. AI platforms can interpret requests and coordinate operations. Business applications and systems of record provide the domain context, authority, and transaction controls needed to carry out those requests.

These functions may be distributed across different platforms, but they must work together to complete the workflow.

I believe this convergence suggests that application differentiation may increasingly depend on how effectively these technologies work together to produce reliable business outcomes.

## The Product Is What Happens Next

The developments in healthcare AI suggest that the value of a conversational application depends on more than the quality of its interactions.

A successful workflow might produce a confirmed appointment, an authorized transaction, or a properly handled exception requiring human involvement. These outcomes depend on the application's ability to use the right information, apply the necessary controls, and complete the work reliably.

As conversational technology becomes more accessible, the ability to turn understanding into operational action is becoming an important part of application value.

**As voice becomes infrastructure, workflow becomes the differentiator.**

---

## Sources and Publication Notes

Selected primary sources documenting the company announcements and product descriptions referenced in this commentary. Company statements are cited as evidence of product direction, not as independent verification of performance.

- [Talkdesk — Complex specialty scheduling announcement, March 5, 2026](https://www.talkdesk.com/news-and-press/press-releases/complex-scheduling/)
- [Notable — Contact Center / AI Agents and EHR-connected workflows](https://www.notablehealth.com/operational-groups/access)
- [PatientNow — Company history and 2025 Recura acquisition](https://www.patientnow.com/company/about)
- [Alianza — Crux announcement, September 2026](https://www.alianza.com/whats-new/alianza-crux-powering-cognitive-communications/)

## Publication Information

Author: Johnny Lai  
Publication: Technology & Market Commentary  
Edition: Version 1.0  ·  October 2026  
Copyright © 2026 Johnny Lai. All rights reserved.  
This commentary expresses the author’s interpretation of public technology and market developments. Company and product names are the trademarks of their respective owners. References to companies do not imply affiliation or endorsement.

## About the Author

Johnny Lai is a technology product and platform leader with extensive experience in enterprise software, communications platforms, cloud infrastructure, and emerging technologies. His career spans large enterprises, startups, and consulting, including leadership roles at AT&T, Verizon, Lucent Technologies Bell Laboratories, and Meritechnic.

His recent work focuses on AI-enabled applications, workflow orchestration, and the integration of AI with enterprise systems and business processes. He also serves as an Adjunct Lecturer in Computer Science at Hunter College (CUNY), where he teaches advanced web development and entrepreneurship.

His writing draws on his experience in technology architecture, product development, and applied AI to examine emerging technology and market developments.
