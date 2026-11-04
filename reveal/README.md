# Entry #1 – revealed pre-registration

Entry #1 has failed. This folder reveals the frozen experiment as it stood at its start on 2026-10-17:
version, start, deadline, the seven rules (original German wording) and all 201 strategies.

## Check it yourself
The SHA-256 of `entry-1.frozen.json` must equal the fingerprint published in
`proof/entry-1-fingerprint.txt`, which is timestamped on the Bitcoin blockchain via OpenTimestamps
(`proof/entry-1-fingerprint.txt.ots`, added on 2026-10-20).

```
sha256sum reveal/entry-1.frozen.json
# 4b2a41b06fe4615331e0ca2f17bf5f54db78bddd2dbf302612cafd973e8d2a35
```

So the rules and strategies were not changed after the start.

## Result
All strategy families failed under their own rules (loss limit or deadline). A later, stricter offline
search (v2 to v4: hourly and weekly bars, trend, mean reversion, breakout, relative strength, time effects)
also found no edge after costs. No real money was traded.
