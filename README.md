Project Title

Agentic IT Helpdesk Assistant using UiPath Agent Builder, Data Fabric and RPA Workflows

Problem Statement

Organizations receive thousands of employee IT support requests relating to:

Password resets
VPN issues
Software installation
Access requests
Outlook issues
Hardware support

Most requests are repetitive, causing high IT support workload and slower response times.

This solution implements an Agentic AI Helpdesk Assistant that attempts self-resolution first and creates tickets only when automatic resolution is not possible.

Solution Architecture:
Employee -> UiPath Agent -> Knowledge Base Search -> Issue Classification -> 
Self-Service Resolution -> Resolved? -> Yes ----------------→ Close Request ↓ No -> Collect Required Details -> Ticket Generation Workflow -> Data Fabric -> Generate RITM Ticket -> Return Ticket Number -> Employee
