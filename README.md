# The NIST Statistical Test Suite with LFSR PRNG

## Description

This repository contains the code for testing random number generators published by the US National Institute of Science and Technology (NIST). The code was created to accompany NIST SP-800-22 R1a, a copy of which can be found in this repository as [`nistspecialpublication800-22r1a.pdf`][1] (ref \[1]).

[1]: (nistspecialpublication800-22r1a.pdf)


## How to rebuild

```console
$ make rebuild
```

It creates an executable, `assess`, which is usually run interactively to do a test. See Section 5.6 of [[1]].

### Sample commandline run

```console
$ time echo "10 1 0 100" | ./assess 1000000
```


## Origin

**Source File**: *sts-2_1_2.zip*

**Document File**: *A Statistical Test Suite for Random and Pseudorandom Number Generators for Cryptographic Applications* (Andrew Rukhin, Juan Soto, James Nechvatal, Miles Smid, Elaine Barker, Stefan Leigh, Mark Levenson, Mark Vangel, David Banks,Alan Heckert, James Dray, San Vo) **Revised**: *April 2010* (Lawrence E Bassham III)



