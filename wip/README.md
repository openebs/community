# Welcome to our community...
[![OpenEBS Welcome Banner](/images/openebs_community_banner_retro_gamer.png)](https://www.openebs.io/)

## [openebs.io](https://www.openebs.io/)
<BR>

## Work In Progress (WIP) <BR>
> [!IMPORTANT]
> Test This directory is for the Maintainers to manage community docs that are in early devlopment, under constant editorial review but are not yet ready for public conumption or comment yet.<BR>
<BR>

> **This WIP folder** is managed by the OpenEBS Admins, Maintainers and Senior leaders in the OpenEBS project team.
> Currently it is being curated by... <BR>
>
> :rocket: &nbsp; Ed Robinson | @edrob999 <BR>
> :star: &nbsp; David Brace | @orville-wright <BR>
> :zap: &nbsp; Vishnu Attur | @avishnu <BR>
> :sunglasses: &nbsp; Tiago Castor | @tiagolobocastro <BR>

<BR>
<BR>
This is change. Change is coming. You can run but you can't hide....
<BR>
<BR>
This is how you structure your COMMITT messages...
<BR>

---
> [!IMPORTANT] <BR> 
> **type** &nbsp;&nbsp;  **(scope):** &nbsp;&nbsp; **subject/description** &nbsp;&nbsp;  **meta** <BR>
<BR>

**Type of work**: 

The **Type** keyword that many people quickly look for. So its very important to make it accurate.<BR>
It references the type of work that you have done. 

| Type code | Description of what this type code means |
| :---      | :---          |
| chore:    | Changes to the build process or auxiliary tools and libraries such as documentation generation |
| docs:     | Documentation only changes |
| feat:     | A new feature |
| fix:      | A bug fix     |
| hack:     | Hacking on some code to figure something out | 
| perf:     | A code change that improves performance |
| refactor: | A code change that neither fixes a bug nor adds a feature |
| style:    | Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc) |
| test:     | Adding missing tests |
<BR>

---

**Scope of work**

The **Scope**  is a 1 word keyword. It generally references the thing, module, package, file or entity that you were working on that has been impacted/changed. You can make up your own scope keywords, but try to be consistent with them becasue this represents your style and how you want people to quickly understand the work that you have done.<BR>

> For example: when committing to openebs/maya repo, the scope can be...<BR>

| Scope  code | Description of what your scope of work fociused arround |
| :---        | :---                                                    |
| keywords    | mayactl, m-apiserver, spc-watcher, cast, install, util  |
| keywords    | compile, travis-ci, bors |

> For example: when committing to docs or readme's that are NOT complex engineering code modules/files, the scope can be...<BR>

| Scope  code | Description of what your scope of work focused arround |
| :---        | :---                                                    |
| keywords    | typo, headings, restructure, tidy, polish |
| keywords    | format, images, links, table |

---

**Subject / Description**

The **Subject/Description** is a free format description of what work you did & why.
- It should be a short succinct description of the change
- use imperative, present tense: “change” not “changed” nor “changes”
- don't capitalize first letter
- no dot (.) at the end
- avoid special characters (e.g.  @, #, !, ', <>, [] etc )
- be aware that users will view this info via differnt GIT tools (e.g. cli, IDE, WebApp, MobileApp, Browser, API, JSON etc) and each app will truncate the info differntly. So shorter the better. 10 words if a fairly good limit. 
<BR>
---
**Meta**

We generally do not use the  **Meta** keyword. It provides embeded API/App control commands to CI-Pipeline tools and GitHub Enabled apps, or scripts the process output (txt/json). You can avoid it unless you absolutely need it. 