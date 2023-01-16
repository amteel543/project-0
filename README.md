# UOCIS322 - Project 0

Trivial project to exercise version control, turn-in, and other mechanisms
for CIS 322.

Please read this **thoroughly** before starting.

## Setting up Git

### Windows Users

If you're using Windows, please refer to this [link](https://www.howtogeek.com/336775/how-to-enable-and-use-windows-10s-built-in-ssh-commands/) for instructions on enabling SSH.

### Setting up keys

In order to access your GitHub repositories and commit changes,
you have to set up an SSH key first. This is more secure and convenient than using your GitHub username and password every time. Read more 
[here](https://docs.github.com/en/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent).

### Adding keys

Once you've created your keys and added them to your GitHub account, use the following command to add the key:
```
ssh-add path/to/.ssh/ssh_filename
Author: Aaron Teel

Contact Address: ateel@uoregon.edu

This software copies the credentials.ini file into the "hello" directory, then executes the python file within the "hello" directory to print "Hello world" to the console
