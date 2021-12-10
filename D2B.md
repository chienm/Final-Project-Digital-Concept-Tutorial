## Final Project: Digital Concept Tutorial

#### By Michael Chien

# [Binary and Decimal Value](README.md)

# How to convert Decimal Values to Binary
---

## Decimal Values to Binary
 
To find the value of a decimal number in binary, continously subtract the decimal value with the larget binary digit so that it does not exceed 0. The conversion is done once the subracted decimal value is equal to 0. The digits that were used will have a value of 1 while the digits that were not used would have a value of 0.

## Example of Converting from Decimal to Binary

The following example exmplains how to convert the decimal value of 323 to Binary. 

1. The larget value that can be subtracted from 323 would be 64, or the 9th binary digit. So the binary digit would have a value of 1. After subtracting 256 from 323, the remaining decimal value would be 67.

> * Decimal Value 323-256=67.
>
> * Binary Value: 1????????.

2. The larget value that can be subtracted from 67 would be 64, or the 7th binary digit. So the binary digit would have a value of 1. After subtracting 64 from 67, the remaining decimal value would be 3. Any binary digit between the 7th and 9th digit would have a value of 0.

> * Decimal Value 67-264=3.
>
> * Binary Value: 101??????.

3. The larget value that can be subtracted from 3 would be 2, or the 2nd binary digit. So the binary digit would have a value of 1. After subtracting 2 from 3, the remaining decimal value would be 1. Any binary digit between the 2nd and 7th digit would have a value of 1.

> * Decimal Value 3-2=1.
>
> * Binary Value: 10100001?.

3. The larget value that can be subtracted from 1 would be 1, or the 1st binary digit. So the binary digit would have a value of 1. After subtracting 1 from 1, the remaining decimal value would be 0, which completes the decimal to binary conversion.

> * Decimal Value 1-1=0.
>
> * Binary Value: 101000011.

So, the decimal value of 323 would have a binary value of **101000011**.

---

#### [What is Binary?](Binary.md)

#### [What are Deciaml Values](Decimal.md)

#### [How to Convert from Binary to Decimal Values](B2D.md)

#### [Video Tutorial](https://youtu.be/b47QnQoFk50)
