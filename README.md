# viterbidecoder

This project is to realize a n,k,m viterbi decoder in systemc.

This project provides a test bench and configurable n,k,m.

|| Configuring the environment
1. Install SystemC latest verion
2. configure systemc and m as parameters for linker in eclipse environment
3. Add linker and library path

|| Configuring the project
1. viterbi_decoder_functions.h has all n,k,m and polynomials parameters
2. viterbi_decoder_testBench.h has TestCase selection function switch
3. viterbi_decoder_testBench.cpp has TestCase defining variables xTestArraySize, xTestArray

|| Tracing
1. viterbi_decoder_functions.h has C_DEBUGTRACE ENABLE/DISABLE functionality which provides tracing of the each node's possible incomming calls and their hamming distance and consolidated output value, as well as minimum value traced node
2. viterbi_decoder_testBench.h shows output decoded at every iterations and the latency.
