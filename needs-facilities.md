# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given The system works good with sensor
  
  When The report uses time to time update
  
  Then The report shows the data in web format
  or api format or sql.

Scenario: Alert when seating capacity is full

  Given The system sensor works good
  
  When The data in report reaches the "Max" value
  for the hour
  
  Then The system informs the staff working the 
  specific department
