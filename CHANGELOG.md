# Changelog

## v3.11.1 (07/07/2022)
## Changes
## 🐛 Hotfixes

- Modify to analyze pub dependency @dd-jy (#90)

---

## v3.11.0 (16/06/2022)
## Changes
## 🚀 Features

- Add to generate yaml format result @dd-jy (#88)

## 🔧 Maintenance

- Change the output for Go @dd-jy (#89)

---

## v3.10.1 (10/05/2022)
## Changes
## 🔧 Maintenance

- Add --direct option in help message @dd-jy (#87)

---

## v3.10.0 (10/05/2022)
## Changes
## 🚀 Features

- Support to comment direct/transitive type @dd-jy (#83)

---

## v3.9.4 (11/04/2022)
## Changes
## 🚀 Features

- Support Package.resolved v2 (swift) @dd-jy (#84)

## 🐛 Hotfixes

- Fix to show npm package license even if not spdx @dd-jy (#80)
- Fix the npm issue (no packages to install) @dd-jy (#79)

## 🔧 Maintenance

- Add a commit message checker @soimkim (#82)

---

## v3.9.3 (11/03/2022)
## Changes
## 🔧 Maintenance

- Apply f-string format @bjk7119 (#78)
- Comment out some sentences in the PR template @soimkim (#77)

---

## v3.9.2 (14/02/2022)
## Changes
## 🐛 Hotfixes

- Support local scm package for Cocoapods @dd-jy (#76)

---

## v3.9.1 (10/02/2022)
## Changes
## 🔧 Maintenance

- Modify to print output file name @bjk7119 (#75)

---

## v3.9.0 (13/01/2022)
## Changes
## 🚀 Features

- Modify to analyze the license name for carthage @dd-jy (#73)

## 🔧 Maintenance

- Update the README to add 'how it works without Internet' @dd-jy (#74)

---

## v3.8.0 (24/12/2021)
## Changes
## 🚀 Features

- Support GO package manager @dd-jy (#71)

## 🔧 Maintenance

- Update CONTRIBUTING guide @dd-jy (#72)
- Fix typo @syleeeee (#70)
- Update README.md @syleeeee (#68)
- Update LicenseRef-3rd_party_licenses.txt @dd-jy (#67)

---

## v3.7.6 (18/11/2021)
## Changes
## 🚀 Features

- Add setup.py installation for pypi @dd-jy (#63)

## 🐛 Hotfixes

- Fix the pypi result when pip-licenses package exists @dd-jy (#66)

## 🔧 Maintenance

- Change the log when it fails to detect the package manager @dd-jy (#65)
- Fix url for User Guide @JustinWonjaePark (#64)

---

## v3.7.5 (04/11/2021)
## Changes
## 🔧 Maintenance

- Add maven scope into comment of FOSSLight report @dd-jy (#62)

---

## v3.7.4 (21/10/2021)
## Changes
## 🐛 Hotfixes

- Fix a bug related to return sheet_list in main @soimkim (#59)

## 🔧 Maintenance

- Add '-f(format)' option and modify '-o' option. @dd-jy (#61)
- Return sheet_list and change sheet name to SRC_FL_Dependency @soimkim (#60)
- Change sheet name to SRC_FL_Dependency from SRC @soimkim (#57)
- Run PR action for all branches @soimkim (#58)
- Return sheet_list from main @soimkim (#56)

---

## v3.7.3 (07/10/2021)
## Changes
## 🔧 Maintenance

- Modify -o option to add output file name(.csv, .xlsx) @dd-jy (#55)

---

## v3.7.2 (30/09/2021)
## Changes
## 🐛 Hotfixes

- Add test scope in excludedScopes for maven plugin @dd-jy (#54)

## 🔧 Maintenance

- Refactoring the code @dd-jy (#53)

---

## v3.7.1 (16/09/2021)
## Changes
## 🐛 Hotfixes

- Print pip-licenses, PTable packages if it already exists @dd-jy (#51)
- Fix the pypi windows venv command error without virtualenv package @dd-jy (#50)

## 🔧 Maintenance

- Add gitattributes to exclude test directory for languages @dd-jy (#52)
- Update README.md @k2heart (#49)

---

## v3.7.0 (27/08/2021)
## Changes
## 🚀 Features

- Support carthage package manager @dd-jy (#48)

---

## v3.6.1 (25/08/2021)
## Changes
## 🚀 Features

- Support swift package manager @dd-jy (#45)

## 🐛 Hotfixes

- Fix the gradle license parsing error @dd-jy (#47)
- Fix a bug related release actions @soimkim (#46)
- Fix the maven license result parsing issue @dd-jy (#44)

## 🔧 Maintenance

- Fix the gradle license parsing error @dd-jy (#47)
- Set condition to use FOSSLight Util v1.1.0 or later @bjk7119 (#43)
- Merge init_log & init_log_item functiions @bjk7119 (#40)
- Update version in setup.py when released @bjk7119 (#38)
- change the pypi license separator from ';' to ',' @dd-jy (#37)
- Update CONTRIBUTING.md @bjk7119 (#36)

---

## v3.5.0 (14/07/2021)
## Changes
## 🐛 Hotfixes

- Fix the android scanning issues @dd-jy (#35)

## 🔧 Maintenance

- Fix the android scanning issues @dd-jy (#35)
- Move user-guide link to FOSSLight guide &  @dd-jy (#34)
- Add tox test for windows and MacOS @bjk7119 (#34)
- Add tox test for each package manger in Ubuntu environment @bjk7119 (#31)

---

## v3.4.0 (02/07/2021)
## Changes
## 🐛 Hotfixes

- Fix the windows executable file issue @dd-jy (#30)

---

## v3.3.0 (24/06/2021)
## Changes
## 🐛 Hotfixes

- Fix the pub parsing error @dd-jy (#29)

---

## v3.2.1 (24/06/2021)
## 🔧 Maintenance

- Update PR action commands @soimkim (#28)
- Update nomos standalone binary and source @dd-jy (#27)
- Update nomos standalone binary @dd-jy (#25)
- Update reuse related files @soimkim (#24)
- Change name to FOSSLight Dependency Scanner @dd-jy (#23)

---

## v3.2.0 (11/06/2021)
## Changes
## 🚀 Features

- add android dependency scanning @dd-jy (#21)

## 🔧 Maintenance

- change user guide @dd-jy (#22)

---

## v3.1.0 (10/06/2021)
## Changes
## 🐛 Hotfixes

- fix the executable file import error @dd-jy (#20)

## 🔧 Maintenance

- Add files for reuse compliance. @soimkim (#19)
- Update only CHANGELOG.md when releasing @soimkim (#18)
- Apply Tox Configuration & Change help message @bjk7119 (#17)

---

## v3.0.7 (17/05/2021)
## Changes
## 🔧 Maintenance

- Refactoring code and use fosslight_util @dd-jy (#15)
- Update user-guide.md @dd-jy (#14)
- Update contributing guide about DCO @dd-jy (#13)
- Update the pypi description to README.md @dd-jy (#12)
- Add 'cocoapods:' to oss name for cocoapods package @dd-jy (#11)
- Change oss name for cocoapods package manager @dd-jy (#10)
- Create CODE_OF_CONDUCT.md @dd-jy (#9)
- Add CONTRIBUTING.md @dd-jy (#8)

---

## v3.0.6 (25/03/2021)
## Changes
## 🐛 Hotfixes

- Fix the cocoapods error @dd-jy (#7)

## 🔧 Maintenance

- Update changelog @dd-jy (#6)
- Update github workflows @dd-jy (#5)
---

## v3.0.5 (19/03/2021)
## Changes
## 🚀 Features
- Support cocoapods package manager


---

## v3.0.4 (13/03/2021)
## Changes
## 🔧 Maintenance
- Add license file to wheel
---

## v3.0.3 (12/03/2021)
## Changes
## 🔧 Maintenance
- Modify to include binaries that analyze license text.
---

## v3.0.2 (05/03/2021)
## Changes
## 🐛 Hotfixes
- Fix to generate a single oss for multiple license names for npm, maven