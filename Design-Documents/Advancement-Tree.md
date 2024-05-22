```mermaid
%%{init: {"flowchart": {"defaultRenderer": "elk"}} }%%
flowchart TD
  
  Novice-Explorer(Novice Explorer\n Explore 3 Different Biomes)
  Novice-Explorer-->Novice-Scavenger & Berry-Foraging
  
  Mountaineer(Mountaineer\n Climb the tallest Mountain on your Island)
  Mountaineer-->Sand-Mining & Gravel-Mining
  
  Novice-Scavenger(Novice Scavenger\n Open a Chest)
  Novice-Scavenger-->Crop-Harvesting & Tree-Harvesting
  



  Novice-Hunter(Novice Hunter\n Kill 10 Cows, Pigs, Chickens, and Sheep)
  Novice-Hunter-->Mountaineer & Crop-Harvesting
  
  Novice-Mob-Slayer(Novice Mob Slayer)
  Novice-Mob-Slayer-->Basic-Wood-Working



  Novice-Builder(Novice Builder)
  Novice-Builder-->Basic-Wood-Working
  Basic-Wood-Working(Basic Wood Working)
  Basic-Wood-Working-->



  Flower-Gathering(Flower Gathering\n)
  Flower-Gathering-->Shrubbery-Clearing
  
  Shrubbery-Clearing(Shrubbery Clearing\n)
  Shrubbery-Clearing-->Seed-Gathering
  
  Seed-Gathering(Seed Gathering\n Collect 10 Seeds)
  Seed-Gathering-->Novice-Foraging
  
  Novice-Foraging(Novice Foraging\n)
  Novice-Foraging-->Berry-Foraging  
  
  Berry-Foraging(Berry Foraging\n)
  Berry-Foraging-->Crop-Harvesting & Mushroom-Foraging & Sappling-Framing
  
  Crop-Harvesting(Crop Harvesting\n)
  Crop-Harvesting-->Berry-Farming & Sappling-Farming
  
  Mushroom-Foraging(Mushroom-Foraging\n)



  Berry-Farming(Berry Farming)
  
  Sappling-Farming(Sappling Farming\n)



  Dirt-Mining(Dirt Mining\n)
  Dirt-Mining-->Sand-Mining & Novice-Builder
  
  Sand-Mining(Sand Mining\n)
  Sand-Mining-->Gravel-Mining
  
  Gravel-Mining(Gravel Mining\n)
  Gravel-Mining-->Clay-Mining
  
  Clay-Mining(Clay Mining\n)
  Clay-Mining-->Snow-Mining
  
  Snow-Mining(Snow Mining\n)
  Snow-Mining-->Ice-Mining
  Ice-Mining(Ice Mining\n)
  
  Tree-Harvesting(Tree Harvesting)
  Basic-Wood-Working-->Tree-Harvesting
```
