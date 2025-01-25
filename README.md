# Subtle Array Comparison Bug in TypeScript

This repository demonstrates a common yet subtle bug in TypeScript when comparing arrays of potentially different lengths. The function `compareArrays` aims to check if two number arrays are identical, but it fails for arrays of unequal lengths due to an off-by-one error in its length check.