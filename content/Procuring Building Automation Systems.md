# Understanding What You're Really Trying to Solve

When building owners begin a BAS procurement, they often lead with technical specifications: "We want an open protocol system" or "We need BACnet compatibility." While these specifications aren't wrong, they're often proxies for underlying concerns that deserve direct attention.

> [!tip]
> **What building owners typically worry about:**
> 
> - Getting locked into a single contractor who can charge whatever they want
> - Being unable to get service when needed
> - Paying premium prices for parts and labor with no competitive alternatives
> - Being forced to replace an entire system because one vendor goes out of business or discontinues support
> - Losing control over their own building
> 
> These are legitimate business concerns. The question is whether the typical technical specifications actually address them—and whether they create new problems in the process.

## The Real Problem: Vendor Lock-in and Competition

The core concern in most BAS procurements is avoiding a situation where you're captive to a single vendor or contractor. Building owners have heard horror stories: a facility stuck with one controls contractor who knows they have no alternatives and prices accordingly, or a proprietary system that becomes unsupportable when the manufacturer exits the market.

**But here's the critical insight: specifying =="open protocol" doesn't automatically solve this problem.**==

> [!tip]
> You can have an open protocol system and still be effectively locked into one contractor if:
> 
> - They're the only local contractor competent with that manufacturer's specific implementation
> - They control the system server, graphics, and naming conventions
> - They've structured the installation in ways that make transition difficult
> - They hold institutional knowledge about the building that wasn't documented
> 
> Conversely, you can have a proprietary system with healthy competition if:
> 
> - Multiple qualified local contractors represent that manufacturer
> - Your contract terms protect against price gouging
> - Your staff understands the system well enough to evaluate contractor performance
> - You've maintained good documentation and system knowledge

==**The solution isn't primarily in the product specifications—it's in understanding your local market and structuring your procurement and contracts accordingly.**==

## Assessing Your Local Contractor Landscape

Before writing technical specifications, invest time in understanding who actually services BAS in your area:

**Key questions:**

- Which major BAS manufacturers have ==multiple qualified contractors== in your region?
- What is the reputation and financial stability of these contractors?
- Do any contractors have particularly deep expertise with your building type or specific technical requirements?
- Are there contractors who work across multiple manufacturers' platforms?
- What is the typical response time and service quality ==based on other building owners' experiences==?

This research shapes your procurement strategy more effectively than any protocol specification. If three reputable contractors in your area all work with Johnson Controls Metasys, that's a competitive market regardless of whether Metasys is your first choice on technical grounds. If only one struggling contractor supports a particular manufacturer locally, ==that's a lock-in risk even if the system is BACnet-compliant.==

> [!tip]
> **Talk to peer facilities.** Other building owners and facility managers in your area are your best source of information about contractor performance, pricing, and responsiveness. Your local AEE chapter, ASHRAE chapter, BOMA chapter, or similar professional organizations can facilitate these conversations.

## Understanding the Interoperability Reality

Many building owners assume that specifying open protocol means they can freely mix manufacturers' equipment or easily transition between contractors. The reality is more nuanced.

**Open protocol enables basic data exchange.** A BACnet-compliant controller from Manufacturer A can read temperature data from a sensor made by Manufacturer B, and a graphics package from Manufacturer C can display that data. This is valuable for integration—connecting your BAS to your energy management system, or integrating a specialty piece of equipment.

==Open protocol does not mean plug-and-play equipment or seamless contractor transitions.==

Here's why:

When you have a functioning BAS from a single manufacturer with coordinated programming, graphics, naming conventions, and sequences, that system represents significant engineering effort and institutional knowledge. If you add equipment from different manufacturers or bring in different contractors to work on different parts of the system, you face practical challenges:

**Who owns the system architecture?**

- Who controls the server and maintains backups?
- Who establishes and enforces naming conventions?
- Who manages graphics and user interface consistency?
- Who coordinates software updates and cybersecurity patches?

**Who handles integration and troubleshooting?**

- When something doesn't work, who is responsible?
- If three contractors have touched the system, how do you determine which one caused the problem or who should fix it?
- How do you prevent contractors from blaming each other instead of solving problems?

**What about warranties and support?**

- Manufacturers typically warranty their systems when installed as complete, coordinated packages
- Mixing equipment can void warranties or create gaps in coverage
- Technical support from manufacturers becomes complicated when they're troubleshooting integration with competitors' equipment

**How do you maintain institutional knowledge?**

- A single contractor working with a system over time develops deep knowledge of your specific installation, sequences, and quirks (and builds [[Relationships]] with facilities staff)
- Spreading work across multiple contractors dilutes this knowledge
- Documentation becomes even more critical but is often inadequate

> [!tip]
> This doesn't mean you should never have multiple contractors or integrate different manufacturers' equipment. It means you should do so deliberately, with clear delineation of responsibilities, strong documentation requirements, and realistic expectations about complexity and support.

**For most buildings, the better strategy is:**

- Select a primary system from one manufacturer with strong local support
- Use open protocols for integration points—connecting your BAS to metering equipment, specialty systems, or enterprise-level software
- Maintain flexibility through contract terms and contractor relationships rather than through equipment mixing

## Structuring Procurement and Contracts for Competition

If the goal is to avoid vendor lock-in and maintain competitive pricing, focus your procurement on business [[Relationships]] and contract terms, not just technical specifications.

**Key procurement elements:**

**Identify qualified contractors and their manufacturer relationships.** Your RFP should seek to understand:

- Which systems the contractor is authorized to sell and service
- ==Their technicians' training and certification levels==
- Their local service capacity and ==response times==
- ==Their references with similar facilities==

**Evaluate based on the complete package:** system capabilities, contractor competence, local support availability, and total cost of ownership—==not just initial price or protocol specifications.==

**Structure contracts to maintain competition:**

- Separate system installation from ongoing service when practical, allowing you to re-bid service competitively
- Include specific performance requirements: response times, resolution timeframes, key personnel qualifications
- Require comprehensive documentation and training for your staff
- Establish clear pricing structures for routine service, emergency service, and additions/modifications
- Include provisions for knowledge transfer if you change contractors

**Specify documentation requirements:**

- Complete as-built drawings and sequences of operation
- Points lists with consistent naming conventions
- Programming logic and graphics source files in formats your staff can access
- System architecture documentation
- Maintenance procedures and troubleshooting guides

Good documentation doesn't just help future contractors; it empowers your own staff to understand and manage the system effectively.

**Require training for your staff** as part of the installation contract. The more your team understands the system, the better they can evaluate contractor performance and avoid unnecessary service calls.

**Consider term limits with re-compete opportunities.** A three-to-five-year service contract with good performance metrics gives the contractor incentive to maintain quality while ensuring you're not locked in indefinitely.

## Open Source vs. Open Protocol vs. Open Architecture

These three terms often get conflated in BAS discussions, but they mean fundamentally different things:

**Open Source** refers to ==software whose source code is publicly available for inspection, modification, and redistribution==. As discussed in [[Open Source|our note on Open Source]], true open source BAS are rare in commercial applications. When manufacturers offer BACnet-compliant systems, the protocol may be open but their controller firmware, programming tools, and system software remain proprietary. Open source is not the same as open protocol, and ==building owners who ask for "open source controls" usually mean something else.==

**Open Protocol** means a standardized, publicly documented communication language (like BACnet) that allows devices from different manufacturers to exchange data. [[BAS Communication Protocols|open protocols]] enable interoperability at the communication layer. They allow different manufacturers' devices to share information on the same network and enable integration between systems. What open protocols don't provide: interchangeable hardware, unified programming tools, consistent user interfaces, or seamless multi-vendor operation. You can have an open protocol system that's still functionally single-vendor in how it operates and is maintained.

**Open Architecture** is a broader and somewhat ambiguous term. In building controls, it typically means a system design built on standard, non-proprietary components and interfaces—the modern equivalent of the openness that [[Pneumatic Control Systems]] once offered. An open architecture might use open protocols for communication, standard network infrastructure (Ethernet, IP), documented interfaces for integration, and modular design allowing components to be replaced or upgraded independently. However, "open architecture" has no precise technical definition, and vendors may use the term to describe systems that still contain substantial proprietary elements.

> [!tip]
> **What building owners usually want when they use these terms:** vendor independence, competitive service markets, and the ability to make changes without being held hostage to pricing or availability from a single source. The path to achieving these goals is rarely through equipment specifications demanding open source, open protocol, or open architecture. Instead, it comes from:
> 
> - Choosing systems with healthy local contractor ecosystems
> - Structuring contracts that maintain competition
> - Requiring comprehensive documentation
> - Building internal staff capability to understand and manage the system
> - Using open protocols strategically for integration points rather than assuming they solve vendor lock-in concerns

## Matching System Complexity to Organizational Capability

This consideration is important enough that we've dedicated a separate note to it (see: Owner Staff Capabilities), but it deserves mention in any procurement discussion.

The sophistication of the BAS you procure should match not just your building's technical needs but also your organization's realistic capability to manage it—both now and in the future.

**Consider:**

- Can your current staff operate the system, or just read it?
- Can they modify sequences and troubleshoot, or only call for service?
- What is your realistic hiring and retention outlook for technical staff?
- What level of external support will you need, and can you afford it sustainably?

A highly capable facilities team might thrive with a complex, flexible system that gives them extensive control. A team focused on corrective maintenance with high turnover might be better served with a simpler system from a manufacturer with robust local service support, even if it's less technically sophisticated on paper.

The wrong match—over-specifying complexity beyond your operational capacity—creates ongoing problems and often leads to systems that drift into poorly maintained states or become dependent on expensive external support.

## Making the Decision

Effective BAS procurement requires balancing multiple factors:

**Technical fit:** Does the system meet your building's control requirements?

**Local support ecosystem:** Who can install, service, and modify this system in your area, and what's their reputation?

**Organizational capability:** Can your team manage this system effectively given realistic staffing and resources?

**Business terms:** Do the contract terms protect you from lock-in while giving the contractor reasonable certainty?

**Total cost of ownership:** What will this system cost over 15-20 years, including service, upgrades, and eventual replacement?

The goal is not to find the perfect system on paper, but to find the combination of technology, contractor relationship, and business terms that will serve your building well over the long term. Often this means accepting some trade-offs—a less technically impressive system in exchange for better local support, or a proprietary system that three qualified contractors can service rather than an open protocol system with limited local expertise.

The most important insight: **your procurement specifications should reflect your local market reality and organizational needs, not abstract preferences about protocols or vendor neutrality.** Start with understanding who can actually support your building, then structure your technical specifications and contract terms accordingly.

---
# See Also
- [[Building Automation Systems]]
- [[Tips for Owners and Facility Managers]]