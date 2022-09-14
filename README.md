# Prison_Architect_Mod_Files
This is the main.dat file unpacked from the Prison Architect game. These are the files the devs have made available for modding. The reason for uploading the files here is to keep track of changes between patches, because as we all know not all changes make it into the patch notes.

I don't really mod, so this isn't the place for questions about it. I spent a lot of time learning and really dislike changes that aren't in patch notes so I decided to upload the files here to keep track of changes myself.

## How To Use
### 1. First go to the $_Data_Compare Folder 
![Picture of main folder with an arrow point towards Data Compare folder](https://i.imgur.com/DBDtXBz.png)




### 2. In there, click the History button 
![Arrow pointing towards History Button](https://i.imgur.com/JVwVM0r.png)

### 3. Click any update that you want to compare.
![Clicking Gangs update](https://i.imgur.com/1DQYk0Q.png)

### 4. Congratulations! You now have the power to spy on Paradox with me to make sure we know everything they're changing that could affect mods!
![View of update changes](https://i.imgur.com/Tc881Zu.png)

## Downloading the Updated or Past Files
Since I don't really mod nor play PrisonArchitect, my updates may be sporadic so I have to sometimes download old files. PA doesn't allow you to download old versions through Steam so I have to use a different method. Since I have ADHD, I know I'm going to keep forgetting my method and having to Google so I'm writing the steps I take here.

### 1. Go to [PA's SteamDB page]([https://www.example.com](https://steamdb.info/app/233450/depots/)).

### 2. Click the depot you're interested in, I chose PC Content.
![Pc Content Depot](https://i.imgur.com/wF42ngo.png)

### 3. Click Manifests.
![Manifests Link](https://i.imgur.com/H72VhYX.png)

### 4. This is every update as it arrived on Steam, not it's actual release date so there might be mismatches with what you are looking for. Keep track of the Manifest ID.
![Arrow pointing to manifest id](https://i.imgur.com/cHmCRYs.png)

### 5. Now go to the [Steam Console](steam://nav/console), now using the App id: 233450, Depot ID (this is PC Contents): 233451, and the manifest id of the update we want, we can download using the following syntax: 
`download_depot <appid> <depotid> [<target manifestid>] [<delta manifestid>] [<depot flags filter>] : download a single depot`

That's the entire syntax, but honestly you only need: `download_depot 233450 233451 [<target manifestid>]`

Note: After entering the command, steam doesn't notify you that it's begun downloading. Don't worry, it's downloading! It'll notify you were the files are after download is complete.
