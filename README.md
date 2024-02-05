# SOL PROCTOR INSTRUCTIONS

## Overview:
Create an automated scheduling system for SOL testing proctors, **based on teacher planning periods, testing schedule roation, and room capabilities**.

## Input Lists:
- **List 1: Teachers**:
- -  Teacher Name
- - Planning Period
  - SPED status (True/False) - Boolean
 - **List 2: Schedule**:
 - - Session (Date/Period)
   - Location
   - Population
   - SPED Room (True/False)
Output:
- Session
- Location
- Population
- Sped Room
- Examiner
- Proctor
- Proctor
- Proctor  
Data:
Historical data provided by the user, specifically the May 2022 Locations 3-day by subject document and the May 2022 Proctors document.  
## System Workflow:
**System matches students with test examiners and proctors based on the provided data.**
**The system does not schedule students**; they are assumed to be already assigned to rooms.
Matchmaking is done based on room capacity and the number of proctors required.
