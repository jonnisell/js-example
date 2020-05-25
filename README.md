# js-example
Första JS exemplet

## Getting started
To get started with this repo you clone the code from this repo onto your own computer. You'll need what's called a "local copy" 
to run the source code on your machine

1. Install Git by following the instructions on this link: [Atlassian](https://www.atlassian.com/git/tutorials/install-git) Use the 
_Git for Mac installer_
2. Issue a git command in the terminal application on the mac by doing `git clone https://github.com/jonnisell/js-example.git`
The URL is a reference to this repo in Git terms

Now that you have the code on your machine you can run it. To do this we need a Python webserver.

3. In the folder where you've downloaded the code issue this command:
`python -m http.server 8000`  
It means that Python will set up a webserver that will serve the content of the folder on port 8000
4. Now you should be able to view the webpage in a browser (Chrome or Firefox) by typing *http://localhost:8000* in the address bar
