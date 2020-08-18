# Visit-counter for a Facilities Manager

# Scenario: Report visitor trends during a week of operation

  Given The system works good with sensor
  
  When The data from system shows daily update
  
  Then the Facilities Manager able to see number of visitors
  on each day of week in the form of a graph according to
  the various categories.

# Scenario: Alert when seating capacity is full

  Given The system sensor works good and there are availability
  of seats
  
  When The data in report reaches the "Max" value
  for the hour.
  
  Then The system will inform the staff working the
  specific department through alert notification.
