# MyPet Editor Translations

Translations of the MyPet web editor ([MyPet-Configurator](https://github.com/MyPetORG/MyPet-Configurator)).
Please translate on the MyPet translation site, not by pull request:

* https://translation.mypet-plugin.com

## Branches
This repository follows the MyPet branch pipeline: `staging` → `alpha` → `main`.

* Pull requests (including Crowdin's) target `staging`, the default branch. They are squash-merged.
* `alpha` feeds the alpha editor and `main` the release editor; both are updated only by promotion PRs.
* A translation change that belongs to an editor or plugin change uses the same branch name as that PR and names it in the PR's **Siblings** section.

One-time manual step (owner): in Crowdin's GitHub integration for the editor project, set the branch to `staging`.
