---
layout: article
title: Rezip epub folders
meta: Commands on rezipping epub
category: misc
tag: epub
---

Terminal (from within the epub directory).

```
zip -X0 "full path to new epub file" mimetype
zip -rDX9 "full path to new epub file" * -x "*.DS_Store" -x mimetype
```

Convert to MOBI, transfer to Kindle using Calibre.

