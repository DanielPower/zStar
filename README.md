# zStar

Lua pathfinding library using the astar algorithm.

## Dependencies
zArray - A library to simplify two dimensional arrays.

## Example
```lua
require('zArray')       -- Library to simplify 2-dimensional arrays
require('zStar')        -- Pathfinding library

-- Start Point
point1 = {
    x = 1,
    y = 1,
}

-- End point
point2 = {
    x = 6,
    y = 0,
}

-- List of all collidable cells
zStar.collidables = {
    {x=3, y=0},
    {x=3, y=1},
}

-- Get the path
path = zStar.getPath(point1.x, point1.y, point2.x, point2.y)
```
