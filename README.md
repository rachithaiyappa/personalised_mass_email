# personalised_mass_email

This script was written in October 2019 when I was a part of the team hosting the course 'Principles of Science' at Ashoka University, Sonepat, India. 

More details about the course: rachithaiyappa.github.io/teaching

This script was used to send some personalised feedback and grades/marks to each student of the course. The idea was to automate this process instead of having to manually email each student of the class.

This script has been tested for a gmail account (sender-side).
Please note, for this to work, your (sender's) gmail account must allow 'Less secure apps' (https://devanswers.co/allow-less-secure-apps-access-gmail-account/). No changes need to be made to the receiver's account.

An example of the excel sheet from which the data is being read from has also been attached.

PS: I'm not sure of how well messages and login credentials are encrypted (via smptlib) when the script creates a connection to the sender's gmail account. Here are the doc files (https://docs.python.org/2/library/smtplib.html)
