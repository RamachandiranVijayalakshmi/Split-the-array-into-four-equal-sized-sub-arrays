## Split-the-array-into-four-equal-sized-sub-arrays
## Sample code to check the array
```sh
import numpy

print("Creating 8X3 array using numpy.arange")
sampleArray = numpy.arange(10, 34, 1)
sampleArray = sampleArray.reshape(8,3)
print (sampleArray)

print("\nDividing 8X3 array into 4 sub array\n")
subArrays = numpy.split(sampleArray, 4) 
print(subArrays)
```
## Expected output
Creating 8X3 array using numpy.arange
[[10 11 12]
 [13 14 15]
 [16 17 18]
 [19 20 21]
 [22 23 24]
 [25 26 27]
 [28 29 30]
 [31 32 33]]

Dividing 8X3 array into 4 sub array

[array([[10, 11, 12],[13, 14, 15]]), 
array([[16, 17, 18],[19, 20, 21]]), 
array([[22, 23, 24],[25, 26, 27]]), 
array([[28, 29, 30],[31, 32, 33]])]
