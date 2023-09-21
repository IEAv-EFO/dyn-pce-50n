# dyn-pce-50n

baud rate: 38400

Message read has 13 Bytes continuously sent by dynamometer at approx 15 ms, formatted `\s\s-1.20N\s\s\s\r\n`.

To zero reference: `Z\r\n`
Choose Newton unit: `E\r\n`

For a python reference, check [@roneydua](https://github.com/roneydua/doutorado/blob/4e5b99f724f4f8f54f1ec53d2479db4d36d11c2e/aquisitions/auxiliary_classes.py#L268C19-L268C19)'s code.
