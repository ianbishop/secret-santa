*Automated Secret Santa*

The Automated Secret Santa program takes in a csv of email addresses and template email to send, randomizes the email addresses, and sends off the secret santa details to the receipient.

Example usage:

./secret-santa.py -e emails -a attachment -H smtp.gmail.com -P 587 -u myusername -p mypassword

* `emails` CSV file of format Name,email (e.g. Ian Bishop,bishop14@gmail.com)
* `attachment` HTML template where `${santa}` is the santa, `${receipient}` is their match
