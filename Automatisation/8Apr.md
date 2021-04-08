# 3 main goals to explore

( https://docs.google.com/spreadsheets/d/1boMLKo-tNyKYdBQ3rQTAhwTrTgNMQJLknb_x-Sfdako/edit#gid=0 : legacy document on the various sources )

## 1 - Anti-scam service

#### Use a txt list of host

A text list of compromised/scam hosts. When a user would visit a host from this list a notice would appear 
e.g. 
```
Ce site a été signalé comme frauduleux. Nous vous conseillons de quitter cette page.
```

This could be **easy** to implement and a **quick** win.

The following project could be perfect :
https://github.com/durablenapkin/scamblocklist

#### Use an api or self-hosted AI service

This would probably increase the amount of pages targeted and would hence make it more relevant.
Though technical side would be hard to implement if we don't use a paid service, and might cost us bandwidth.

paid service : https://www.scampredictor.com/tarifs/ (already used by signal-arnaque)

Free AI : https://github.com/bolster-inc/neo (checkphish.ai)
