# cool-git-stuff
A repo containing cool code to make Gitting very fun on Ubuntu (And other, it's worth a try)

## WHAT DO I DO WITH THIS STUFF?
Glad you asked! Just copy the stuff and use it as attached configuration in your .bashrc file (I hope you know what that is, cuz I don't, I just know what it does! ^^>).

Now, **.bashrc** is a file that, among other stuff and among other files, loads a configuration that your shell will be using during that session. For instance, if you would like to automatically define a variable named `my_name_plus_cool` you would define it within that file using `export my_name_plus_cool=cool$USER`. once you login again to your shell or source the .bashrc file using `source /home/$USER/.bashrc` you will have access to that variable, for example print it out to the screen using `echo $my_name_plus_cool`. This is only a simple example, imagine all the other cool stuff you could do, like define complex function and have access to them.

Talking about functions, in this repo, you will have a bunch .sh files that expose function, variables... that do cool stuff with **Git**. So obviously, you will need Git installed on your system. I'm sure you'll figure out how to install Git on your system (If you already dare do cool stuff with shell scripting).

Okay, go ahead, clone this repo, or individually download files and start using them. It might be best to check them first, you know, never download shell scripts and use them immediately. After having checked them, put them in your user directory (`/home/$USER`) then add reference to them in your **.bashrc** file by adding the line `source <whatever the file name that you have just downloaded, checked and put in your user directory>` at the very end of your **.bashrc** file.

I guess that's that. I can't say other generic stuff about this repo, I don't exactly know what will be published here as features as I will be pushing as I figure out new ideas and turn them into scripts.

See ya!
