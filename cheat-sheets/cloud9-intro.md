## Running App in Cloud9

Things that are important to know about your environment.

That setup will work for you regardless of your computer setup. There are a couple of small adjustments you’ll need to make in the process of building the applications that the most tutorials will suggest. Here’s what you need to know:

* If you use this setup you will use Cloud9’s IDE setup instead of a native text editor on your computer like sublime text.
* If instructions ever tell you to run a command that starts with `rails server`, you’ll always need to run the command: `rails s -b $IP -p $PORT`, instead.
* Instead of visiting your app using localhost, you will use the trick this article suggests to preview your app.
* Everytime you open Cloud9, you will need to start the postgres server with: sudo `/etc/initi.d/postgres start`.
* After using Cloud9 for a long period of time, you may run out of disk space, and it may prompt you to upgrade. You will not need to upgrade. To reclaim the disk space, run the following command:
  > sudo rm -rf /home/ubuntu/.local/share/heroku/tmp

Overall, Cloud9 is a really great development environment, and in a lot of cases using that is a lot smoother than working with other alternative installation setups.