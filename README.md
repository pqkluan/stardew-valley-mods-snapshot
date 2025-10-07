# Instruction

This is for my gold fish memory.

## How to update when the mod list changes

Once we add / update the mods using Vortex.
Open the mod staging folder located at:

```
C:\Users\pqkluan\AppData\Roaming\Vortex\stardewvalley\mods
```

Then stage the changes using git:

```
git add .
git commit -m "Update mod list"
git push
```

## How to use this repo (on the Steam Deck)

Since Vortex don't work with Stardew Valley on Steam Deck, we will need to manually add the mods to the game folder.

Open the game folder using Steam.
Pull the repo to your the folder:

```
git clone git@github.com:pqkluan/stardew-valley-mods-snapshot.git ./Mods
```

Make sure the final path looks like this:

```
*\steamapps\common\Stardew Valley\Mods
```

Then, whenever you want to update the mods, just run:

```
git pull

```

Inside the Mods folder.
