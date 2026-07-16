**Project Title**

Agentic IT Helpdesk Assistant using UiPath Agent Builder, Data Fabric and RPA Workflows

Project Description:  Designed and implemented an Agentic AI-based IT Helpdesk Automation solution using UiPath Agent Builder, Studio Web, Data Fabric, and RPA Workflows. Built a knowledge-grounded support agent capable of resolving common IT issues, classifying requests, invoking automated workflows, generating unique RITM ticket identifiers, storing requests in Data Fabric, and escalating unresolved incidents through a governed ticketing process. Demonstrated AI-driven decision-making, workflow orchestration, enterprise data management, and human-in-the-loop support automation.

**Problem Statement**:
Organizations receive thousands of employee IT support requests.

Password resets,
VPN issues,
Software installation,
Access requests,
Outlook issues,
Hardware support,

Most requests are repetitive, causing high IT support workload and slower response times. This solution implements an Agentic AI Helpdesk Assistant that attempts self-resolution first and creates tickets only when automatic resolution is not possible.

Solution Architecture:
Employee -> UiPath Agent -> Knowledge Base Search -> Issue Classification -> 
Self-Service Resolution -> Resolved? -> Yes ----------------→ Close Request ↓ No -> Collect Required Details -> Ticket Generation Workflow -> Data Fabric -> Generate RITM Ticket -> Return Ticket Number -> Employee
