# Vector2

A vector in 2D space.

*Since:* 0.4.0

## Properties

### x

`vector.x: number`

The x coordinate of the vector.

### y

`vector.y: number`

The y coordinate of the vector.

## Methods

### length

`vector.length(): number`

Compute the length of the vector: `sqrt(x^2 + y^2)`.

**Returns**

The length of the vector.

### directionTo

`vector.directionTo(v: Vector2): Vector2`

Compute a unit vector pointing to `v` from `this`.

**Arguments**

* `v: Vector2`. A vector.

**Returns**

A new unit vector pointing to `v` from `this`.

### equals

`vector.equals(v: Vector2): boolean`

Check if `this` and `v` have the same coordinates.

**Arguments**

* `v: Vector2`. A vector.

**Returns**

`true` if `this` and `v` have the same coordinates.

### toString

`vector.toString(): string`

Generate a string representation of the vector.

**Returns**

A string representation of the vector.