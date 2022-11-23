# Character Packing

Character packing - SMS, CBS and USSD packing.

## Compile
```
1> c(pack).
```
## Usage
```
pack:start({PackingType, String}) -> {ok, SpareType, PackedString} | {error, Reason}
```

PackType: `(sms, cbs, ussd)`

SpareType: Number of padding bit

Reason: `(Undefined method, Unknown charater)`

## Reference

[ETSI TS 123 038](https://www.etsi.org/deliver/etsi_ts/123000_123099/123038/05.00.00_60/ts_123038v050000p.pdf)
