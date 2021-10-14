---
name: YAHTZEE!!!
about: Template for actions testing
title: Played Yahtzee! {{ date | date('dddd, MMMM Do h:mm') }}
labels: ''
assignees: ''

---

Someone just played a game of Yahtzee: 
Final roll is **{{env.num}}**


Today is: {{ date | date('dddd, MMMM Do h:mm') }}
Next week will be {{ date.duration(7, 'd') | date('dddd, MMMM Do h:mm') }}
