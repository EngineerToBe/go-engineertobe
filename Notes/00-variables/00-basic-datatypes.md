Data Types specify the kinds of the value a variable can store and also what kind of operation can be performed on a variables?

GoLang is strictly typed language.

## Integers

It is of two types

Note:

When we say Platform Dependent. It means 

    On 32 bit machines, the size of int will be 32 bits or 4 byte.
    On 64 bit machines, the size of int will be 64 bits or 8 byte

### Signed 

A Signed integer can be either positive or negative.


Just FYI 8 bits == 1 byte

| Type | Size | Range |
| --- | ----------- |------------|
| int | Depend upon the Platform | -2^31 to 2^31 -1 and 64-bit system can store -2^63 to 2^63 -1 |
| int8 | 8 bits / 1 byte | -2^7 to 2^7 - 1 |
| int16 | 16 bits / 2 byte | -2^15 to 2^15 -1 |
| int32 | 32 bits / 4 byte |  -2^31 to 2^31 -1 |
| int64 | 64 bits / 8 byte | -2^63 to 2^63 -1 |


### Unsigned 

| Type | Size | Range |
| --- | ----------- |------------|
| uint | Platform Independent | 2^31 -1 and 64-bit system can store 2^63 - 1 |
| uint8 | 8 bits / 1 byte | 0 to  2^8 - 1 |
| uint16 | 16 bits / 2 byte | 0 to 2^16 -1 |
| uint32 | 32 bits / 4 byte |  0 to 2^32 -1 |
| uint64 | 64 bits / 8 byte | 0 to 2^64 -1 |
| uintptr | Platform Independent | -231 to 231 -1 on 32-bit and -263 to 263 -1 on 64-bit |


## Floats

Floats are numbers with decimals. It is of two types

| Type | Size | Range |
| --- | ----------- |------------|
| float32 | 32 bits / 4 bytes |  -3.4E+38 to +3.4E+38 |
| flaot64 | 64 bits / 8 bytes | 1.2E-38 to 3.4E+38 |


## Complex Numbers

Complex Numbers are of two types

| Type | Size | Range |
| --- | ----------- |---------------|
| complex64 | `complex64` has `float32` real part and `float32` imaginary part | 1.2E-38 to 3.4E+38 |
| complex128 | `complex128` has `float64` real part and `float64` imaginary part | -1.7E+308 to +1.7E+308 |



## Byte

byte in Go is an alias for uint8 meaning it is an integer value. This integer value is of 8 bits and it represents one byte i.e number between 0-255.


## Rune

rune in Go is  an alias for int32 meaning it is an integer value. This integer value is meant to represent a Unicode Code Point. 


## String

string is a read only slice of bytes in golang. String can be initialized in two ways

    * using double quotes “” eg “this”
    * using back quotes ` eg  \`this`


## Booleans

The data type is bool and has two possible values true or false.

Default Value: false