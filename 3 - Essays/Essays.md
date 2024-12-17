### Recent Essays
```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "3 - Essays"
sort file.ctime desc
limit 5
```
