# Power on and power off
  
## Scenario: Power on the calculator

  Given The calculator is off
  When press "on/off"
  Then see screen sets to "zero"

## Scenario: Power off the calculator

Given The calculator is on
And screen displays either "zero" or previous calculations
When press "on/off"
Then screen sets to no display
