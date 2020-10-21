###SwitchSDSetup v.2

Start script with 'sudo /path/to/script/setup.sh' and navigate through the menus, it should be more or less self explanatory.
Once you configured everything, select "Save changes", this will write everything to the selected device.

The script supports installing l4t ubuntu, android oreo, up to 2 EmuMMCs, up to 2 Android installations (Android Oreo + Android Q, Android Q + Android Q).

To install Android Q, place tegra210-icosa.dtb and lineage-17.1-[date]-UNOFFICIAL-[model].zip or tegra210-icosa.dtb and system.img, vendor.img, boot.img in a directory and start the script from that directory (or, if you dont start the script from there, navigate to that directory on image selection)

Important: Android Q has not released yet, you will have to build it yourself, check out the switchroot discord for instructions.
Please to *NOT* ask for prebuilt images, it releases when it releases, which can be in a day, in a week or in a year.
If you want to install a second Android Q image, it has to be built with the files from Files/lineage.zip (extract to your source directory, overwrite existing files).

For questions, open an issue, ask via discord pm (Nautilus#8264) or ping me in the switchroot discord.

Feel free to report any issues or create pull requests (to clean up the script).

As always, im not responsible, if your switch ends up as paperweight, you overwrite your eMMC and dont have a backup or your house burns down.
