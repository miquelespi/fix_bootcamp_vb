# fix_bootcamp_vb

Example of how to fix your bootcamp partiotion on OS X on an automated manner so that virtualbox can run it anytime.

Setup:
- Add execution privileges to the shell script 
```
$ chmod +x fix-virtualbox.sh
```
- Modify the setup_sample.workflow with automator so that it contains you root access password.
- Save it as an application.
- Include it in the Login items under "System Perferences" > "User accounts".
- Restart you machine and you're good to go!
