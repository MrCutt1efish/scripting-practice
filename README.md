# scripting-practice
To install:

Make the scripting directory
>sudo mkdir /usr/local/bin/mine

Add it to the path variable
>export PATH=/usr/local/bin/mine:$PATH

Move the downloads to the mine directory
>sudo mv */Downloads/scripting /usr/local/bin/mine
>rm /usr/local/bin/mine/scripting

Change its permissions
>sudo chmod -R u+x /usr/local/bin/mine
