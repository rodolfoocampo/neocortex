### All ideas

```dataview
table max(file.ctime, file.mtime) as "Recent Date", file.tags as "Area"
from "1 - Ideas"
where contains(file.tags, "Ideas")
sort max(file.ctime, file.mtime) desc
```
### Apps

```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "1 - Ideas"
where contains(file.tags, "Ideas/Apps")
sort max(file.ctime, file.mtime) desc
```
### Writing
```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "1 - Ideas"
where contains(file.tags, "Ideas/Writing")
sort max(file.ctime, file.mtime) desc
```

### Music
```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "1 - Ideas"
where contains(file.tags, "Ideas/Music")
sort max(file.ctime, file.mtime) desc
```

### Random
```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "1 - Ideas"
where contains(file.tags, "Ideas/Random")
sort max(file.ctime, file.mtime) desc
```

### Leonardo
```dataview
table max(file.ctime, file.mtime) as "Recent Date"
from "1 - Ideas"
where contains(file.tags, "Ideas/Leonardo")
sort max(file.ctime, file.mtime) desc
```







