#Developmental Journal
### Guiding Goal :If a hospital staff member can't complete the verification in under one minute without asking for help, we've failed.

# Build Log

This document records the progress of Project Atlas from the initial idea through development and deployment.

The purpose of this log is to document decisions, milestones, challenges and lessons learned throughout the project.


## Day 1

Date:
2 July 2026

### Objective

Begin planning a healthcare verification platform that simplifies the collection of geotagged verification photographs.

### Problem Identified

Healthcare facility verification currently requires repeated explanations, follow-ups and manual collection of geotagged photographs, making the process slow and inefficient.

### Project Goal

Develop a web application that enables healthcare facilities to securely submit geotagged photographs in under one minute.

### Today's Progress

- Project idea finalized
- Project repository created
- Documentation structure created
- Mission statement defined
- MVP identified

### Next Goal

Design the first user interface and begin setting up the project architecture.

### Day 2 03/07/2026 : Designing the User Interface

Sentence to Grab User attention would be :
- Geo Verify / Verify your facility in under 1 minute

User is not required to create account

After User taps link this is what they should see :

- Health care Facility Verification

- Hello,

- Record Consults is conducting a verification of your healthcare facility.

- This process takes less than one minute.

- You will be asked to:

- Take 3 photographs [insert examples]
- NB :Example only — your photo does not need to look exactly like this.

- Share your location
- Your location and photographs will only be used for this verification request.

- [I'm Ready]

- [Start Verification] BUTTON

Ask for GPS at the start 
- User will HAVE to agree to turn GPS on otherwise it wont work.
- Explain to user : Location is only used to verify that the photographs were taken at the healthcare facility.

Verification will happen in 3 guided steps :
- Step 1/3 (Take photo of main entrance )
- Step 2/3 (Take photo of building signage )
- step 3/3 (Take photo of Reception/Exterior)

Success screen Then Appears 
- Verification Submitted
- Thank you.
- Your verification has been received successfully.
- Reference Number: RC-2026-000123

When can Users Fail?
- Failure 1
GPS denied.Solution? Explain why it's needed.
- Failure 2
Camera permission denied.Solution? Prompt them
- Failure 3 
Wrong photograph uploaded.Solution?
Show an example image. AT THE START 