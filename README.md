## System Flow

RAW INPUT  
↓  
Deterministic Translation Engine  
↓  
Structured Output Schema
## Example Workflow

Raw Input:

Injector alarm triggered during trauma CT scan.
System halted injection mid-sequence.
Power cycle required twice before scan could resume.

↓

Structured Output:

{
  "device": "CT Injector",
  "context": "Trauma CT scan",
  "event": "Alarm triggered during injection sequence",
  "mitigation_attempted": "Power cycle (2)",
  "status": "Needs engineering review",
  "priority": "High"
}# ops-translation-engine
