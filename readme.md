# Vaccine spotter for India



Vaccine spotter is a simple tool for tracking the availability of Covid vaccines in any state in India
It uses the api from COWIN site to monitor for vaccine availability and sent an immediate email to user.
 ✨

## Instructions

- Search for district id in provided csv file
- Run in the terminal and monitor the vaccine availability
- Sent email to email address set by user immediately when there is vaccines available

 

## Installation

Vaccine-spotter requires python3 to run

Set email details, district_id in the script 

``` sh 
# For gmail, the lesssecureapps connection needs to be turned on for email to work :  https://myaccount.google.com/lesssecureapps
# need to change the smpt address for other mail providers

email_user = 'test@gmail.com'
email_password = '<password>'

sent_from = email_user
to = ['<to_email@gmail.com>']

# time gap
minutes = 1


Run the script after setting the values 
```sh
python vaccine_spotter.py

```
No data is collected from users . The script is open to verify
 
## Development

Want to contribute? Great!


