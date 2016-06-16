To set up these Bash commands on your Mac, here's the process I suggest:
* Create a `bin` directory in your home directory.
* In your home directory, add the following lines to your `.profile` or `.bash_profile` file:

        # Creates environment variable for the path to your new tools
        export TOOLS="$HOME/bin"

        # Loads tools on every command line session
        export PATH=$PATH:$TOOLS
* Clone this repository in the new `bin` directory.
