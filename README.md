Pascal for C users
==================

**Note:** Logical operators (AND/OR/XOR etc) are logical or boolean depending on the type of the arguments (boolean or integer). Since Pascal had a separate boolean type from the start, boolean operators on integers were not necessary, and are always logical.

| C   | [Pascal](https://wiki.freepascal.org/Pascal "Pascal") | Notes |
| --- | --- | --- |
| {   | [Begin](https://wiki.freepascal.org/Begin "Begin") |     |
| }   | [End](https://wiki.freepascal.org/End "End") |     |
| =   | :=  | [Becomes](https://wiki.freepascal.org/Becomes "Becomes") |
| ==  | =   | [Equal](https://wiki.freepascal.org/Equal "Equal") |
| /   | /   | [Float Division](https://wiki.freepascal.org/Slash "Slash") (Integer: [div](https://wiki.freepascal.org/Div "Div")) |
| %   | [Mod](https://wiki.freepascal.org/Mod "Mod") | Modulo operation |
| !   | [Not](https://wiki.freepascal.org/Not "Not") | Logical not |
| !=  | <>  | [Not equal](https://wiki.freepascal.org/Not_equal "Not equal") |
| &&  | [And](https://wiki.freepascal.org/And "And") | Logical and |
| \|  | [Or](https://wiki.freepascal.org/Or "Or") | Logical or |
| &   | [And](https://wiki.freepascal.org/And "And") | Bitwise and |
| \|  | [Or](https://wiki.freepascal.org/Or "Or") | Bitwise or |
| ^   | [Xor](https://wiki.freepascal.org/Xor "Xor") | Exclusive or |
| ~   | [Not](https://wiki.freepascal.org/Not "Not") | One's complement |
| >\> | [Shr](https://wiki.freepascal.org/Shr "Shr") | bit shift right   Note: shr is a logical bitshift, not arithmetic. If the left operand is a negative value of a signed type, then the result of an shr operation may not be what you expect. |
| <<  | [Shl](https://wiki.freepascal.org/Shl "Shl") | bit shift left |
| \+\+ | [Inc](https://wiki.freepascal.org/Inc "Inc") |     |
| \-\- | [Dec](https://wiki.freepascal.org/Dec "Dec") |     |
| /\* | { or (* | [Comment](https://wiki.freepascal.org/Comments "Comments") start |
| */  | } or *) | Comment end |
| //  | //  | End of line comment (only one line comment) |
| 0x  | [$](https://wiki.freepascal.org/Dollar_sign "Dollar sign") | prefix for hex-number e.g. $FFFFFF |
| 0   | [&](https://wiki.freepascal.org/%26 "&") | prefix for oct-number e.g. &77777777 |
| 0b  | [%](https://wiki.freepascal.org/Percent_sign "Percent sign") | prefix for bin-number e.g. %11111111 |
| &   | [@](https://wiki.freepascal.org/@ "@") | [address operator](https://wiki.freepascal.org/@ "@") |
| \*  | [ ^ ](https://wiki.freepascal.org/%5E"^") | See [Pointer](https://wiki.freepascal.org/Pointer "Pointer") and [Pointers](https://wiki.freepascal.org/Pointers "Pointers") |
| if() | [If](https://wiki.freepascal.org/If "If") [Then](https://wiki.freepascal.org/Then "Then") |     |
| if() else | [If](https://wiki.freepascal.org/If "If") [Then](https://wiki.freepascal.org/Then "Then") [Else](https://wiki.freepascal.org/Else "Else") |     |
| while | [While](https://wiki.freepascal.org/While "While") [Do](https://wiki.freepascal.org/Do "Do") |     |
| do while | [Repeat](https://wiki.freepascal.org/Repeat "Repeat") [Until](https://wiki.freepascal.org/Until "Until") [Not](https://wiki.freepascal.org/Not "Not") |     |
| do while ! | [Repeat](https://wiki.freepascal.org/Repeat "Repeat") [Until](https://wiki.freepascal.org/Until "Until") |     |
| for ++ | [For](https://wiki.freepascal.org/For "For") [To](https://wiki.freepascal.org/To "To") [Do](https://wiki.freepascal.org/Do "Do") |     |
| for -- | [For](https://wiki.freepascal.org/For "For") [Downto](https://wiki.freepascal.org/Downto "Downto") [Do](https://wiki.freepascal.org/Do "Do") |     |
| switch case break | [Case](https://wiki.freepascal.org/Case "Case") [Of](https://wiki.freepascal.org/Of "Of") [End](https://wiki.freepascal.org/End "End") |     |
| switch case break default | [Case](https://wiki.freepascal.org/Case "Case") [Of](https://wiki.freepascal.org/Of "Of") [Else](https://wiki.freepascal.org/Else "Else") [End](https://wiki.freepascal.org/End "End") |     |
| const a\_c\_struct *arg | [Constref](https://wiki.freepascal.org/Constref "Constref") arg : a\_c\_struct |     |
| a\_c\_struct *arg | [Var](https://wiki.freepascal.org/Var "Var") arg : a\_c\_struct |     |

  

| C type | [Pascal](https://wiki.freepascal.org/Pascal "Pascal") [type](https://wiki.freepascal.org/Data_type "Data type") | Size (bits) | Range | Notes |
| --- | --- | --- | --- | --- |
| char | [Char](https://wiki.freepascal.org/Char "Char") | 8-bit |     | [ASCII](https://wiki.freepascal.org/ASCII "ASCII") |
| signed char | [Shortint](https://wiki.freepascal.org/Shortint "Shortint") | 8-bit | -128 .. 127 |     |
| unsigned char | [Byte](https://wiki.freepascal.org/Byte "Byte") | 8-bit | 0 .. 255 |     |
| char* | [PChar](https://wiki.freepascal.org/PChar "PChar") | (32-bit) |     | Pointer to a null-terminated string |
| short int | [Smallint](https://wiki.freepascal.org/Smallint "Smallint") | 16-bit | -32768 .. 32767 |     |
| unsigned short int | [Word](https://wiki.freepascal.org/Word "Word") | 16-bit | 0 .. 65535 |     |
| int | [Integer](https://wiki.freepascal.org/Integer "Integer") | (16-bit or) 32-bit | -2147483648..2147483647 | Generic integer types |
| unsigned int | [Cardinal](https://wiki.freepascal.org/Cardinal "Cardinal") | (16-bit or) 32-bit | 0 .. 4294967295 | Generic integer types |
| long int | [Longint](https://wiki.freepascal.org/Longint "Longint") | 32-bit | -2147483648..2147483647 |     |
| unsigned long int | [Longword](https://wiki.freepascal.org/Longword "Longword") | 32-bit | 0 .. 4294967295 |     |
| float | [Single](https://wiki.freepascal.org/Single "Single") | 32-bit | 1.5E-45 .. 3.4E+38 |     |
| double | [Double](https://wiki.freepascal.org/Double "Double") | 64-bit | 5.0E-324 .. 1.7E+308 |     |
| unsigned long long | [QWord](https://wiki.freepascal.org/QWord "QWord")| 64-bit | 0 .. 18446744073709551615 | 
  

| C type | [Pascal](https://wiki.freepascal.org/Pascal "Pascal") | Notes |
| --- | --- | --- |
| struct { } | [Record](https://wiki.freepascal.org/Record "Record") [End](https://wiki.freepascal.org/End "End") |     |
| union { } | [Record](https://wiki.freepascal.org/Record "Record") [Case](https://wiki.freepascal.org/Case "Case") [Of](https://wiki.freepascal.org/Of "Of") [End](https://wiki.freepascal.org/End "End") | [Variant Record](https://wiki.freepascal.org/Case#Variant_Record "Case") |





| C   | [Pascal](https://wiki.freepascal.org/Pascal "Pascal") | [Unit](https://wiki.freepascal.org/Unit "Unit") |
| --- | --- | --- |
| abs | Abs | [System](https://wiki.freepascal.org/System_unit "System unit") |
| acos | ArcCos | [Math](https://wiki.freepascal.org/index.php?title=Math_unit&action=edit&redlink=1 "Math unit (page does not exist)") |
| asin | ArcSin | [Math](https://wiki.freepascal.org/index.php?title=Math_unit&action=edit&redlink=1 "Math unit (page does not exist)") |
| atan | ArcTan | [System](https://wiki.freepascal.org/System_unit "System unit") |
| atof | StrToFloat | [SysUtils](https://wiki.freepascal.org/sysutils "sysutils") |
| atoi | StrToInt | [SysUtils](https://wiki.freepascal.org/sysutils "sysutils") |
| atol | StrToInt | [SysUtils](https://wiki.freepascal.org/sysutils "sysutils") |
| atoll | StrToInt64 | [SysUtils](https://wiki.freepascal.org/sysutils "sysutils") |
| ceil | Ceil | [Math](https://wiki.freepascal.org/index.php?title=Math_unit&action=edit&redlink=1 "Math unit (page does not exist)") |
| cos | Cos | [System](https://wiki.freepascal.org/System_unit "System unit") |
| exp | Exp | [System](https://wiki.freepascal.org/System_unit "System unit") |
| floor | Floor | [Math](https://wiki.freepascal.org/index.php?title=Math_unit&action=edit&redlink=1 "Math unit (page does not exist)") |
| pow | Power | [Math](https://wiki.freepascal.org/index.php?title=Math_unit&action=edit&redlink=1 "Math unit (page does not exist)") |
| round | Round | [System](https://wiki.freepascal.org/System_unit "System unit") |
| sin | Sin | [System](https://wiki.freepascal.org/System_unit "System unit") |
| sqrt | Sqrt | [System](https://wiki.freepascal.org/System_unit "System unit") |
| strcpy | Copy | [System](https://wiki.freepascal.org/System_unit "System unit") |
| strlen | Length | [System](https://wiki.freepascal.org/System_unit "System unit") |
| tan | Tan | [Math](https://wiki.freepascal.org/index.php?title=Math_unit&action=edit&redlink=1 "Math unit (page does not exist)") |
| toupper | UpCase | [System](https://wiki.freepascal.org/System_unit "System unit") |


**Assignment Operators** 

|Operator C | Description | Example |
| ---       | ---         | ---     |
|=  |Simple assignment operator. Assigns values from right side operands to left side operand|C = A + B is equivalent to pascal C:= A + B|
|+=|Add AND assignment operator. It adds the right operand to the left operand and assign the result to the left operand.|C += A is equivalent to pascal C:= C + A
|-=|Subtract AND assignment operator. It subtracts the right operand from the left operand and assigns the result to the left operand.|C -= A is equivalent to pascal C := C - A|
|*=|Multiply AND assignment operator. It multiplies the right operand with the left operand and assigns the result to the left operand.|C *= A is equivalent to pascal C := C * A|
|/=|Divide AND assignment operator. It divides the left operand with the right operand and assigns the result to the left operand.|C /= A is equivalent to pascal C := C / A|
|%=|Modulus AND assignment operator. It takes modulus using two operands and assigns the result to the left operand.|C %= A is equivalent to pascal C := C mod A|
|&=|Bitwise AND assignment operator.|C &= 2 is equivalent to pascal C := C and 2|
|^=|Bitwise exclusive OR and assignment operator.|C ^= 2 is equivalent to pascal C := C or not 2|
|&#124;= |Bitwise inclusive OR and assignment operator.| C &#124;= 2 is equivalent to pascal C := C or 2|
|note: in free pascal you may not convert the following operators (+= , -= , *= , /=)|||


### C++

| C++ type | [Pascal](https://wiki.freepascal.org/Pascal "Pascal") | Notes |
| --- | --- | --- |
| class { } | [Class](https://wiki.freepascal.org/Class "Class") [End](https://wiki.freepascal.org/End "End") |     |
| class: { } | [Class](https://wiki.freepascal.org/Class "Class")( ) [End](https://wiki.freepascal.org/End "End") |     |
| template &lt;class T&gt; class { } | [Generic](https://wiki.freepascal.org/index.php?title=Generic&action=edit&redlink=1 "Generic (page does not exist)") = [Class](https://wiki.freepascal.org/Class "Class")&lt;T&gt; [End](https://wiki.freepascal.org/End "End") |     |
| struct { } | [Object](https://wiki.freepascal.org/Object "Object") [End](https://wiki.freepascal.org/End "End") | If you want methods |
