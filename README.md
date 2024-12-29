## Usage of this mod template

paste the contents of your mod (`mod.ini` and accompanying mod folders) directly into the topmost folder of this repository such that `mod.ini` exists in the same location as `changelog.md`, etc.

when importing your `mod.ini` and mod folders, copy the paths of everything from the file import menu (Drag files here) after your files have been uploaded but not added to the repo, then
paste this into `mod_files.txt` and remove the starting backward slash and replace it with `add `.

```
add mod.ini
add data000/CameraFactorEnemy.bxm
add data000/CameraFactorGeneral.bxm
add data000/CameraFactorStandard.bxm
```

Edit `changelog.md` to reflect the changelog of your mod. Use template's placeholder text as a guide for the markdown and general formatting.
Edit `mod_version.ini` to update the `VersionString` and `DownloadSizeString` to show the new version and it's approximate mod filesize.

to link your mod with your repo, open any of the files inside the repo and open it as Raw, then copy the site link and remove the file from the site (so that it reduces down to the main path of the repository and not the file that you used to get the repo link) and then add it to your HMM/RMM mod via the 'Update Server' field. Re-import your `mod.ini` OR edit it from inside the repo along with the new version number.

> [!CAUTION]
> `https://raw.githubusercontent.com/BlaixenU/procamera-server/refs/heads/main/changelog.md`

> [!TIP]
> ` https://raw.githubusercontent.com/BlaixenU/procamera-server/refs/heads/main/ `

