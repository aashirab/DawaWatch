# DawaWatch
An AI-powered platform for medicine batch tracking and cold-chain risk monitoring.

DawaWatch is a concept for helping medicine-supply teams identify potential storage, transport, and expiry risks at the batch level. Its current browser prototype, ColdChain Guard, lets users register medicine batches, review storage guidance, track expiry and estimated shelf life, and sort stock using First Expired, First Out (FEFO).
Project status: Prototype / proof of concept. The included HTML demonstrates a rule-based tracker. Machine-learning predictions, live IoT sensor feeds, automated shipment tracking, and verified external medicine databases are proposed future capabilities---not implemented in the current HTML file.
Technology
- HTML
- CSS
- Vanilla JavaScript
- Browser localStorage for saving batch entries

  Run locally
No build step or package installation is required for the current
prototype.
1. Download or clone this repository.
2. Open ColdChain Guard – Medicine spoilage tracker(1).html in a modern browser.
3. Add a batch and explore the Tracker, FEFO dispatch order, and Medicine rules tabs.

Future scope
- Integrate temperature and humidity sensors or data loggers for
  real-time monitoring.
- Add shipment/location tracking and delay information.
- Use QR codes for batch identification and traceability.
- Connect to a verified medicine-information source for storage requirements.
- Evaluate machine-learning models for prioritising alerts, using appropriate validated data.
- Build a multi-user dashboard and secure backend for shared inventory records.
- Keep longer-term storage-condition and batch histories for review.

Contributing
Suggestions and improvements are welcome. Useful next steps include adding input validation, automated tests for expiry calculations, a verified source for medicine storage rules, and a backend for shared records.
Disclaimer
DawaWatch / ColdChain Guard is an educational prototype. Its built-in medicine data and risk indicators are not validated for operational use. Verify all medicine-specific requirements with authoritative sources and qualified personnel before making storage, quarantine, or dispatch decisions.

   
