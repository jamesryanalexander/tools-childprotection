# tools-childprotection
SubModule for LCATools - ChildProtection reporting tools (Logging/NCMEC etc).

### Files
* NCMECreporting.php - Form to fill out for takedowns of indecent images on WMF websites
* NCMECprocessing.php - Processing script to take information from NCMECreporting.php and report it to NCMEC (if needed) and log it internally.
* NCMECretract.php - Form to retract reports to NCMEC that were never completely submited (if report was already fully submited but be retracted directly with them).
* NCMECprocessingOldDebug.php - Old processing script kept around still for debugging.
* espsubmittal.xsd - NCMEC xsd scehema for their API.
