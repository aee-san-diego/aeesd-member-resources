# History of BAS Communication Protocols

Building Automation Systems emerged in the 1970s and 1980s as manufacturers developed digital controls to replace [[Pneumatic Control Systems]]. Each manufacturer—Johnson Controls, Honeywell, Siemens, and others—developed their own proprietary communication protocols. This wasn't malicious; it was the natural state of technology development before industry-wide standards existed. Each company was solving the same problem independently, using different approaches to enable their controllers, sensors, and operator interfaces to communicate.

By the late 1980s and early 1990s, the building industry recognized that proprietary systems created problems: building owners were locked into single vendors for expansion and service, integration between different building systems was difficult or impossible, and competition was limited. Two major standardization efforts emerged to address this:

1. LonWorks (LON), developed by Echelon Corporation in the early 1990s, offered a complete networking platform with its own hardware and software architecture. It gained significant traction, particularly in Europe and in specific applications like lighting control.
2. BACnet (Building Automation and Control networks), developed by [[ASHRAE]] starting in 1987 and released as a standard in 1995, took a different approach. Rather than dictating specific hardware, BACnet defined how building automation devices should communicate—the language they should speak—while allowing flexibility in implementation.

Over time, BACnet became the dominant open protocol in North America. Several factors contributed to this: ASHRAE's credibility and lack of commercial interest (versus Echelon's proprietary ownership of LON), BACnet's flexibility in implementation, and its focus on HVAC and building automation specifically rather than general industrial control. BACnet became ANSI/ASHRAE Standard 135, then an ISO standard, cementing its position as the international standard for building automation.

Today, when building owners specify "open protocol," they almost universally mean BACnet in North America.

# What "Open Protocol" Actually Means (and Common Misinterpretations)

An open protocol is a standardized communication language that is publicly documented and not controlled by a single manufacturer. BACnet specifies how devices exchange information: how a controller asks a sensor for a temperature reading, how trend data is structured, how alarms are communicated.

**Here's what open protocol does mean:**

- Multiple manufacturers can make devices that communicate using the standard
- The building owner is not technically locked into one manufacturer's ecosystem for basic communication
- Different manufacturers' devices can theoretically exchange data on the same network

**Here's what open protocol does NOT mean:**

- All BACnet devices are interchangeable or plug-and-play
- Any contractor can seamlessly add any manufacturer's equipment to any existing system
- You should mix manufacturers' equipment freely within a single system
- The system software, graphics, programming tools, or user interface are "open"

The most common misinterpretation is that "open protocol" equals "mix and match hardware." Building owners often believe that specifying BACnet means they can have Contractor A install Trane controllers, Contractor B add Johnson Controls VAV boxes, and Contractor C integrate it all seamlessly. This is theoretically possible but practically problematic.

Another critical misunderstanding: owners confuse "open protocol" with "[[Open Source]]". The BACnet standard is open, but each manufacturer's implementation, programming software, graphics packages, and system architecture remain proprietary.

# Technical Details of the Protocols

To understand why "open protocol" doesn't mean "plug and play," it helps to understand what these protocols actually standardize.

**BACnet defines:**

- **Objects and Properties**: Standard ways to represent building automation concepts (analog inputs, binary outputs, schedules, etc.)
- **Services**: Standard commands devices use to communicate (read property, write property, subscribe to change of value, etc.)
- **Network layers**: How data moves across different network types (IP, MS/TP, Ethernet, etc.)
- **Interoperability levels**: BACnet devices declare their conformance through PICS (Protocol Implementation Conformance Statements) and BIBBs (BACnet Interoperability Building Blocks)

**BACnet does NOT define:**

- How controllers are programmed (each manufacturer has proprietary programming tools)
- User interface design or graphics
- Database structure or naming conventions
- Specific hardware specifications
- Advanced features beyond basic communication

This is why two BACnet-compliant controllers from different manufacturers can see each other's data points, but you typically wouldn't want to mix them in a single coordinated system. They speak the same language at a basic level but may have very different dialects, capabilities, and programming paradigms.

LonWorks (LON) took a more prescriptive approach, defining not just communication but also network topology and hardware specifications. While this created tighter integration among LON devices, it also required proprietary hardware components.

Modbus, an older protocol from the industrial automation world, is sometimes encountered in building systems, particularly when integrating industrial equipment or legacy systems. Modbus is simpler than BACnet but lacks many building-specific features.

## Today's Common BAS Protocols

**BACnet/IP** is now the dominant standard for new building automation systems in North America. Most major manufacturers—Johnson Controls, Siemens, Honeywell, Trane, Carrier, Delta Controls, Reliable Controls, and many others—offer comprehensive BACnet/IP product lines. Building codes and standards (including California Title 24) often require BACnet compatibility.

**BACnet MS/TP** (Master-Slave/Token-Passing) remains common for field-level devices like VAV controllers and sensor networks, running over simpler RS-485 wiring rather than Ethernet.

> [!NOTE]
> [[Tridium]] (Niagara Framework) is a bit different from the others because it's not a protocol - it's a software platform/framework that can communicate using multiple protocols (BACnet, Modbus, LON, and many others). It's protocol-agnostic middleware that sits between field devices and the user interface. Tridium is often used as an integration platform, particularly in complex buildings with equipment from multiple manufacturers or in situations requiring a unified front-end for diverse systems.

**LonWorks** still exists in installed systems, particularly in Europe and in lighting control applications, but has declined significantly in market share for new HVAC control installations.

**Modbus** persists for integrating specific equipment—chillers, boilers, generators, meters—into building automation systems, particularly when interfacing with industrial-grade equipment.

**Proprietary protocols** haven't disappeared. Many manufacturers offer both open protocol product lines and proprietary system lines, sometimes with the proprietary systems offering advanced features or tighter integration at the cost of vendor lock-in.

The critical insight: major BAS manufacturers offer multiple product lines. Johnson Controls makes both BACnet-compliant systems and proprietary systems. The same is true for Siemens, Honeywell, and others. ==Specifying "open protocol" doesn't disqualify any major manufacturer—it narrows down which of their product lines they'll propose.== This is fundamentally different from how most building owners think about the specification.

---
# See Also
- [[Building Automation Systems]]
- [[BAS Communication Protocols]]
- [[Open Source]]
- [[Procuring Building Automation Systems]]