---
date: <%tp.date.now("YYYY-MM-DD")%>T<%tp.date.now("HH:mm")%>
tags:
  - Daily
cssclasses:
  - daily
  <% "- " + tp.date.now("dddd", 0, tp.file.title, "DDMMYYYY").toLowerCase() %>
---
# DAILY NOTE
## <% tp.date.now("dddd, MMMM Do, YYYY", 0, tp.file.title, "DDMMYYYY") %>

***
### Journal

==<u>Day’s thought:</u>== 

<u>Day’s conquer:</u>

<u>Day’s summary:</u>

***
### Tasks

> [!todo]+ To do
> - [ ] Task 1
> - [ ] Task 2
> - [ ] Task 3

>[!attention]+ Lembretes!
>- Tome Whey e Creatina!
>- Ligue para os Pais
>- Cheque OKRs