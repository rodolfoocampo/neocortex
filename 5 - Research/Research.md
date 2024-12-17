### Recent Notes
```dataview
table file.folder as "Folder", max(file.ctime, file.mtime) as "Recent Date"
from "5 - Research"
sort max(file.ctime, file.mtime) desc
limit 5
```
