# Template for setting up reproducible projects
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-6-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

*A The Turing Way inspired project to enable reproducibility in data science.*

## About this Repository

This is a template for setting-up a research or data science project online, such as on GitHub.
This repository includes files and directories recommended for enabling reproducibility and collaboration in a project, as well as sharing of research objects.

This repository follows the recommendations and guidance provided in *[The Turing Way](https://the-turing-way.netlify.app/welcome)* handbook to data science.
When reusing this repository, please update information on your README page with information about your project.

<!--If reusing this repository, delete this section -->
## About README

On an online repository, such as GitHub, the project overview page is named ‘README’ which is equivalent to the main page of a website.
README page should describe the project -- what is the purpose of the project, who is involved, how to collaborate and where to find key resources.

To learn more about how to create a README.md file, please read the [Landing Page - README File](https://the-turing-way.netlify.app/project-design/project-repo/project-repo-readme.html) chapter in The Turing Way Guide for Project Design.

<!--If reusing this repository, delete this section -->

## Repo Structure

Inspired by [Cookie Cutter Data Science](https://github.com/drivendata/cookiecutter-data-science)

```
├── LICENSE
├── README.md          <- The top-level README for users of this project.
├── CODE_OF_CONDUCT.md <- Guidelines for users and contributors of the project.
├── CONTRIBUTING.md    <- Information on how to contribute to the project.
├── data
│   ├── processed      <- The final, canonical data sets for modeling.
│   └── raw            <- The original, immutable data dump.
│
├── docs               <- A default Sphinx project; see sphinx-doc.org for details
│
├── models             <- Trained and serialized models, model predictions, or model summaries
│
├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
│                         the creator's initials, and a short `-` delimited description, e.g.
│                         `1.0-jqp-initial-data-exploration`.
│
├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
│   └── figures        <- Generated graphics and figures to be used in reporting
│
├── project_management <- Meeting notes and other project planning resources
│
├── src                <- Source code for use in this project.
│   │
│   ├── data           <- Scripts to download or generate data
│   │   └── make_dataset.py
│   │
│   ├── models         <- Scripts to train models and then use trained models to make
│   │   │                 predictions
│   │   ├── predict_model.py
│   │   └── train_model.py
│   │
│   └── visualisation  <- Scripts to create exploratory and results oriented visualisations
│       └── visualise.py
└──
```

**Maintainers**

This repository is jointly developed and maintained by Open Research Community Building (led by Dr. Malvika Sharan) and Research Application Management (led by Dr. Aida Mehonic) teams under the Tools, Practices and Systems Research Programme at The Alan Turing Institute.

*Please create [an issue](../../issues) to share references or ideas related to the development of this project.*

🎯 Roadmap
---

### Checklist for setting an online repository 

- [ ] Add a README file
- [ ] Add a [CONTRIBUTING](CONTRIBUTING.md) file
- [ ] Add a [LICENSE](LICENSE.md)
- [ ] Add a [Code of Conduct](CODE_OF_CONDUCT.md)
- [ ] Install [all-contributors](https://allcontributors.org/) bot
- [ ] .gitignore file (choose from a template)
- [ ] Issue templates
    - [ ] Optionally Install [Welcome/behavior](https://github.com/behaviorbot/welcome) bot (see The Turing Way [config](https://github.com/alan-turing-institute/the-turing-way/blob/main/.github/config.yml))
- [ ] Create a directory with files for project management (meetings, report, proposals)
- [ ] Create a directory with files for communications
- [ ] Create a directory for research analysis
- [ ] Create a directory for research results/outcome to share (?)
- [ ] Create a directory for ethics approval and project policies
- [ ] Create a directory with files for stakeholders info and nature of engagement
- [ ] Connect repo with Zenodo
- [ ] Add cff file for citation
- [ ] Add badges

📫 Contact
---

For any organisation related queries or concerns, you can directly reach out to Malvika Sharan by emailing [msharan@turing.ac.uk](mailto:msharan@turing.ac.uk).

♻️ License
---

This work is licensed under the MIT license (code) and Creative Commons Attribution 4.0 International license (for documentation).
You are free to share and adapt the material for any purpose, even commercially,
as long as you provide attribution (give appropriate credit, provide a link to the license,
and indicate if changes were made) in any reasonable manner, but not in any way that suggests the
licensor endorses you or your use, and with no additional restrictions.

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="http://malvikasharan.github.io/"><img src="https://avatars.githubusercontent.com/u/5370471?v=4?s=100" width="100px;" alt="Malvika Sharan"/><br /><sub><b>Malvika Sharan</b></sub></a><br /><a href="#ideas-malvikasharan" title="Ideas, Planning, & Feedback">🤔</a> <a href="#content-malvikasharan" title="Content">🖋</a></td>
      <td align="center"><a href="https://github.com/EKaroune"><img src="https://avatars.githubusercontent.com/u/58147174?v=4?s=100" width="100px;" alt="Emma Karoune"/><br /><sub><b>Emma Karoune</b></sub></a><br /><a href="#ideas-EKaroune" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=EKaroune" title="Documentation">📖</a></td>
      <td align="center"><a href="http://www.aleesteele.com"><img src="https://avatars.githubusercontent.com/u/18509789?v=4?s=100" width="100px;" alt="Anne Lee Steele"/><br /><sub><b>Anne Lee Steele</b></sub></a><br /><a href="#ideas-aleesteele" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=aleesteele" title="Documentation">📖</a></td>
      <td align="center"><a href="https://github.com/vhellon"><img src="https://avatars.githubusercontent.com/u/93144591?v=4?s=100" width="100px;" alt="Vicky Hellon"/><br /><sub><b>Vicky Hellon</b></sub></a><br /><a href="#ideas-vhellon" title="Ideas, Planning, & Feedback">🤔</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=vhellon" title="Documentation">📖</a></td>
      <td align="center"><a href="http://jending.com"><img src="https://avatars.githubusercontent.com/u/5104098?v=4?s=100" width="100px;" alt="Jennifer Ding"/><br /><sub><b>Jennifer Ding</b></sub></a><br /><a href="#content-dingaaling" title="Content">🖋</a> <a href="https://github.com/alan-turing-institute/reproducible-project-template/commits?author=dingaaling" title="Documentation">📖</a> <a href="#ideas-dingaaling" title="Ideas, Planning, & Feedback">🤔</a></td>
      <td align="center"><a href="http://lappland.io"><img src="https://avatars.githubusercontent.com/u/51458?v=4?s=100" width="100px;" alt="Hilmar Lapp"/><br /><sub><b>Hilmar Lapp</b></sub></a><br /><a href="https://github.com/alan-turing-institute/reproducible-project-template/issues?q=author%3Ahlapp" title="Bug reports">🐛</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!
