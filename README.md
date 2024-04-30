# Unity Pathfinding made Simple
Unity Pathfinding made Simple is composed of a single CS file that you can copy-paste to your own projects, and have a simple A* pathfinding algorithm, that avoids all GameObjects that contain a collider that isn't a trigger.

## How do I use it?
In order to use this class, you only need to call the ´´AStar´´ method, and set as the parameters the starting position, and the desired end position. The function's output will be an array of Vector3 objects that, if you set your GameObject to move towards in succession, will navigate the obstacles.
