# HA1

**The name of the game:** Jump Boy

**Game Description:** 3D platformer with infinite different world generation

**Main character:**
Third view character - controlled by the player

### Gameplay:

**Goal:** Go through as many levels as possible each time getting harder
**Game mechanics:** Jump between platforms, collect bonuses
**Levels:** always different, creating by 6 types of platforms

### Graphics and styling: 
A starter content was used for the graphics

### Technical Description:
**Game engine:** Unreal Engine 4

### Funding and marketing:
The game will be distributed free and will not be monetize by any means other than donations.

## Description of the generation of levels and increasing their complexity

The number of levels in the game is infinite, exactly the same as the variations of the structure of these levels.
After each completed stage, the number of platforms increases by 1, the speed of all platforms increases, as well as the repulsion from some of their types.

## Description of bonuses
One type of bonuses has been implemented - slowing down all platforms for 5 seconds (red star bonus)

## Description of all moving obstacles

There are 6 types of moving obstacle platforms in the game:
* **RotatorPlatform** - returns the player back when touching
* **Rotator Platform (2-nd type)** - pushes the player into contact
* **VerticalMovingPlatfrom** - moves up and down
* **HorizontalMovingPlatform** - moves left and right
* **BarrelPlatform** - does not allow the player to quickly run across the platform and blocks movement until there is enough space to pass
* **SpinningPlatform** - does not allow the player to run straight

## Additional items for added copyright features
Platforms are able to appear in a small radius in width and height, so that the player cannot jump only straight

---

## Links
[UE4 Documentation](https://docs.unrealengine.com/)

[UE4 Forums](https://forums.unrealengine.com/)

[Procedural Generation](https://www.youtube.com/watch?v=Nb7HvAR0bsQ&t=348s)