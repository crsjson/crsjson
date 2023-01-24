CRSJSON
=======

CRSJSON is a JSON encoding of
[WKT2:2019 / ISO-19162:2019: Geographic information - Well-known text representation of coordinate reference systems](http://docs.opengeospatial.org/is/18-010r7/18-010r7.html>),
which itself implements the model of [ISO-19111](https://docs.opengeospatial.org/as/18-005r4/18-005r4.html).
Apart from the difference of encodings, the semantics is intended to be exactly
the same as WKT2:2019, and CRSJSON can be morphed losslessly from/into WKT2:2019.

Please refer to the [specification](crsjson.rst) and the [schema](crsjson.schema.json)
