<%* 
const dv = this.app.plugins.plugins["dataview"].api 
%>
# Quest-uri 
<%* 
let quests ="";
dv.pages('"Quests"').where(q => JSON.stringify(q).includes(tp.file.title) && q.file.name != tp.file.title).forEach(b => quests +=` - ${b.file.link}\n`)
 tR += quests
%>