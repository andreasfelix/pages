# Untitled object in JSON lattice file format Schema

```txt
https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0
```




| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                              |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ------------------------------------------------------- |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Allowed               | none                | [schema.json\*](out/schema.json "open original schema") |

## 0 Type

`object` ([Details](schema-definitions-element.md))

# undefined Properties

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                                   |
| :-------------------------- | -------- | -------- | -------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)               | `string` | Required | cannot be null | [JSON lattice file format](schema-definitions-element-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/type")               |
| [description](#description) | `string` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/description") |
| [length](#length)           | `number` | Required | cannot be null | [JSON lattice file format](schema-definitions-element-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/length")           |
| [dx](#dx)                   | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/dx")                   |
| [dy](#dy)                   | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/dy")                   |
| [ds](#ds)                   | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/ds")                   |
| [tilt](#tilt)               | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/tilt")               |

## type

Type of the element.


`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/type")

### type Type

`string`

## description

Description of the element.


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/description")

### description Type

`string`

## length

The length of the element.


`length`

-   is required
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/length")

### length Type

`number`

### length Constraints

**minimum**: the value of this number must greater than or equal to: `0`

## dx

Horizontal misalignment


`dx`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/dx")

### dx Type

`number`

## dy

Vertical misalignment


`dy`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/dy")

### dy Type

`number`

## ds

Longitudinal misalignment


`ds`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/ds")

### ds Type

`number`

## tilt

Rotation about the longitudinal axis


`tilt`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/allOf/0/properties/tilt")

### tilt Type

`number`
