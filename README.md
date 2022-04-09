# Floating Point Number - Binary

## Float64 (Double)

***0*** ***00101100001*** ***0100111000110100010000010110000101001110001101000100*** (example)

| Sign      | Exponent          | Mantissa                                                   |
| :-------: | :---------------: | :--------------------------------------------------------: |
| ***0***   | ***00101100001*** | ***0100111000110100010000010110000101001110001101000100*** |

Sign     = (1 bit) ***0***

Exponent = (11 bits) ***00101100001***

Mantissa = (52 bits) ***0100111000110100010000010110000101001110001101000100***

| Float64  | Maximum                         | Minimum                        |
| :------- | :-----------------------------: | :----------------------------: |
| Positive | 1.7976931348623157 × 10 ^ 308   | 4.9406564584124654 × 10 ^ −324 |
| Negative | −4.9406564584124654 × 10 ^ −324 | −1.7976931348623157 × 10 ^ 308 |

[More info about Float64](https://en.wikipedia.org/wiki/Double-precision_floating-point_format)

## Float32 (Float)

***0*** ***00101100*** ***00101001110001101000100*** (example)

| Sign    | Exponent       | Mantissa                      |
| :-----: | :------------: | :---------------------------: |
| ***0*** | ***00101100*** | ***00101001110001101000100*** |

Sign     = (1 bit) ***0***

Exponent = (8 bits) ***00101100***

Mantissa = (23 bits) ***00101001110001101000100***

| Float64  | Maximum                  | Minimum                 |
| :------- | :----------------------: | :---------------------: |
| Positive | 3.4028234664 × 10 ^ 38   | 1.4012984643 × 10 ^ −45 |
| Negative | −1.4012984643 × 10 ^ −45 | −3.4028234664 × 10 ^ 38 |

[More info about Float32](https://en.wikipedia.org/wiki/Single-precision_floating-point_format)