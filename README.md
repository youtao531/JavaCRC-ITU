# JavaCRC-ITU
CRC-ITU algorithm implamantation in Java
### Usage
Import the class in your project
```java
import com.dknacht.crcitu.CRCITU;
```
Then use the CRCITU.process(string) to calculate the result
```java
CRCITU.process("0d0103588990501766460026"); // will return "7bf9"
CRCITU.process("0d010358899050176646002a"); // will return "b195"
CRCITU.process("0d010358899050176646002b"); // will return "a01c"
```
### Lincense
This implementation is under the MIT license.
