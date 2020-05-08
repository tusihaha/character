# Character packing
### Export
**start({PackingType, String}) -> {ok, SpareType, PackedString} | {error, Reason}**

PackType: Loại packing `(sms, cbs, ussd)``
SpareType: Số bit padding

Reason: `Undefined method` khi sai loại PackingType, `Unknown charater` khi kí
tự không nằm trong bảng.
