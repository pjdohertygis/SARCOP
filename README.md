# Wide Area Search Templates
(Formerly known as SARandFirstResponderSurvey)
This is a GitHub page for recording and resolving issues related to the Wide Area Search Templates for waypoints (points), tracklogs (lines), and assignments / incident areas (polygons). It includes a Survey123 zip file that you can download and use as a template to deploy a field application for recording the location of human interactions, hazards, damage surveys, and operation support.

You may also want to see our Structure Specialist templates here https://github.com/pjdohertygis/StSTemplates

# Links
- Hub Site https://sargis-napsg.hub.arcgis.com/
- Sandbox https://experience.arcgis.com/experience/9051a07ffd1947bbb395e9f9b4088f85/
- YouTube Playlist https://www.youtube.com/playlist?list=PLtl2mJ4_4VyAZCLUQXzia_9bPVRV91co4

# Version 8 Highlights 
We are now using a "one stop shop" approach where teams only need to access one link for all apps. In addition, from the Battlecard Page you only need to access one QR Code. Survey123 and FieldMaps are accessible from an app launched in the QuickCapture project.

## New Waypoints
- Preliminary Damage Assessment Categories - These are the categories used in the preliminary damage assessment (PDA) process. This is related to the observed damage, not the structural risk. This will help expedite disaster declaration and recovery processes for State and Local government.  https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/64 
- Human Remains Detected https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/56 
- Pet Evacuation https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/11 
- Lifeline Report https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/98 
- Searched  https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/77 
[only used during Recon / Hasty when a damage assessment is not being done, vehicle search]

## Additional Modifications
- Squad Number vs Squad Leader Name https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/66
- Comments fields reduced to a single field (General, Hazard, Human Interaction, etc.) https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/83 
- Removing Operational Period from interface (still in data) https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/87 
- Remove Follow-up Form icon since this is accounted for with the follow-up workflow https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/97 
- Removed Other (not assigned) waypoint https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/100
- Original Waypoint Field - records the initial waypoint to keep a record when it changes (e.g., Survivor detected --> Rescue) https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/106
- Moved the Photo Button higher up in the form https://github.com/pjdohertygis/WideAreaSearchTemplates/issues/78 

To see all proposed changes and their status, see https://github.com/pjdohertygis/WideAreaSearchTemplates/issues?q=is%3Aissue+milestone%3A%22Version+8.0%22

# Version 7 Highlights
## Changes to the XLSForm / Template (by SARWG)
- Added A Follow-Up Question for taking action on waypoints like Victim Detected, Victim Confirmed, Human Remains Detected, or any other waypoints that would typically require further action. https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/31
- Added A Review Status Question for vetting data before being sent to external stakeholders. https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/7
- Removed the Patient Identification field because it was causing technical issues on the backend (prevented deploying multiple surveys from the source feature layer) and it was also a potential policy issue for agencies that cannot collect PII without prohibitive restrictions. https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/16
- Added an Operational Period field (optional).  https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/13

See the closed issues page for a full list https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues?q=is%3Aissue+is%3Aclosed

## Updates to Survey123 App (by Esri)
- You can now use Standard Map Types via Settings (See Doc) and this allows you to see the web map from the basemap switcher. Now you can see your waypoints collected, tracklines, and assignments areas, etc. You must enable standard map types. This can be selected in either Survey123 Connect and the Survey123 field app by opening Settings > Map and selecting Standard.
