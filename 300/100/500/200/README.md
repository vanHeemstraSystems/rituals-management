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

7. Make your first push on Mac! First, you need to commit by entering a message (such as "Initial Commit") and click Commit.

MORE ...