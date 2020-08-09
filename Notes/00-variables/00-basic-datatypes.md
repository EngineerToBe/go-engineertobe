Data Types specify the kinds of the value a variable can store and also what kind of operation can be performed on a variables?

GoLang is strictly typed language.

## Integers

It is of two types

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
| uint | Depend upon the Platform | 2^31 -1 and 64-bit system can store 2^63 - 1 |
| uint8 | 8 bits / 1 byte | 0 to  2^8 - 1 |
| uint16 | 16 bits / 2 byte | 0 to 2^16 -1 |
| uint32 | 32 bits / 4 byte |  0 to 2^32 -1 |
| uint64 | 64 bits / 8 byte | 0 to 2^64 -1 |


## Floats

Floats are numbers with decimals. It is of two types

| Type | Size | Range |
| --- | ----------- |------------|
| float32 | 32 bits / 4 bytes |  -3.4E+38 to +3.4E+38 |
| flaot64 | 64 bits / 8 bytes | 1.2E-38 to 3.4E+38 |






