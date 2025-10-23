## 👥 Team Members

| Name | GitHub Username |
|------|------------------|
| **Khalil Ghanem** | [@khalilgh1](https://github.com/khalilgh1) |
| **Hacene Serine Nour El Imane** | [@serlolz](https://github.com/serlolz) |
| **Chakib Belamri** | [@cha-ki-b](https://github.com/cha-ki-b) |
| **Lydia Khalem** | [@Lyydie](https://github.com/Lyydie) |
| **Essedik Abdel Rahim Bachounda** | [@lordseddik](https://github.com/lordseddik) |

## Website Link:
https://khalilgh1.github.io/team-portfolio-project/

## Team Retrospective Analysis

During the development of our team portfolio website, the most significant technical challenge we encountered was managing version control efficiently while multiple members worked on different sections simultaneously. Since the project involved several HTML pages and shared assets like stylesheets and JavaScript files, ensuring consistent project structure and avoiding overwriting each other’s work required careful coordination. Early in the process, we realized that our initial Git workflow lacked strict conventions for folder organization and branching, which later led to merge conflicts and confusion about where files should reside.

One notable merge conflict occurred when the initial project structure was pushed to the develop branch. The original setup had all the HTML, CSS, and JavaScript files placed directly in the root directory. Meanwhile, Chakib reorganized the structure by creating dedicated folders for styles and scripts, moving the respective files accordingly. When we later attempted to merge our changes, Git could not automatically reconcile the differences, as the same files had been modified and relocated in different commits. To resolve the conflict, we first reviewed the commit history to understand the scope of the changes. We then manually compared both versions, accepted the new directory structure, and carefully adjusted all relative paths in the HTML files to ensure that style and script links still worked correctly. Once everything was tested locally, we committed the resolved version and merged it into the main branch.

The pull request and peer review process proved to be highly effective in maintaining code quality and consistency. Each merge request was reviewed by at least one teammate, allowing us to catch small mistakes, such as broken paths or missing links (most frequent issues we had), before deployment. This process also encouraged clearer commit messages and better communication between members. Overall, these collaborative practices helped us improve the structure, readability, and maintainability of the final website, turning the initial merge challenge into a valuable learning experience for our team’s workflow.

