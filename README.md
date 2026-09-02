# Introduction to Digital Humanities

Course website for **Introduction to Digital Humanities**, taught annually in the autumn
semester at the University of Bern (Walter Benjamin Kolleg / Digital Humanities).

Co-taught by Tobias Hodel, Elena Spadini and Francesco Beretta.

🌐 <https://dhbern.github.io/introduction-to-dh/>

|                      |                                                                                                                          |
| -------------------- | ------------------------------------------------------------------------------------------------------------------------ |
| Semester             | Autumn Semester 2026 (HS 2026)                                                                                           |
| Time                 | Tuesdays, 10:15–12:00                                                                                                    |
| Room                 | Unitobler, Lerchenweg 36, F-112                                                                                          |
| First / last session | 15 September 2026 / 15 December 2026                                                                                     |
| Companion course     | [DH Lab](https://dhbern.github.io/dh-lab/) ([repo](https://github.com/DHBern/dh-lab))                                    |
| Course materials     | [ILIAS](https://ilias.unibe.ch/ilias.php?baseClass=ilrepositorygui&cmdNode=yv:ng&cmdClass=ilObjCourseGUI&ref_id=3733960) |

The course is compulsory for the MA Major and MA Minor in Digital Humanities and open to
students from other programmes, in particular History, Near Eastern Studies and German Studies.

## Structure

```
contents/
  home.qmd          course description, organisation, joint weekly programme
  syllabus.qmd      all 14 sessions with readings
  sessions/NN.qmd   one page per session
  assignment.qmd    assessment brief
  resources.qmd     tools, standards, reference works
  blog.qmd          student project sites
  posts/            student contributions
  about.qmd         teaching team, licence, related sites
  bibliography.bib  all readings
```

## Local development

Requires [Quarto](https://quarto.org/docs/get-started/).

```bash
quarto preview      # live preview
quarto render       # build to _site/
npm install         # dev tooling (prettier, husky, commitizen)
npm run format      # format sources
```

## Deployment

Pushing to `main` triggers `.github/workflows/quarto-publish.yml`, which lints, renders,
optimises, checks for dead links and deploys to GitHub Pages.

## Contributing

Corrections and suggestions are welcome — open an
[issue](https://github.com/DHBern/introduction-to-dh/issues/new/choose) or a pull request. See
[CONTRIBUTING.md](CONTRIBUTING.md) and the [Code of Conduct](CODE_OF_CONDUCT.md).

## Licence

- Text and teaching materials: [CC BY-SA 4.0](LICENSE-CCBYSA.md)
- Code: [AGPL-3.0](LICENSE-AGPL.md)

Third-party material, readings in particular, remains under its own licence.
