# 3 main goals to explore

( https://docs.google.com/spreadsheets/d/1boMLKo-tNyKYdBQ3rQTAhwTrTgNMQJLknb_x-Sfdako/edit#gid=0 : legacy document on the various sources )

## 1 - Anti-scam service

#### Use a txt list of host

> coverage : 4/5
> Notice quality : 2/5
> Expected traffic : 2/5

A text list of compromised/scam hosts. When a user would visit a host from this list a notice would appear 
e.g. 
```
Ce site a été signalé comme frauduleux selon scamblocklist, groupe de dev qui recense les sites à risque. Nous vous conseillons de quitter cette page.
```

This could be **easy** to implement and a **quick** win.

The following project could be perfect :
https://github.com/durablenapkin/scamblocklist

#### Use an api or self-hosted AI service

> coverage : 5/5
> Notice quality : 2/5
> Expected traffic : 4/5
 
This would probably increase the amount of pages targeted and would hence make it more relevant.
Though technical side would be hard to implement if we don't use a paid service, and might cost us bandwidth.

- paid service : https://www.scampredictor.com/tarifs/ (already used by signal-arnaque)
- paid service : https://checkphish.ai/plans/

- Free AI : https://github.com/bolster-inc/neo

## 2 - Create a new __éclaireur__ from twitter feed


> coverage : 2/5
> Notice quality : 4/5
> Expected traffic : ?

Now that the twitter POC has been made, we should try it creating a new éclaireur (at least in dev).

Twitter that could be used  for the fisrt try :
https://twitter.com/sebsauvage_net

## 3 - Offer DRM-free alternatives to games


> coverage : 3/5
> Notice quality : 4/5
> Expected traffic : 4/5

GOG is a DRM free video games store. Other Games stores offer the same games from GOG, but with DRM. 
This idea is when visiting a store page, have a notice show :
```
Ce jeu est displonible en version sans DRM sur GOG.com pour XX€
```

The website https://www.gogdb.org/ does that by pluging itself to official gog api as explained here https://new.gogdb.org/moreinfo

This solution would add a whole new dimension to our offer and may bring in a new demographic.

## 4 - OpenBeautyFact

> coverage : 4/5 (with Xpath)
> Notice quality : 4/5
> Expected traffic : 3/5


OpenBeautyFacts cold give some information including a score for a given product. Api is open.

Notice example : 
```
Ce produit a reçu un eco-score de 2/5. Regardez plus de détails sur cette page.
```
