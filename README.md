### Setup

To set up these Bash commands on your Mac, here's the process I suggest:
* Create a `bin` directory in your home directory.
* In your home directory, add the following lines to your `.profile` or `.bash_profile` file:

        # Creates environment variable for the path to your new tools
        export TOOLS="$HOME/bin"

        # Loads tools on every command line session
        export PATH=$PATH:$TOOLS
* Clone this repository in the new `bin` directory.
* Make sure you give yourself execute permissions on the Bash script files.

### Commands

* `landing`: creates a Bootstrap landing page. Asks you several questions to fill in specifics like title and contact email. The template was designed for myself (it uses my email by default), but it's easy to change the details manually.
* `babel-proj`: creates a Node project with Babel and ES 2015 transpiling set up. To transpile your source code in the `src` sub-directory, run `npm run build`.
