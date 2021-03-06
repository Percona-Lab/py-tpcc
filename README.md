## TPC-C in Python for MongoDB

This repo is an experimental variant of Python TPC-C implementation based on the original [here](http://github.com/apavlo/py-tpcc).

The structure of the repo is:

1. **pytpcc** - the code for pytpcc with driver (DB) specific code in **drivers** subdirectory.
2. **vldb2019** - 2019 VLDB paper, poster and results generated from this code
   * [VLDB Paper](vldb2019/paper.pdf)
   * [VLDB Poster](vldb2019/poster.pdf)
   * [Result directory](vldb2019/results)

All the tests were run using [MongoDB Atlas](https://www.mongodb.com/cloud/atlas?jmp=VLDB2019).
Use code `VLDB2019` to get $150 credit to get started with MongoDB Atlas.

