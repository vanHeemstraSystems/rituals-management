# 200 - Setup your Git Repository

We'll be using [Visual Studio Code](https://code.visualstudio.com/) as a Git Client.

1. On Mac and iOS, run NotePlan at least once, so the notes folder gets created.

2. Set the Sync on Mac and iOS inside NotePlan to "No Sync" in the preferences.

- On iPad inside NotePlan choose Settings. From Sync choose "Turn Off Sync".
- On Mac (Mini) inside NotePlan choose Preferences . From Sync choose "No Sync".

3. Open Finder at NotePlan’s sync folder (```Macintosh HD > Users > [your user name] > Library > Containers > NotePlan 3 > Data > Library > Application Support > co.noteplan.NotePlan3```) and delete the directory named "co.noteplan.NotePlan3", backing up any files, if you already have some. **Note**: GitHub can't create a new repository in an existing folder.

4. In Visual Studio Code or any other git app, create a new repository pointing to the ".../Application Support" directory where we deleted NotePlan’s sync folder and name the folder "co.noteplan.NotePlan3".

Local Path: ```/Users/[your user name]/Library/Containers/NotePlan 3/Data/Library/Application Support```
Repository Name: ```co.noteplan.NotePlan3```

**Note**: Make sure to change the user name ```[your user name]``` in your local path to your Mac's username, if you copy it from above. 

5. Copy any files back which you have backed up before.

6. Now we need to ignore some folders from syncing, otherwise, they will create conflicts continuously. Ignore the folder ```Caches```, ```com.microsoft.appcenter```, and files ending with ```.log```. You can do this in the Visual Studio Code in a new ```.gitignore``` file in the root of the repository:

```
Caches*
*.log
com.microsoft.appcenter*
```
.gitignore

7. Make your first push on Mac (here: Mac Mini)! First, you need to commit by entering a message (such as "Initial Commit") and click Commit.

8. On iOS (here; iPad), close NotePlan and open ```NotePlan```’s folder in the Files app in "On my iPhone/iPad" and delete any files in there, so they don’t cause issues. **Warning**: make sure the files on your Mac are the most recent files. If not copy them over to your Mac from your iOS device.

9. Setup [Working Copy](https://apps.apple.com/us/app/working-copy-git-client/id896694807) the same on iOS (here: iPad). Tap on the plus icon at the top left and then on "Link external directory" (**Note**: This requires purchasing the Pro version of Working Copy) and select ```NotePlan```’s folder in "On my iPad/iPhone".

10. Add the previous repository we have created on your Mac to this folder and pull changes. First go to your GitHub account in Safari and open the newly created repo, then click on the green "Code" button to copy the "SSH" link.

11. Then on iOS (here: iPad), in the ```Working Copy``` app, tap on the synced NotePlan folder you have added before, now called "Documents", tap at the top on "Repository", then tap on "Add Remote" at the bottom.

Into the URL field, paste or type the SSH URL we have copied before from the GitHub repository website.

- If you are already authenticated with GitHub, you can tap on "Test". 
- If you are **not** authenticated, you can tap at the top right on "Save", go back to the first screen in ```Working Copy``` and open the preferences by tapping on the preferences icon top left. Inside the preferences, select "SSH Keys". Tap on the key which should be already available. ```WorkingCopy@xxxxxxxxx```.

Then tap on "Connect with GitHub" and enter your GitHub username, password, etc.

11. Now you are ready. You can make changes either on Mac and iOS and then you have to manually commit and push the changes. On the other device, you will need to pull changes every time. If you don’t do this, you will run into conflicts, which you can resolve with the git apps easily.

## Your First Sync

1. To make your first sync, change a file on your Mac by entering something for example in today's note. 

2. Then open GitHub Desktop and you should see some files on the left under "changes".

As before, enter something into the summary field below and hit "Commit", then "Push origin" at the top right.

3. Now open Working Copy on iOS, select your repository called "Documents" and hit the Working Copy button at the bottom right. From here you can also commit, push and pull. Since we want to pull the changes we did on Mac, we need to select "Pull" and this should download the changes.

4. If you make a change in NotePlan on iOS, you can go back to Working Copy, tap on the floating button bottom right again and this time commit your changes by selecting all files which are listed, hitting "Commit" (type a summary if needed) and then hit "Push".
5. On Mac, you can open GitHub Desktop and pull the changes.

## Resolving Conflicts

You might run into a conflict if you have changed a note on two different devices without pushing/pulling first. In this case Working Copy or GitHub Desktop will notify you of the conflict and you need to resolve it by selecting the version you want to keep or trying to merge it. Then you commit this selection and pull again.