This is a repository intended to include unused maps for the /tg/station codebase. Station maps, event maps, or unused ruins are all welcomed.
# Important Notes
* All maps provided here are provided as is, with no guarantee of working on the most up to date version of /tg/station code. Inclusion of a file noting the commit hash on which the map last worked would be appreciated.
* Only maps for the /tg/station codebase will be accepted.
* Update PRs for old maps are welcomed! However, if you are updating a map that we currently do not have in our repository, it is requested that you leave a version of the un-modified map for archival purposes.
* Any questions regarding the repository should be directed to one of /tg/'s maptainers, presently EOBGames (@emerald_or_bust), Maurukas (@kas72839), MMMiracles (@mmmiracles) and san7890 (@san7890). Pinging @tgstation/maptainers in the comments of your PR if it has not recieved any attention is of good help.

## Submodules

We provide a courtesy submodule of tgstation/tgstation code (https://github.com/tgstation/tgstation). If you find that you're having some issues (i.e.: the submodule is blank), try running this command in your repository's Command Line Interface:

```
git clone https://github.com/tgstation/tgstation.git --recursive
```

This may take a good chunk of time to install, unfortunately. However, from there, you can leverage all the tooling that the tgstation repository has to help with any potential uptainance (portmanteu of upkeep and maintainance) you may wish to do on any older map files we have here. We have an action that automatically updates this submodule every six hours when changes are present. 

Please always make certain that your submodule's commit is the same as the one on the repository (you should *never* update the submodule's commit in one of your PRs, just undo any changes your client may want to do to it). You may also reach out if you are having any issues with this system. We do not track any changes to this submodule beyond the commit version, so do feel free to edit it however you like.

If you need to update your branch, we _strongly_ recommend pulling our `main` branch.
However, if something fails (like the commentor bot posting an alert on your PR), try running the following commands and committing those changes, as it's likely something goofed out and is trying to push something it shouldn't.
```
git submodule update --init --recursive
git submodule update --recursive --remote
```
This is not recommended because it can latch onto a commit that the bot isn't accustomed to yet, so preventing any change to the `tgstation` submodule is always more ideal.

## Licensure

Since this repository derives a the great majority of its content from the /tg/station codebase, it is most proper to use the same license as the codebase. This is the GNU Affero General Public License v3.0. You can find a copy of this license in [the LICENSE file in the root of this repository](https://github.com/tgstation/map_depot/blob/main/LICENSE).

If a map is not derived from the /tg/station codebase, and is an original creation to be stored here for archival purposes or to be accessible to the public- the original author of the map file may elect to sublicense their map under a different license (as it is uniquely their work). The declaration of the desired license should be made in the PR that adds the map file to the repository, and stored in a visible location within the map-specific folder.
