# Setting up

To start working on a project, the first step is to clone its repository and set up your local development environment. The first part is always the same - just use the `git clone` command which you will have learned about by now. Some projects may not require any special set up and those that do handle it in different ways. In HYPED, we have a `setup.sh` script which configures some things for you. Other things are configured/installed when you first try to compile the code. Some setup (like installing Git, VS Code, or WSL) is handled by giving you instructions to follow manually.

### More detail 

The `setup.sh` script registers git hooks in your local repo. These are scripts that run every time you perform some git action (e.g. commit or push). In the main HYPED repo, for example, they will not allow you to commit code that does not compile. 

## Step 1: Setting up

Please clone this repository now. Once you have it, execute the `setup.sh` script. You will need to do the same before you start working on the main HYPED repo.

### :keyboard: Activity: Specific description

1. Clone this repository
2. `cd` into the cloned repo
3. Run `bash setup.sh`

<hr>
<h3 align="center">Watch below this comment for my response</h3>

> _Sometimes I respond too fast for the page to update! If you perform an expected action and don't see a response from me, wait a few seconds and refresh the page for your next steps._
