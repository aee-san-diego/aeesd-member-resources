# What "Open Source" Actually Means

The concept of open source originated in the software world. In the 1980s, the free software movement, led by figures like Richard Stallman and the GNU Project, established the principle that software source code should be freely available for anyone to inspect, modify, and distribute. The term "open source" was formalized in the late 1990s to describe software whose source code is publicly accessible under licenses that permit modification and redistribution.

Open source software has become enormously successful in certain domains. Linux powers much of the internet's infrastructure. Apache web servers, Python programming language, and countless other open source projects form the backbone of modern computing. The model works because communities of developers contribute improvements, bugs get identified and fixed quickly through public scrutiny, and users aren't locked into a single vendor's vision or pricing.

## The Pneumatic Controls Era and "Pure" Open Systems

Before digital controls, buildings relied on [[Pneumatic Control Systems]] using compressed air to actuate dampers, valves, and other mechanical equipment. Pneumatic systems were based on universal physical principles and standard mechanical components—pipes, fittings, pressure regulators, damper actuators. Any contractor who understood compressed air systems and basic control logic could install, maintain, modify, and troubleshoot these systems.

This is why people sometimes joke that pneumatic controls represent the purest form of "open source" building automation. While there was no source code to be open, pneumatic systems embodied a kind of openness that building owners still long for: systems based on well-understood principles, using standard components, serviceable by any competent contractor, with no proprietary software or vendor lock-in.

Of course, pneumatic controls had significant limitations—slow response times, difficulty implementing complex sequences, limited monitoring capabilities, and high maintenance requirements as seals and components aged. The move to digital controls brought enormous improvements in precision, functionality, and energy efficiency, but it also introduced the proprietary systems and vendor dependencies that concern building owners today.

## Why Modern BAS Aren't Open Source

When digital building controls emerged in the 1970s and 1980s, manufacturers made substantial investments in developing their systems. They invested (and continue to invest) in hardware design, embedded software, communication protocols, control algorithms, user interfaces, and programming tools. These investments are recovered through product sales and ongoing service relationships.

This is the same model followed by most commercial software companies. Microsoft Windows is not open source. Apple's operating systems are not open source. Most commercial software, from enterprise systems to specialized industrial controls, is proprietary. Companies protect their source code as intellectual property, both to recoup development costs and to maintain competitive advantages.

Building automation manufacturers are no exception. Johnson Controls, Siemens, Honeywell, Trane, and others maintain proprietary control over their:

- Controller firmware and embedded software
- Programming and configuration tools
- System architecture and database structures
- Graphical user interfaces
- Advanced control algorithms and optimization routines

Even when these manufacturers offer products that communicate via [[BAS Communication Protocols|open protocols]] like BACnet, the underlying software remains proprietary. ==You can read and write data points using the standardized protocol, but you cannot access or modify the source code that runs on the controllers or that powers the system software.==

## Open Source Projects in Building Controls

Some open source building automation projects do exist, though they haven't achieved significant commercial market share in traditional building automation systems.

- **VOLTTRON**, developed by Pacific Northwest National Laboratory (PNNL), is an open source platform for building energy management and distributed sensing and control. It's designed for research and advanced applications like demand response and grid integration.

- Various **open source SCADA platforms** and industrial control systems sometimes get applied to building automation, particularly in academic or research settings.

- The **home automation and IoT space** has spawned numerous open source projects—Home Assistant, OpenHAB, and others—that some building owners and operators have experimented with for smaller facilities or specific applications.

However, these open source options face significant barriers to widespread commercial adoption: limited technical support infrastructure, fewer out-of-the-box integrations with major HVAC equipment, steeper learning curves for typical building operations staff, and limited availability of contractors trained to work with these platforms. Most building owners ultimately choose commercial BAS platforms with established support networks, even if it means accepting proprietary systems.

> [!tip]
> When building owners express interest in "open source" controls, they're often articulating a desire for the kind of openness that pneumatic systems once offered: vendor independence, competitive service markets, and freedom from lock-in. But actual open source software is rarely what they need or want, and it's not what commercial BAS manufacturers offer, even when their products support open protocols.

---
# See Also
- [[Building Automation Systems]]
- [[BAS Communication Protocols]]
- [[Procuring Building Automation Systems]]