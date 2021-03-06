# AnimalFarm
A Bukkit/Spigot plugin that enhances Minecraft farming methods by making them more realistic and harder.

# Todo
* Reimplement WildSex features - In optimal conditions animals should automatically reproduce.
* Animals should need to eat grass / whatever to be able to survive. Animals that don't eat should start losing health. (This forces outdoor farming and farming in large spaces.)
    * Spigot reports -> SheepRegrowWoolEvent triggered whenever sheep eat grass. Should be fixed.
    * Use EntityChangeBlockEvent to notice eaten grass
    * Use own variety of PathfinderGoalEatTile to make animals eat (https://bukkit.org/threads/deobfuscated-unobfuscated-pathfindergoal.233633/#post-2263215)
* It should be able to modify grass spread rate.
* Eggs should automatically hatch to create chicks if the parent chicken stays around throughout the time.
* Sheep should only regenerate white wool
    * Paint sheep white on SheepRegrowWoolEvent
* No XP should drop from animal killing
* Animals should be able to get sick and spread disease

* Unattended plants should wither (convert to shrub blocks)
* Farming efficiency should depend on water amount & light level & biome. (All plants are equal but some are more equal)
* Unattended farmland & overused grass should rot into mycelium (and spread)
* Raw meat etc. should eventually rot when stored in warm storage (check chests, check if they have ice around them)
