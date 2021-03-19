# Practices

- 34 practices, 15 are covered
- (*) marked on knowing level is required (blank if recall level is required)
- General Management Practices
- Service Management Practices
- Technical Management Practices

---

## Continual Improvement (knowing level)

    recurring org activity performed at all levels to ensure that an org's performance continually meeets the stakeholder's expectations

- applies to SVS in its entirety
- includes
    - ITIL continual improvement model
    - improve service value chain activity
    - **continual improvement practice**
        - supports day-to-day efforts
        - should be small team to handle this
- can be used as high-level guide to support improvement initiatives
- puts strong focus on customer value
- ensures improvement efforts can be linked back to org's vision
- supports an iterative approach to improvement

### continual improvement model

1. what is the vision? - business vision, mission, goals, and objectives
2. where are we know? - perform baseline assessments
3. where do we want to be? - defined measurable targets
4. how do we get there? - define the implementation plan
5. take action - execute improvement actions
6. did we get there? - evaluate metrics and KPIs
7. how do we keep the momentum going? - and back to 1

### the practice itself

    it is the development of improv-related methods and techniques and the propagation of a continual improvement culture across the organization, in alignment with the organization's overall strategy

key activities
- encourage continual improvement across the org
- secure time and budget
- identify and log improv opportunities
- assess and prioritize improv opp
- make business cases for improv action
- plan and implement improv
- measure and evaluate improv results
- coordinate improv activities across the org
-

    the practice is integral to the development and maintenance of every other practice as well as to the complete lifecycle of all services and the SVS itself

---

## Information Security Management (recall level)    

    Purpose is to protect the information needed by the org to conduct its business. Includes understanding and managing risks to the confidentiality, integrity, and availability of information

the required security is established my means of policies, processess, behaviors, risk management, and controls, which must maintain a balance between:

- prevention
- detection
- correction

- interact with every other practice
- processes and procedures include:
    - incident management process
    - risk management process
    - control review and audit process
    - event management
    - procedures for tests 

---

## Relationship Management (recall level)
    purpose is to establish and nurture the links between the organization and its stakeholders at strategic and tactical levels
> identification, analysis, monitoring and continual improvement

impacts much more planning than other SVC acitivities

---

## Supplier Management (recall level)

    purpose is to ensure that org's suppliers and their performances are managed appropriately to support the **seamless provision** of quality products and services

### Central activities:
- creating single point of visibility and control to ensure consistency
- maintaining a supplier strategy, policy, and contract management information
- negotiating and agreeing contracts and arrangements
- managing relationships and contracts with internal and external suppliers
- managing supplier performance

>the supplier strategy defines the org's plan for how it will leverage the contribution of suppliers in the achievement of its overall service management strategy

### Different types of supplier relationships:
- insourcing
- outsourcing
- single source/partnership
- multisourcing

> a service integrator is recommended to manage all relationships

### the organization should evaluate and select suppliers based on:

- importance and impact of the value of the service provided to the business by the supplier
- risk associated with using the service
- cost of the service and its provision

### Activities

- supplier planning
- evaluation of supplier and contracts
- supplier and contract negotiation
- supplier categorization
    - strategic
    - tactical
    - commodity
- supplier and contract management
- warranty management
    - activate warranty based on performance
- performance management
    - track and monitor key measures
- contract renewal or termination

---

## Change enablement

    purpose is maximize the number of successfull IT changes by ensuring that risks have been property assessed, authorizing changes to proceed, and managing the change schedule

scope includes:
- all it infra
- apps
- docs
- processes
- supplier relationships

> all changes should be assessed by people who are able to understand the risks and the expected benefits

> organizational change is people knowledge, while change enablement refers to products and services

### types

- standard changes (routine in acco)
    - low risk
    - pre authorized
    - fully documented
- normal changes
    - need to be scheduled, assessed and authorized
- emergency changes
    - must be implemented as soon as possible
    - should have same tests and documenation

---

## Incident Management

    purpose is to minimize the negative impact of incidents by restoring normal service operation as quickly as possible

- log and manage every incident to ensure that it is resolved in time and meets expectations of the customer and user
- agree, document, and communicate target resolution times to ensure that expectations are realistic
- prioritize based on agreed classification to ensure that incidents with the highest business impact are resolved first
- store information in a suitable tools
- update the progress on a timely basis

### Contributes on
- high
    - engage 
    - deliver support
- medium
    - design and transition
    - obtain/build
    - improve
- zero
    - plan

---

## IT Asset Management (recall)

    purpose is to plan and manage the complete lifecycle of all IT assets to help the organization to:

- maximize value
- control costs
- manage risks
- supporte decicion-making about purchase, re-use, retirement, and disposable of assets
- meet regulatory and contractual requirements

```
The scope inclues all software, hardware, networking, cloud services, and client devices. May include non-IT or IoT assets such as buildings or information.
```

### Types
- IT asset management (ITAM)
    - equipment and infra
- Software asset management (SAM)
    - management, control, protection throughout all stages of software lifecycle

### Activities
- hardware assets must be labelled and for clear identification
- software assets must be protected from unlawful copying (unlicensed use)
- Cloud-based assets must be assigned to specific products or groups so that the costs can be maanged
- Client assets must be assigned to individuals who take responsibility for their care
- Define, popuplate, and maitain the asset register in terms of structure and content, and the storage facilities for assets and related media
- Control the asset lifecycle in collab with other practices and record all changes made to assets
- provide current and historical data, reports, and support to other practices about IT assets
- Audit assets, related media, and conformity and drive corrective and preventive improvements to deal with the detected issues

### Contribution
- high
    - obtain/build
- medium
    - plan
    - deliver and support
- low 
    - engage
    - improve

---

## Monitoring and Event Management (recall)
    
    purpose is to systematically observe services and service components, and record and report the selected changes of state, identified as events

### Activities
- identify what services, systems, CIs, or other service components should be monitored and how
- implement and maitaing monitoring
- defined which changes of state will be treated as events (aand what event it is)    
- policies for how each type of event should be handle
- implement processess and automations to operationalize all that


### Contribution
- high
    - deliver and support
- medium
    - design and transition
    - improve
- low
    - engage
    - obtain/build

---

## Problem Management (know)

    purpose is reduce the likelihood and impact of incidents by identifying actual and potential causes of incidents, and manages workarounds and known errors

**Problem** is a cause, or potential cause, of one or more incidents

**Known error** is a problem that has been analyzed bu has not been resolved

Phases:
1. Problem Identification
    - Be proactive, find trends in incidents
2. Problem Control
    - Analyze
    - Document
3. Error Control
    - Manage the *known errors*
    - Identify permanent solution (create change request)
    - Identifying the change, does not mean it will be implemented
    - Evaluate costs and risks to approve (or not) the change

When a problem cannot be resolved quickly, it is often useful to find and document a workaround for future incidents.
- Workarounds are documented in problem records.
- This can be done at any state and it does not need to wait for the analysis to be complete.

### Contribution
- high
    - deliver and support
    - **improve**
- medium
    - engage
        - customers may want to be envolved
- low
    - design and transition
    - obtain/build

---

## Release Management (recall)

    Purpose is to make new and changed services and features available for use. Is a version of service or other configuration item, or a collection of configuration items, that is made available for use.

Traditional vs Agile/DevOps
- single task, small tasks

### Contribution
- high 
    - design and transition
- medium
    - obtain/build
    - deliver and support
    - plan
- low
    - improve
    - engage

---

## Service Configuration Management (recall)

    Purpose is ensure that accurate and reliable information about the configuration aof services, and the CIs that support them, is available when and where it is needed

Identify and control how CIs contribute to an IT service.
For Asset management, cost/value is focused, here is how assets interacts and contribute.

### Contribution
- high
    - design and transition
    - obtain/build
- medium
    - deliver and support
    - improve
- low
    - engage
    - plan

---

## Service Desk (know - depth)
    Purpose is capture demand for incident resolution and service requests. It should also be entry point and single point of contact for the serice provider with all its users.

Service desks provide a clear path for users to report issues, queries and requests.

Channels: 
- phone calls
- walk-in service desks
- service portals and mobile apps
- text and social media messaging
- chat
- public and corporate social media
- email

Technologies:
- intelligent telephony systems
- workflow systems
- workforce management
- knowledge base
- call recording and quality control
- remote access tools
- dashboard and monitoring tools
- configuration management systems

The face to interact. Empathetic link. Holistic picture is important. Soft skills.

### Contribution
- high
    - engage
    - deliver and support
- medium
    - design and transition
    - improve
- low
    - obtain/build

---

## Service Level Management (know)

    Purpose is set clear business-based targets for service levels, and ensure dleivery of services is properly assessed, monitored, and managed against these targets

- establishes a shared view of services and target service levels
- ensures that orgs meet the levels by collecting ana analysing metrics
- perform service reviews to meet the needs
- captures and reports issues

### Service Level Agreement (SLA)

    is a documented agreement between provider and customer

- must be related to a service 
- must reflect an agreement
- should relate to defined outcomes and not operational metrics
- must be simply written and easy to understand and use for all parties

SLA Watermelon effect (green otuside, for provider, red inside, for customer).

**Engagement** is required to understand and confirm the actual ongoing needs and requirements of customers.

**Listening** is important as a relationship-building and trust-building activity, to show customers that they are valued and understood.

analyze info from number of sources, including:
- customer engagement
- customer feedback
- operational metrics
- business metrics

### Contribution
- high
    - plan
    - engage
- medium
    - design and transition
    - obtain/build
    - deliver and support
    - improve

---

## Service Request Management (know)

    Purpose is support the agreed quality of a service by handling all pre-defined, user-initiated service requests in an effective and user-friendly manner

includes:
- request for a service delivery action
- request for information
- request for provision of a resource or service
- request for access to a resource or service
- feedback, compliments, and complaints

guidelines
- standard and automated as possible
- policies should be established reducing approvals
- expectations of fulfilment tiems should be clear
- opportuinitioes for improv should be identified and implemented to produce faster fulfilment times
- policies and workflows for doc should be included

### Contribution
- high
    - engage
    - deliver and support
- medium
    - design and transition
    - obtain/build
- low
    - improve
- zero
    - plan

---

## Deployment Management
    Purpose is move new or changed hardware, software, doc, processess, or any other component to live envs (also staging)

- Distinct approaches
    - phased deployment
    - continuous delivery
    - big bang deployment
    - pul deployment

### Contribution
- high
    - design and transition
    - obtain/build
- low
    - improve
- zero
    - plan
    - engage
    - deliver and support

---

# Takeaways

- practices are divided into categories
