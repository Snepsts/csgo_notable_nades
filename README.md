# csgo_notable_nades
This repo is housing a [Notable](https://notable.app/) file base

If you're on Windows and don't have WSL, you should be very ashamed of yourself #1, but #2 you should set it up and use it here: https://learn.microsoft.com/en-us/windows/wsl/install

Just use the default Ubuntu, it's definitely a good choice for this

* Install notable
* Go to the notable install folder `~/.notable` (on Windows: `C:\Users\<your-username-here>\.notable`, on WSL console it's `/mnt/c/Users/<your-username-here>/.notable`, so to get there use the command `cd /mnt/c/Users/<your-username-here>/.notable`)
* Ensure there's no folders in it (delete `notes` and `attachment` if they exist), then run the following commands in WSL:
* `git init`
* `git remote add origin git@github.com:Snepsts/csgo_notable_nades.git`
* `git fetch`
* `git checkout -t origin/main`

In the future, if you want to update, go to the notable install folder again in console `.notable` and type `git pull`
