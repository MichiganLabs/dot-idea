# MichiganLabs Android Studio/IntelliJ Project file templates

Copy the contents of this repo into the `.idea/` folder of your new project **after importing it**. Every time you re-import an IntelliJ project, the `.idea` folder will be wiped out and reset to defaults. If you copy in the `.idea` template before importing your project, it will overwrite the settings.

If you make changes to project level settings to enable new inspections, change style guidelines, etc, be sure to update this repo with your changes.

This repo can be tracked as a git submodule so it can be synced between this repo and other projects easily:

```bash
git submodule add https://code.michiganlabs.com/MichiganLabs/dot-idea.git .idea
```

To update the settings in your project, run:

```bash
git submodule foreach git pull
```

Then commit the changes to `.gitmodules`

## Making Changes
Any changes you make to the project settings from the IntelliJ preferences which are saved to "project scope" will be
saved to these config files. Please remember to submit those changes back to this repo with an MR.
