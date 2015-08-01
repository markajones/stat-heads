---
layout: article
title: SAS reminders 001
meta: Some SAS stuff that I tend to forget
category: sas
tag: sas
---

In the `data` definition set a `debug` option:

```
data sasdata.life / debug;
    set sourcedata;
    * more stuff
run;
```

Debugger commands:




