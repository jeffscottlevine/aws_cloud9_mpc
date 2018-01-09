# Introduction

I wanted to learn about the [Django](https://www.djangoproject.com/) web framework and I also wanted to get some experience using [AWS Cloud9](https://aws.amazon.com/cloud9/) but needed a good starting environment.   That led to the creation of this repo.   This repo contains the files associated with the Django polling tutorial that can be found at https://www.djangoproject.com/.  I decided to name this project, MyPollingCompany, hence the name "mpc." The repo currently supports the following platform: 

1. Amazon Linux 1 for the Cloud9 IDE on its own EC2 instance.

# Instructions for Building this with Amazon Linux 1 for the Cloud9 IDE on its own EC2 instance

1.  Create an AWS Cloud9 environment in its own instance, not an ssh instance. A t2.micro instance is good enough.
2.  Open the environment.
3.  Go to the existing terminal window or open up a new bash window.
4.  cd $HOME/environment
5.  git clone "the https URL from github"
6.  cd mpc
7.  ./amazon_linux1_cloud9_setup.sh
8.  Follow the instructions displayed at the conclusion of the script.
9.  When you are done, delete your AWS Cloud9 workspace so you no longer incur charges from AWS.

# Financial Considerations

1. There are costs for the AWS resources used by this repo.  You are responsible for all such costs.

# Notes

1. The files may contain multiple versions of content.  I did this so I could keep track of what changed throughout the tutorial.

2. I am usinmg MySQL for the backend.

# Security Considerations

1. This is a demo and is not built with strong security in mind.
2. The passwords are short and are generated with pwgen.
3. Passwords are used on command lines - a strong no no!
4. The Django secret key is generated by pwgen.

# Miscellaneous Files

1. Django.run - The AWS Cloud9 "runner" for Django.
2. requirements.txt - Used by "pip" to reinstall the required python modules.

# Attribution

1. The background image is from Kelli Tungay and came from https://unsplash.com/photos/RAVdOqWXPvg.
