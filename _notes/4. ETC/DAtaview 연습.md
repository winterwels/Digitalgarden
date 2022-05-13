```dataview
LIST
FROM "0. Inbox"
SORT file.size DESC
LIMIT 10
```

---
alias: "document"
last-reviewed: 2021-08-17
thoughts:
  rating: 8
  reviewable: false
---
```
---
author: 어쩌구
date: 2022-02-16
rating: ㅁㅁㅁㅁㅁ
tags: books, creativity, writing
---
```


```dataview
TABLE author AS "작가", date AS "읽은 날짜", rating AS "평가"
FROM #books 
SORT date DESC
```

```dataview
TASK from #목표 
```

---
type: 'management'
date: '2022-02-16'
tags: ['timecheck']
---