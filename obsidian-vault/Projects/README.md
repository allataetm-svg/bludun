# Projects

Projeleri burada tutun. Her proje bir dosya veya klasör olabilir ve `tags: [project]` içermelidir.

Dataview örneği (aktif projeler):

```dataview
table file.link as Project, status as Status, due as Due
from "Projects"
where contains(tags, "project")
sort due asc
```

Yeni proje oluşturmak için `Templates/project.md` şablonunu kullanın.
