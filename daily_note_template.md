---
tags:
  - DailyNote
aliases:
---
## ☕ Good morning...
>[!tip]+ 🎯 Main Focus Points
>- 

>[!todo]+ 📝 Today's Action Items
>- [ ] 
> ### Yesterday's Bridge
> ```dataview
LIST WITHOUT ID Work 
FROM #DailyNote 
WHERE file.cday = this.file.cday - dur(1 day)
FLATTEN Work
>```
## 👨‍💻 Get to Work...
> [!example]+ 💡 Ideas & Insights
>Some couple of #idea's
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
## 🌃 See you Tomorrow!
> [!cite] 💭 Reflection
>

> [!danger] 🌅 Tomorrow’s Focus
> 1. [Work:: I need to work on this tomorrow!]