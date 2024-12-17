### Recent Notes
```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "2 - Notes"
sort max(file.ctime, file.mtime) desc
limit 5
```
