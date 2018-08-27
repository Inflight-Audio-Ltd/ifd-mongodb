## MongoDB Native Driver transitional package

Help with migration from **Monk** driver version 1.0.1, to **MongoDB Driver** version 3.0.1.

It is not possible to have at the same time MongoDB Driver 1.4.40 and 3.0.1.

**Monk** driver version 1.0.1 doesn't have aggregation queries neither real promises, for example no `catch` clause.

**Monk** depends on Mongodb Driver version 1.4.40, and  Mongoskin 1.4.13.

**MongoDB** driver version 1.4.40 doesn't have promises.
