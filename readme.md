##`mikrotik OS v6
Iteration Over PPP Secrets: Loops through each PPP secret/user, retrieves the expiration date from the comment field, validates its format, converts it to numeric format, and compares it with today's date to take appropriate actions (disabling/enabling users). Do nothing for expired users if they are already disabled.

##Note:- PPPoE user comment date format "mmm/dd/yyyy" Example- jul/15/2024
