# JSON lattice file format Schema

```txt
https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json
```

Defines the magnetic lattice format


| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                            |
| :------------------ | ---------- | -------------- | ------------ | :---------------- | --------------------- | ------------------- | ----------------------------------------------------- |
| Can be instantiated | Yes        | Unknown status | No           | Forbidden         | Forbidden             | none                | [schema.json](out/schema.json "open original schema") |

## JSON lattice file format Type

`object` ([JSON lattice file format](schema.md))

# JSON lattice file format Definitions

## Definitions group Lattice

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Lattice"}
```

| Property | Type | Required | Nullable | Defined by |
| :------- | ---- | -------- | -------- | :--------- |

## Definitions group Element

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element"}
```

| Property                    | Type     | Required | Nullable       | Defined by                                                                                                                                                                                                          |
| :-------------------------- | -------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [type](#type)               | `string` | Required | cannot be null | [JSON lattice file format](schema-definitions-element-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/type")               |
| [description](#description) | `string` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/description") |
| [length](#length)           | `number` | Required | cannot be null | [JSON lattice file format](schema-definitions-element-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/length")           |
| [dx](#dx)                   | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/dx")                   |
| [dy](#dy)                   | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/dy")                   |
| [ds](#ds)                   | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/ds")                   |
| [tilt](#tilt)               | `number` | Optional | cannot be null | [JSON lattice file format](schema-definitions-element-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/tilt")               |

### type

Type of the element.


`type`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/type")

#### type Type

`string`

### description

Description of the element.


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/description")

#### description Type

`string`

### length

The length of the element.


`length`

-   is required
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/length")

#### length Type

`number`

#### length Constraints

**minimum**: the value of this number must greater than or equal to: `0`

### dx

Horizontal misalignment


`dx`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/dx")

#### dx Type

`number`

### dy

Vertical misalignment


`dy`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/dy")

#### dy Type

`number`

### ds

Longitudinal misalignment


`ds`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/ds")

#### ds Type

`number`

### tilt

Rotation about the longitudinal axis


`tilt`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-element-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Element/properties/tilt")

#### tilt Type

`number`

## Definitions group Drift

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift"}
```

| Property                    | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                      |
| :-------------------------- | ------------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)               | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/type")               |
| [description](#description) | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/description") |
| [length](#length)           | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/length")           |
| [dx](#dx)                   | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/dx")                   |
| [dy](#dy)                   | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/dy")                   |
| [ds](#ds)                   | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/ds")                   |
| [tilt](#tilt)               | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-drift-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/tilt")               |

### type




`type`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/type")

#### type Type

unknown

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"Drift"
```

### description




`description`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/description")

#### description Type

unknown

### length




`length`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/length")

#### length Type

unknown

### dx




`dx`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/dx")

#### dx Type

unknown

### dy




`dy`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/dy")

#### dy Type

unknown

### ds




`ds`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/ds")

#### ds Type

unknown

### tilt




`tilt`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-drift-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Drift/properties/tilt")

#### tilt Type

unknown

## Definitions group Dipole

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole"}
```

| Property                                                  | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                      |
| :-------------------------------------------------------- | ------------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/type")                                             |
| [description](#description)                               | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/description")                               |
| [length](#length)                                         | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/length")                                         |
| [dx](#dx)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/dx")                                                 |
| [dy](#dy)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/dy")                                                 |
| [ds](#ds)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/ds")                                                 |
| [tilt](#tilt)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/tilt")                                             |
| [angle](#angle)                                           | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-angle.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/angle")                                           |
| [radius](#radius)                                         | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-radius.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/radius")                                         |
| [ps_value](#ps_value)                                     | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/ps_value")                                     |
| [e1](#e1)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-e1.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/e1")                                                 |
| [e2](#e2)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-e2.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/e2")                                                 |
| [h1](#h1)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-h1.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/h1")                                                 |
| [h2](#h2)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-h2.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/h2")                                                 |
| [conversion_factor_ps_value](#conversion_factor_ps_value) | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-dipole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/conversion_factor_ps_value") |

### type




`type`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/type")

#### type Type

unknown

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"Dipole"
```

### description




`description`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/description")

#### description Type

unknown

### length




`length`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/length")

#### length Type

unknown

### dx




`dx`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/dx")

#### dx Type

unknown

### dy




`dy`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/dy")

#### dy Type

unknown

### ds




`ds`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/ds")

#### ds Type

unknown

### tilt




`tilt`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/tilt")

#### tilt Type

unknown

### angle

Deflection angle


`angle`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-angle.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/angle")

#### angle Type

`number`

### radius

Radius of curvature


`radius`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-radius.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/radius")

#### radius Type

`number`

### ps_value

Power supply value.


`ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/ps_value")

#### ps_value Type

`number`

### e1




`e1`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-e1.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/e1")

#### e1 Type

`number`

### e2




`e2`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-e2.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/e2")

#### e2 Type

`number`

### h1




`h1`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-h1.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/h1")

#### h1 Type

`number`

### h2




`h2`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-h2.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/h2")

#### h2 Type

`number`

### conversion_factor_ps_value




`conversion_factor_ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-dipole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Dipole/properties/conversion_factor_ps_value")

#### conversion_factor_ps_value Type

`number`

## Definitions group Quadrupole

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole"}
```

| Property                                                  | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                              |
| :-------------------------------------------------------- | ------------- | -------- | -------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [type](#type)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/type")                                             |
| [additionalProperties](#additionalProperties)             | Not specified | Optional | cannot be null | [Untitled schema](undefined.md "undefined#undefined")                                                                                                                                                                                                   |
| [description](#description)                               | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/description")                               |
| [length](#length)                                         | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/length")                                         |
| [dx](#dx)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/dx")                                                 |
| [dy](#dy)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/dy")                                                 |
| [ds](#ds)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/ds")                                                 |
| [tilt](#tilt)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/tilt")                                             |
| [k1](#k1)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-k1.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/k1")                                                 |
| [ps_value](#ps_value)                                     | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/ps_value")                                     |
| [conversion_factor_ps_value](#conversion_factor_ps_value) | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-quadrupole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/conversion_factor_ps_value") |

### type




`type`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/type")

#### type Type

unknown

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"Quadrupole"
```

### additionalProperties

no description

`additionalProperties`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [Untitled schema](undefined.md "undefined#undefined")

#### Untitled schema Type

unknown

### description




`description`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/description")

#### description Type

unknown

### length




`length`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/length")

#### length Type

unknown

### dx




`dx`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/dx")

#### dx Type

unknown

### dy




`dy`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/dy")

#### dy Type

unknown

### ds




`ds`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/ds")

#### ds Type

unknown

### tilt




`tilt`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/tilt")

#### tilt Type

unknown

### k1

Geometric quadrupole strength


`k1`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-k1.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/k1")

#### k1 Type

`number`

### ps_value




`ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/ps_value")

#### ps_value Type

`number`

### conversion_factor_ps_value




`conversion_factor_ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-quadrupole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Quadrupole/properties/conversion_factor_ps_value")

#### conversion_factor_ps_value Type

`number`

## Definitions group Sextupole

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole"}
```

| Property                                                  | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                            |
| :-------------------------------------------------------- | ------------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/type")                                             |
| [additionalProperties](#additionalProperties)             | Not specified | Optional | cannot be null | [Untitled schema](undefined.md "undefined#undefined")                                                                                                                                                                                                 |
| [description](#description)                               | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/description")                               |
| [length](#length)                                         | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/length")                                         |
| [dx](#dx)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/dx")                                                 |
| [dy](#dy)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/dy")                                                 |
| [ds](#ds)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/ds")                                                 |
| [tilt](#tilt)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/tilt")                                             |
| [k2](#k2)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-k2.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/k2")                                                 |
| [ps_value](#ps_value)                                     | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/ps_value")                                     |
| [conversion_factor_ps_value](#conversion_factor_ps_value) | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-sextupole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/conversion_factor_ps_value") |

### type




`type`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/type")

#### type Type

unknown

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"Sextupole"
```

### additionalProperties

no description

`additionalProperties`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [Untitled schema](undefined.md "undefined#undefined")

#### Untitled schema Type

unknown

### description




`description`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/description")

#### description Type

unknown

### length




`length`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/length")

#### length Type

unknown

### dx




`dx`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/dx")

#### dx Type

unknown

### dy




`dy`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/dy")

#### dy Type

unknown

### ds




`ds`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/ds")

#### ds Type

unknown

### tilt




`tilt`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/tilt")

#### tilt Type

unknown

### k2

Geometric sextupole strength


`k2`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-k2.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/k2")

#### k2 Type

`number`

### ps_value




`ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/ps_value")

#### ps_value Type

`number`

### conversion_factor_ps_value




`conversion_factor_ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-sextupole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Sextupole/properties/conversion_factor_ps_value")

#### conversion_factor_ps_value Type

`number`

## Definitions group Octupole

Reference this group by using

```json
{"$ref":"https://github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole"}
```

| Property                                                  | Type          | Required | Nullable       | Defined by                                                                                                                                                                                                                                          |
| :-------------------------------------------------------- | ------------- | -------- | -------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [type](#type)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/type")                                             |
| [additionalProperties](#additionalProperties)             | Not specified | Optional | cannot be null | [Untitled schema](undefined.md "undefined#undefined")                                                                                                                                                                                               |
| [description](#description)                               | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/description")                               |
| [length](#length)                                         | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/length")                                         |
| [dx](#dx)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/dx")                                                 |
| [dy](#dy)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/dy")                                                 |
| [ds](#ds)                                                 | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/ds")                                                 |
| [tilt](#tilt)                                             | Not specified | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/tilt")                                             |
| [k3](#k3)                                                 | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-k3.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/k3")                                                 |
| [ps_value](#ps_value)                                     | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/ps_value")                                     |
| [conversion_factor_ps_value](#conversion_factor_ps_value) | `number`      | Optional | cannot be null | [JSON lattice file format](schema-definitions-octupole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/conversion_factor_ps_value") |

### type




`type`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-type.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/type")

#### type Type

unknown

#### type Constraints

**constant**: the value of this property must be equal to:

```json
"Octupole"
```

### additionalProperties

no description

`additionalProperties`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [Untitled schema](undefined.md "undefined#undefined")

#### Untitled schema Type

unknown

### description




`description`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/description")

#### description Type

unknown

### length




`length`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-length.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/length")

#### length Type

unknown

### dx




`dx`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-dx.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/dx")

#### dx Type

unknown

### dy




`dy`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-dy.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/dy")

#### dy Type

unknown

### ds




`ds`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-ds.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/ds")

#### ds Type

unknown

### tilt




`tilt`

-   is optional
-   Type: unknown
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-tilt.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/tilt")

#### tilt Type

unknown

### k3

Geometric octupole strength


`k3`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-k3.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/k3")

#### k3 Type

`number`

### ps_value




`ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/ps_value")

#### ps_value Type

`number`

### conversion_factor_ps_value




`conversion_factor_ps_value`

-   is optional
-   Type: `number`
-   cannot be null
-   defined in: [JSON lattice file format](schema-definitions-octupole-properties-conversion_factor_ps_value.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/definitions/Octupole/properties/conversion_factor_ps_value")

#### conversion_factor_ps_value Type

`number`

# JSON lattice file format Properties

| Property                      | Type     | Required | Nullable       | Defined by                                                                                                                                                                    |
| :---------------------------- | -------- | -------- | -------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [name](#name)                 | `string` | Required | cannot be null | [JSON lattice file format](schema-properties-name.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/name")                 |
| [description](#description)   | `string` | Optional | cannot be null | [JSON lattice file format](schema-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/description")   |
| [lattice](#lattice)           | `array`  | Required | cannot be null | [JSON lattice file format](schema-properties-lattice.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/lattice")           |
| [sub_lattices](#sub_lattices) | `object` | Optional | cannot be null | [JSON lattice file format](schema-properties-sub_lattices.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/sub_lattices") |
| [elements](#elements)         | `object` | Required | cannot be null | [JSON lattice file format](schema-properties-elements.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/elements")         |

## name

The name of the lattice


`name`

-   is required
-   Type: `string`
-   cannot be null
-   defined in: [JSON lattice file format](schema-properties-name.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/name")

### name Type

`string`

## description

A brief description of the lattice


`description`

-   is optional
-   Type: `string`
-   cannot be null
-   defined in: [JSON lattice file format](schema-properties-description.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/description")

### description Type

`string`

## lattice




`lattice`

-   is required
-   Type: `string[]`
-   cannot be null
-   defined in: [JSON lattice file format](schema-properties-lattice.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/lattice")

### lattice Type

`string[]`

## sub_lattices




`sub_lattices`

-   is optional
-   Type: `object` ([Details](schema-properties-sub_lattices.md))
-   cannot be null
-   defined in: [JSON lattice file format](schema-properties-sub_lattices.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/sub_lattices")

### sub_lattices Type

`object` ([Details](schema-properties-sub_lattices.md))

## elements




`elements`

-   is required
-   Type: `object` ([Details](schema-properties-elements.md))
-   cannot be null
-   defined in: [JSON lattice file format](schema-properties-elements.md "https&#x3A;//github.com/andreasfelix/latticejson/blob/master/latticejson/schema.json#/properties/elements")

### elements Type

`object` ([Details](schema-properties-elements.md))
