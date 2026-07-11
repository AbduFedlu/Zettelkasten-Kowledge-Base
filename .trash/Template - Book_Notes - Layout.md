
---
cssclass: book-notes
---

<div class="book-notes">
<%* 
const pages = await tp.system.prompt("How many pages?");
for (let i = 1; i <= parseInt(pages); i++) { 
%>
<div class="entry">
<div class="left">p.<% i %></div>
<div class="right"></div>
</div>
<%* } %>
</div>

