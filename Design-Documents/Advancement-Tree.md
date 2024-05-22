```mermaid
%%{init: {"flowchart": {"defaultRenderer": "elk"}} }%%
flowchart LR
  Novice-Explorer(Novice Explorer)
  Novice-Explorer-->Novice-Crafting & Knowing-Home & Flower-Gathering

  Mountaineer(Mountaineer)
  Mountaineer-->Knowing-Home

  Novice-Hunter(Novice Hunter)
  Novice-Hunter-->Knowing-Home

  Novice-Crafting(Novice Crafting)
  Novice-Crafting-->Novice-Mining

  Knowing-Home(Knowing Home)
  Knowing-Home-->Novice-Scavenger & Novice-Foraging

  Flower-Gathering(Flower Gathering)
  Flower-Gathering-->Novice-Foraging

  Novice-Mining(Novice Mining)
  Novice-Mining-->Dirt-Mining & Crop-Harvesting & Shrubbery-Clearing

  Novice-Scavenger(Novice Scavenger)
  Novice-Scavenger-->Dirt-Mining

  Novice-Foraging(Novice Foraging)
  Novice-Foraging-->Crop-Harvesting & Shrubbery-Clearing

  Dirt-Mining(Dirt Mining)


  Crop-Harvesting(Crop Harvesting)


  Shrubbery-Clearing(Shrubbery Clearing)
```
