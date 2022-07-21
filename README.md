# README

Installing Ruby on Rails (for Mac):

1. Install Homebrew: Homebrew (Links to an external site.) is a package manager for the Mac that makes installing new software very easy. You can install this tool with this terminal command:

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

Once it is installed, run "brew doctor" to see if there are any issues that need to be fixed.

2. Install Git. You may already have Git on your machine; you can easily check with the command git --versionand see if this gives you a response. If not, there is an official page for installing git at https://git-scm.com/book/en/v2/Getting-Started-Installing-Git (Links to an external site.). Go to the page and follow the instructions for Mac. Verify this was installed by running git from the terminal.

3. Install Ruby Version Manager: RVM(https://rvm.io/) is a nice tool to switch between multiple versions of Ruby. Install it with the following command:

\curl -sSL https://get.rvm.io | bash -s stable

Once it is installed, either restart your terminal or use the command source ... that RVM gives you at the end of the installation to get RVM active. Then install Ruby 2.6.9 with the command: rvm install 2.6.9

4. Install rails: gem install rails -v=5.2.6 --no-document

5. Test your installation: We will build a simple test app using the command line. Open up terminal and switch to the Documents directory by typing cd Documents or whatever directory you would like to create a test app. After that, create the rails app with the following commands.

rails new testapp
(you'll see a bunch of output)
cd testapp
rails server

You can test that this works by going to localhost:3000 in your internet browser and seeing a basic rails splash page.

How to run the application:

1. To start the development server, in terminal run: rails server
2. Open up your browser and go to localhost:3000 to view the application.
3. To access the database type: rails db

Connecting to MySQL Database:
1. Follow the database.yml file.
2. And make sure your Gem file has mysql


