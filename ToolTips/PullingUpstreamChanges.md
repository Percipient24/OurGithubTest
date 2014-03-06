Pulling Upstream Changes
========================

When you Fetch or Pull, by default, you are getting changes from **your** remote repository.

Sometimes, though, we'll want to get the changes from the *IGME/102-2135-01* repository. (Like when I've added a new ICE and you need to get the working files).

To do this, we need to add another repository to our "Remotes" in SourceTree.

**1.** Open SourceTree, and open your local repository.

**2.** Click on the Settings gear, located on the far far right of the toolbar.

**3.** On the "Remotes" tab, click the Add button.

**4.** In the "Remote details" dialog box:
* *Remote name:* upstream
* *URL / Path:* https://github.com/IGME/102-2135-01.git
* *Host Type:* GitHub
* *Host Root URL:* https://www.github.com
* *Username:* [your username]

**5.** Click OK.

**6.** Click OK.

You should now see 'upstream' appear beneath 'origin' in the first collumn of your repo window.

To Actually Pull Changes from Upstream
--------------------------------------

**1.** Right-click on 'upstream' and select 'Pull from upstream.'

**2.** In the "Pull" dialog box:
* The defaults are fine.
* *Remote branch to pull:* master (Click Refresh if necessary!)

**3.** Click OK.

**4.** When this is done, you'll probably want to *Push* the changes.