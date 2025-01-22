# CDDA-Restored-Weapons
Add back cut weapons
 I am unsure how common or rare the spawns will be. Hopefully its on the rare side.

 Github Pr file contains the weapons added back and a link to the PRs where they were removed.


The base game obsoletion_and_migration_0.I file containing the weapons likely needs to be tweaked. I beleive not doing so will end up replacing the readded items. There is a pruned migration_items.json uploaded that should be placed in and overwrite ...\data\json\obsoletion_and_migration_0.I

However, this will need to be done everytime you update game and you'll want to use something like winmerge to compare the changes in the files since new things will likely be added to the migration_items.json that you probably don't want to remove.
