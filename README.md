# GoLang Full Refresh

### Pointers

Go has pointers. A pointer holds the memory address of a value.

The type *T is a pointer to a T value. Its zero value is nil. Basically creating a pointer to value nil.

var p *int
The & operator generates a pointer to its operand.

i := 42
p = &i
The * operator denotes the pointer's underlying value.

fmt.Println(*p) // read i through the pointer p
*p = 21         // set i through the pointer p
This is known as "dereferencing" or "indirecting".

