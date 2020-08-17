# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given The system restarts again with log file
  
  When The foot fall counter records the data
  
  Then The system must "add" the count from
  log file

Scenario: Reconcile counts if the sensor is offline for a while

  Given The system have the log file
  
  When The entry book must have filled  
  
  Then The system is entered manually
