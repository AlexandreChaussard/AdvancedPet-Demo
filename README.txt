##############################################
#                                            #
#       Thank you for this download :) !     #
#                                            #
##############################################

---------------------------------
How to install the pet ?
---------------------------------

A. Get the Mythicmobs ready

1. Take the folder "Packs" in "MythicMobs/Packs" and put it inside the MythicMobs folder, fusionning it with the previous "Packs" folder if it already exists.
2. Reload MythicMobs with /mm r

B. Get the models ready

1. Get the .bbmodel file that you just bought, and put them into ModelEngine's blueprint folder
2. Reload ModelEngine using /meg reload

C. Add the pet to AdvancedPet

Get into the config.yml of AdvancedPet and add the following in the "Pets" section :

  Otter:
    MythicMob: NocsyOtter
    Permission: advancedpet.otter
    Mountable: false
    DespawnSkill: Nocsy_Otter_Despawn
    Distance: 3
    Icon:
      Name: §bOtter
      TextureBase64: ewogICJ0aW1lc3RhbXAiIDogMTYzMDgwNDc0OTY1NCwKICAicHJvZmlsZUlkIiA6ICIyMDA2NTVkMjMyYTE0MTc2OGIwNjQ0NWNkNTliNDg3NCIsCiAgInByb2ZpbGVOYW1lIiA6ICJGaWVzdHlCbHVlXyIsCiAgInNpZ25hdHVyZVJlcXVpcmVkIiA6IHRydWUsCiAgInRleHR1cmVzIiA6IHsKICAgICJTS0lOIiA6IHsKICAgICAgInVybCIgOiAiaHR0cDovL3RleHR1cmVzLm1pbmVjcmFmdC5uZXQvdGV4dHVyZS81MGNhOTNlYjYzYzQ3MGM3OGYxMGM3NmYyOTAyYWQ3ODNjNDI2NjUzOWFlNTA5NzIyZmNkOWIyZTIzMDBhOTIiCiAgICB9CiAgfQp9
      Description:
      - §7A cutie that will follow you everywhere !

Then get in game and make sure to reload the plugin with /advancedpet reload

D. Testing

Open the pet GUI with /advancedpet.
The otter should show up in the available pets if you have the advancedpet.otter permission.
Spawns the mob and try to interact with it with right click to test the petting animations.
Then despawn the pet from the pet GUI and check out the despawn animation.

E. Any issue ?

Do not hesitate to contact me on discord (Nocsy#4967). I'll answer as fast as I can.
You may also use the ticket system of mcmodels.net to address me an issue as it will keep a track of it.

C. Have fun !!