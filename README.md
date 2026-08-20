# nexo-agentforce-ftth
Autonomous AI Agent built on Salesforce Agentforce for FTTH network diagnostics and remote ONT remediation.
# NEXO: Autonomous AI Agent for FTTH Incident Resolution

Autonomous resolution architecture built on **Salesforce Agentforce**, designed to automate Customer Premises Equipment (ONT/Router) diagnostics and remote remediation for Telecommunications and FTTH (Fiber to the Home) providers.

---

## 🎯 Business Impact & Key Metrics
* **Industry Challenge:** Up to 35% of technical on-site dispatches (*truck rolls*) are triggered by minor ONT/Router desynchronizations.
* **Operational Cost Savings:** Eliminates unnecessary dispatch costs averaging ~$1,480 MXN (~$85 USD) per incident.
* **Resolution Speed:** Drastically reduces Mean Time to Resolution (MTTR) from 48 hours to under 2 minutes.

---

## 🏗️ Technical Architecture & Key Capabilities

1. **Deterministic Flow Logic & Identity Authentication:**  
   Enforces secure 4-digit PIN verification before triggering any backend execution or remote network resets.

2. **Backend Execution & Custom Data Modeling:**  
   Automates remote ONT diagnostic commands and persists real-time event logs directly into Salesforce custom objects (`Enlace_Fibra__c`) under system-level auditing (`EinsteinServiceAgent User`).

3. **Knowledge Retrieval (RAG):**  
   Contextual troubleshooting workflows grounded in structured telecommunications technical knowledge bases.

4. **Escalation & Safety Guardrails:**  
   Enforces strict execution limits and deterministic routing to Level 2 human network engineers upon physical layer degradation.

---

## 🛠️ Tech Stack & Author
* **Platform & Tools:** Salesforce Agentforce | Service Cloud | Flow Builder | Custom Objects & Fields
* **Architect / Author:** Irving Uriel Luna Sánchez
* **Focus:** Network & Cloud Infrastructure Trainee | CCNA Candidate (Nov 2026)
* **Project Status:** Top-tier technical evaluation (63.95/80) in the National Salesforce & ITF AI Challenge.
