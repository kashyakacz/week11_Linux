# week11_Linux
#  Install script
1. Clone script from GitHub repo to local machine and file
2. Go into your directory where the repo is saved
3. Change remote URL to any URL of your liking

# Run weather script
1. You can run the weather script by typing the command:
`cat weatherfile`

# Run service file
1. Type the command
`sudo systemctl enable weath.service`
this will enable the command
2. Then type
`sudo systemctl status weath.service`
to view the status of the service file and if it ran

#Run timer file
1. Type the command
`sudo systemctl enable weath.timer`
will enable the timer with the service file for the weather script
2. Type
`sudp system ctl status weath.service`
to view the timer and how the script runs hourly.
3. You can change the timer on the timer file to how you want it by typing the command:
`sudo vim weath.timer'
4. Next to OnUnitActivSec= you can change the seconds.
5. Save the file by pressing the Esc key and typing :wq
6. Run the file and check if the changes worked by following steps 1-2
