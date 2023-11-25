Acunetix 23.7.230728157 Linux // pwn3rzs+cyberarsenal
web based web security assessment, one of the top scanners


Instructions

1. Install using the installer, like
       sudo ./acunetix_23.7.230728157_x64.sh
   during install you will choose your usename and password. note them for later.

2. Run our install.sh to have the cracking steps done for you, so you can
   get going faster and in theory there can be no mistakes!

3. configure your scan profiles and targets and go!


Notes

I wrote "acufix.py" for people who needed to use existing databases or for people
who had used improper cracks and got some of their hosts blocked and didn't
realize that is what the "limit exceeded" message meant - it meant you messed
up in the past so they stuck the fqdn in the local database and until it's 
cleared out even a correct crack wont work.  So, you can use acufix to set
all the hosts to good status, delete the trouble ones, or just wipe it all.


enjoy!
