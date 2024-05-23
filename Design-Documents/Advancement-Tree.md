```mermaid
%%{init: {"flowchart": {"defaultRenderer": "elk"}} }%%
flowchart TD
  
  Novice-Explorer(Novice Explorer)
  Novice-Explorer-->Novice-Scavenger & Berry-Foraging
  
  Mountaineer(Mountaineer)
  Mountaineer-->Sand-Mining & Gravel-Mining
  
  Novice-Scavenger(Novice Scavenger)
  Novice-Scavenger-->Crop-Harvesting & Tree-Harvesting
  



  Novice-Hunter(Novice Hunter)
  Novice-Hunter-->Mountaineer & Crop-Harvesting
  
  Novice-Mob-Slayer(Novice Mob Slayer)
  Novice-Mob-Slayer-->Basic-Wood-Working



  Novice-Builder(Novice Builder)
  Novice-Builder-->Basic-Wood-Working
  Basic-Wood-Working(Basic Wood Working)



  Flower-Gathering(Flower Gathering)
  Flower-Gathering-->Shrubbery-Clearing
  
  Shrubbery-Clearing(Shrubbery Clearing)
  Shrubbery-Clearing-->Seed-Gathering
  
  Seed-Gathering(Seed Gathering)
  Seed-Gathering-->Novice-Foraging & Dirt-Mining
  
  Novice-Foraging(Novice Foraging)
  Novice-Foraging-->Berry-Foraging  
  
  Berry-Foraging(Berry Foraging)
  Berry-Foraging-->Crop-Harvesting & Mushroom-Foraging & Sappling-Farming
  
  Crop-Harvesting(Crop Harvesting)
  Crop-Harvesting-->Berry-Farming & Sappling-Farming
  
  Mushroom-Foraging(Mushroom Foraging)



  Berry-Farming(Berry Farming)
  
  Sappling-Farming(Sappling Farming)



  Dirt-Mining(Dirt Mining)
  Dirt-Mining-->Sand-Mining & Novice-Builder
  
  Sand-Mining(Sand Mining)
  Sand-Mining-->Gravel-Mining
  
  Gravel-Mining(Gravel Mining)
  Gravel-Mining-->Clay-Mining
  
  Clay-Mining(Clay Mining)
  Clay-Mining-->Snow-Mining
  
  Snow-Mining(Snow Mining)
  Snow-Mining-->Ice-Mining
  Ice-Mining(Ice Mining)
  
  Tree-Harvesting(Tree Harvesting)
  Basic-Wood-Working-->Tree-Harvesting
```
