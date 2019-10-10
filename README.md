# certloop
Single script to iterate over a given IP/subnet and check certificate validity.

Uses nmap to get subnet information.
Script is commented to an extent. 

Needs some updates, namely:
  -Timezone specific date issues (in case cert goes invalid same day in a different timezone)
  -Can be done with less redundancy in logic
  
