# Welcome!
This is a launcher coded in java for XPlataformer which is also one of my creations, SO...
why did i create this launcher? because i want to make people not have to go directly to github EVERY update that there is.
so yeah :) it's just a launcher.
for you to be able to make a launcher of your fork of XPlataformer, i'm gonna explain how the launcher downloads, installs,
and verifies the game file.
# How the launcher works
first up,
we gotta understand that the launcher is just a RC1 XPlataformer java converted into a launcher.
so it maybe has the same bugs on the GUI... but don't worry! if a bug is found, you just gotta report it! i will go on and fix it if possible.
now the real thing comes:
- first, the launcher when launched (what an intresting thing) it fetches the versions with an available compiled .jar, and it show it on it's UI
- second, when pressing the download selected version, the magic starts.
**How the download Process works**
  - first, the Launcher downloads and verifies the SHA256 of the downloaded jar with the SHA256 on the github page of the downloaded version
  - then it proceeds to download a levels.zip (this is because of a bug on the game that i don't want to fix now)
  - that levels.zip is unzipped and put on the XPlataformer's jar that was downloaded. (it goes to /XPLATAFORMERJARS/version/)
  - then it proceeds to just update the list and everything is ok!
# Anything weird on the launcher?
just that it still has the game fisics on it... since it's built over the original XPlataformer RC1 source code.
# Where do i download manually XPlataformer jars?
uhh idk why i put this here but here: https://github.com/ripipod/XPlataformer
