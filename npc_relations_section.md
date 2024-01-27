<%* 
const dv = this.app.plugins.plugins["dataview"].api 
%>
# Relatii
<%* let relations =""; dv.pages('"NPCs"').where(q => JSON.stringify(q).includes(tp.file.title) && q.file.name != tp.file.title).forEach(b => relations +=` - ${b.file.link}\n`);tR += relations%>
