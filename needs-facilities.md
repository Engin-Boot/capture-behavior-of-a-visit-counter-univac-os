# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given The system works good with sensor
  
  When The data from system shows daily update
  
  Then The report shows the data in an api format
  or in web(html) format or in graphical format

Scenario: Alert when seating capacity is full

  Given The system sensor works good
  
  When The data in report reaches the "Max" value
  for the hour.
  
  Then The system will inform the staff working the
  specific department
