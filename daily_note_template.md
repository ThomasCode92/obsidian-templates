---
tags:
  - DailyNote
---
## 🧭 Today’s Plan
>[!tip]+ 🎯 Main Focus Points
>- 

>[!todo]+ 📝 Today's Action Items
>- [ ] 
> ### Carryover Tasks
> ```dataview
LIST WITHOUT ID Work 
FROM #DailyNote 
WHERE file.cday = this.file.cday - dur(1 day)
FLATTEN Work
>```
## 🚀 Work Log
> [!example]+ 💡 Observations & Insights
>

> [!abstract]+ 📌 Important Notes
> Some couple of #idea's
>- [idea:: A Great Idea!]

> [!note] 📓 Activity Notes
> ### Edited notes
>  ```dataview
>LIST
>FROM ""
>WHERE file.mday = this.file.day
>AND file.cday != this.file.day
>AND !contains(file.path, "Daily")
>SORT file.mtime DESC
>  ```
> ### Created Notes
> ```dataview
>LIST
>FROM ""
>WHERE file.cday = this.file.day
>AND !contains(file.path, "Daily")
>SORT file.ctime ASC
> ```
## ✅ Wrap-Up
> [!danger] 🌅 Tomorrow’s Focus
> 1. [Work:: I need to work on this tomorrow!]