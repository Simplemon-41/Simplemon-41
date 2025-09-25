# 🏥 HealthChain Mockup

## Patient Data Flow

```mermaid
flowchart TD
    A[Patient Registration] --> B[Hospital A]
    B -->|Stores record| C[(Canton Network Blockchain)]
    C --> D[Hospital B]
    D -->|Authorized access| E[View Patient Data]

SCREEN (example)

+---------------------------------------+
|         HealthChain Registration       |
+---------------------------------------+
| Patient ID:    P-001                   |
| Name:          John Doe                |
| Birth Date:    1990-01-01              |
| Hospital:      Hospital A              |
+---------------------------------------+
| [ Save to Blockchain ]                 |
+---------------------------------------+


---

✅ This mockup shows how hospitals register patients and share data securely via Canton Network.

---

