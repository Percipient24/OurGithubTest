Cloning a Repository from GitHub in SourceTree
==============================================

Click the Clone/New button. This opens the Clone / Add / Create Repository dialog box.

Be on the Clone Repository tab.

Click the globe button on the far right (the tooltip says "Browse hosted projects"). This opens the Edit Hosting Account dialog box.

Change the Hosting Service to GitHub.
Type in your GitHub username.
Click Change Password... and enter your GitHub password. (remembering is fine, it will forget when you log off anyway)
The default values for the rest of the items are fine.
Click OK. This will bring up the Hosted Account List dialog box.
Click Close. This will bring up the Hosted Repositories dialog box.

Select the repository you'd like to clone from the list.
Click OK.

This is the most important part!
--------------------------------

If the Destination Path starts with \\banner.main.ad.rit.edu, you're going to have a bad time.

Click the ... (Browse) button and navigate to D:\Users\abc1234, create a folder there with the same name as the repository, and select that new folder as the target path.

Click Clone.

This is the other important part!
---------------------------------

Because these files are on the D:\ drive, they will not follow you from computer to computer, and may be erased overnight/overweekend. This is ok, because we should always be Committing while we're working and Pushing when we're finished. **If you forget to Push, you run the risk of losing your files if the D:\ drive is wiped.**
