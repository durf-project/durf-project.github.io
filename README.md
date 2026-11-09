# durf-project.github.io

The organisation site of the Dutch Repository Federation (DURF), published at
**https://durf-project.github.io/**.

This repository holds no content of its own. `index.html` forwards to the DURF home page,
which lives in [durf-project/project-page](https://github.com/durf-project/project-page)
and is published at https://durf-project.github.io/project-page/. Keeping the home page in
its own repository means its Markdown content and the bare HTML for the Netherlands Research
Portal stay together, while https://durf-project.github.io/ remains a short, stable address.

```
index.html   forwards to /project-page/ (meta refresh, with a script that keeps ?query and #anchor)
404.html     "page not found" for any unknown address under durf-project.github.io
LICENSE      EUPL v1.2
```

GitHub Pages serves each DURF repository under its own path:

| Address | Repository | What |
| --- | --- | --- |
| [/project-page/](https://durf-project.github.io/project-page/) | [project-page](https://github.com/durf-project/project-page) | Home: about, announcements, themes, documents |
| [/position-paper/](https://durf-project.github.io/position-paper/) | [position-paper](https://github.com/durf-project/position-paper) | Position paper |
| [/durf-gantt/](https://durf-project.github.io/durf-gantt/) | [durf-gantt](https://github.com/durf-project/durf-gantt) | Roadmap |
| [/durf-data-mesh-architecture/](https://durf-project.github.io/durf-data-mesh-architecture/) | [durf-data-mesh-architecture](https://github.com/durf-project/durf-data-mesh-architecture) | Data contracts |
| [/dashboards/](https://durf-project.github.io/dashboards/) | [dashboards](https://github.com/durf-project/dashboards) | Progress dashboards |
| [/durf-design-system/](https://durf-project.github.io/durf-design-system/) | [durf-design-system](https://github.com/durf-project/durf-design-system) | Shared styles, topbar and site menu |

The site menu on all these pages comes from the `SITES` list in `durf-nav.js` in
[durf-design-system](https://github.com/durf-project/durf-design-system). To change the
menu, change it there, not here.

## Licence

EUPL v1.2, see [LICENSE](LICENSE).
