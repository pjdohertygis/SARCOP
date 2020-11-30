# Wide Area Search Template 
(Formerly known as SARandFirstResponderSurvey)
This is a GitHub page for recording and resolving issues related to the SAR and First Responder Survey123 Template. This is a Survey123 zip file that you can download and use as a template to deploy a field application for recording the location of human interactions, hazards, damage surveys, and operation support.

# Links
- Survey123 Deployment Kit https://www.arcgis.com/home/item.html?id=ce2489e702604d578aa0fd8e10ab27ba
- Hub Site (new) https://sargis-napsg.hub.arcgis.com/
- Story Map https://napsg.maps.arcgis.com/apps/MapSeries/index.html?appid=71f7501c36d34dfdaf8a81b424806033
- YouTube Playlist https://www.youtube.com/playlist?list=PLtl2mJ4_4VyAZCLUQXzia_9bPVRV91co4

# Version 7 Highlights
## Changes to the XLSForm / Template (by SARWG)
- Added A Follow-Up Question for taking action on waypoints like Victim Detected, Victim Confirmed, Human Remains Detected, or any other waypoints that would typically require further action. https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/31
- Added A Review Status Question for vetting data before being sent to external stakeholders. https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/7
- Removed the Patient Identification field because it was causing technical issues on the backend (prevented deploying multiple surveys from the source feature layer) and it was also a potential policy issue for agencies that cannot collect PII without prohibitive restrictions. https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/16
- Added an Operational Period field (optional).  https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues/13

See the closed issues page for a full list https://github.com/pjdohertygis/SARandFirstResponderSurvey/issues?q=is%3Aissue+is%3Aclosed

## Updates to Survey123 App (by Esri)
- You can now use Standard Map Types via Settings (See Doc) and this allows you to see the web map from the basemap switcher. Now you can see your waypoints collected, tracklines, and assignments areas, etc. You must enable standard map types. This can be selected in either Survey123 Connect and the Survey123 field app by opening Settings > Map and selecting Standard.
