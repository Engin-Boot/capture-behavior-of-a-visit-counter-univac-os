# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given the system sensor working good
  
  When The Facilities managers provides the data of people 
  visiting hosiptal
  
  Then the data is averages to number of beds available and 
  the number of beds are using for treatment

Scenario: Compute parking slots to reserve for visiting specialists

  Given the system sensor in parking area is
  working properly
  
  When the facilities managers provide the data of people
  visiting hosiptal
  
  Then reserving the parking area for visiting specialists by
  by informating the specific department to do so.
