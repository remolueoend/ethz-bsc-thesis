# Monitoring Complex Data Types

The complete thesis paper can be downloaded [here](https://raw.githubusercontent.com/remolueoend/ethz-bsc-thesis/main/thesis.pdf).

## Abstract

The runtime verification tool `MonPoly` with its extensive temporal specification language `MFODL` provides a broad set of features, including real-time monitoring, global quantification, regular expressions matching over program traces, and computing SQL-like aggregations. While JSON-formatted application logs have become ubiquitous, allowing systems to output events as arbitrary complex data structures, both `MonPoly` and `MFODL` lack support for custom event data types.

To rectify this, we present an extension of `MFODL` that allows users to formulate policies over events of custom product types. A type-checking algorithm accompanies the extension with full type-inference support. Moreover, we provide an extension of `MonPoly` that supports monitoring JSON-formatted application logs with no or minimal preprocessing. We accomplish this with a formula compiler and a generalized log stream preprocessor.

Our case study on two real-world scenarios shows that our extension not only simplifies the monitoring process of complex-typed event streams but it allows users to formulate specifications over complex data structures more naturally, increasing the readability and comprehensibility of monitoring policies.

## Source Code
The source code of this thesis is available on Github: https://github.com/remolueoend/monpoly.
