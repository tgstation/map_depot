This is a repository intended to include unused maps for the /tg/station codebase. Station maps, event maps, or unused ruins are all welcomed.
# Important Notes
* All maps provided here are provided as is, with no guarantee of working on the most up to date version of /tg/station code. Inclusion of a file noting the commit hash on which the map last worked would be appreciated.
* Only maps for the /tg/station codebase will be accepted.
* Update PRs for old maps are welcomed! However, if you are updating a map that we currently do not have in our repository, it is requested that you leave a version of the un-modified map for archival purposes.
* Any questions regarding the repository should be directed to one of /tg/'s maptainers, presently EOBGames (@Emerald_or_Bust#1314), Maurukas (@kas7#2839), and san7890 (@san7890#7890).

## Submodules

We provide a courtesy submodule of tgstation/tgstation code (https://github.com/tgstation/tgstation). If you find that you're having some issues (i.e.: the submodule is blank, try running this command in your repository's Command Line Interface:

`git clone https://github.com/tgstation/tgstation.git --recursive`

This may take a good chunk of time to install, unfortunately. However, from there, you can leverage all the tooling that the tgstation repository has to help with any potential uptainance (portmanteu of upkeep and maintainance) you may wish to do on any older map files we have here. We have an action that automatically updates this submodule every six hours when changes are present. 

Please always make certain that your submodule's commit is the same as the one on the repository (you should *never* update the submodule's commit in one of your PRs, just undo any changes your client may want to do to it). You may also reach out if you are having any issues with this system. We do not track any changes to this submodule beyond the commit version, so do feel free to edit it however you like.
