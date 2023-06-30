<%*
let cat = await tp.system.prompt('Insert category: ')
let topic = await tp.system.prompt('Insert the topic TAG:  ')
let platF = await tp.system.prompt('Insert platform or lab: ')
let link = await tp.system.prompt('Insert the link to learning site:  ')
-%>

*Tags:* #<%cat%> #<%platF%> #<%topic%>

---
*Alias:* <% tp.file.title %>
*Date:* <% tp.date.now('DD-MM-YYYY')%>
*Platform/lab:* <%platF%>
*Category:* <%cat%>


---

# Notes for: <% tp.file.title %>

## Cheat-sheet

- - -

## Topics 📖 


- - -
### Resources 

| 00  | Link     | Comment | tag |
| --- | -------- | ------- | --- |
| 01  | <%link%> |         |     |

