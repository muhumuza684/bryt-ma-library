# Bryt Ma Library

A working library of book concepts, structures, front matter, sources, and research guidance. Each title has up to three files: a **project file** (concept, structure, status), a **front-matter file** (cover copy, title, subtitle, introduction, appendices), and, for fact-heavy titles, a **sources file** (research notes, kept separate from the manuscript). A **master guide** and **style guide** tie the whole library together.

## Start Here
1. Read [`MASTER-GUIDE.md`](MASTER-GUIDE.md): how to research each title, what to always add, what to always avoid.
2. Read [`STYLE-GUIDE.md`](STYLE-GUIDE.md): the voice that should run across every book.
3. Check [`PROGRESS.md`](PROGRESS.md): what's done, what's next, across all 11 book titles.

## Book Index

| # | Title | Project File | Front Matter | Sources | Finished Files |
|---|-------|--------------|---------------|---------|-----------------|
| 01 | Similar =/= Same | [books/01](books/01-similar-not-same.md) | [front-matter/01](front-matter/01-similar-not-same-front-matter.md) | - | - |
| 02 | The Chokepoint | [books/02](books/02-the-chokepoint-hormuz.md) | [front-matter/02](front-matter/02-chokepoint-front-matter.md) | [SOURCES/02](SOURCES/02-the-chokepoint-sources.md) | - |
| 03 | God of Balimwezo (3 volumes) | [books/03](books/03-god-of-balimwezo-series.md) | [front-matter/03](front-matter/03-god-of-balimwezo-front-matter.md) | [SOURCES/03](SOURCES/03-god-of-balimwezo-sources.md) | [books/god-of-balimwezo-omnibus](books/god-of-balimwezo-omnibus/) |
| 04 | She Da Moon | [books/04](books/04-she-da-moon.md) | [front-matter/04](front-matter/04-she-da-moon-front-matter.md) | [SOURCES/04](SOURCES/04-she-da-moon-sources.md) | - |
| 05 | Cries to Mbale | [books/05](books/05-cries-to-mbale.md) | [front-matter/05](front-matter/05-cries-to-mbale-front-matter.md) | - | - |
| 06 | When Agie Left | [books/06](books/06-when-agie-left.md) | [front-matter/06](front-matter/06-when-agie-left-front-matter.md) | - | - |
| 07 | Retries | [books/07](books/07-retries.md) | [front-matter/07](front-matter/07-retries-front-matter.md) | - | - |
| 08 | Die to Live | [books/08](books/08-die-to-live.md) | [front-matter/08](front-matter/08-die-to-live-front-matter.md) | - | - |
| 09 | AbleTech | [books/09](books/09-abletech.md) | [front-matter/09](front-matter/09-abletech-front-matter.md) | - | - |
| 10 | Blind on Purpose | [books/10](books/10-blind-on-purpose.md) | [front-matter/10](front-matter/10-blind-on-purpose-front-matter.md) | - | - |
| 11 | Everyone Has a Language | [books/11](books/11-everyone-has-a-language/) | - | - | [Book 11 Project Guides](books/11-everyone-has-a-language/FINAL_BOOK_3_LANGUAGE_PROJECT_GUIDES.zip) |

## Technology Course Library

The technology course library contains 11 structured technology course projects.

| # | Course | Main Focus |
|---|--------|------------|
| 01 | The Hidden Power of the Command Line | CMD, PowerShell, Permissions, and the Windows Control Surface |
| 02 | The Power of Electron | From Web Technologies to Desktop Applications, Automation, and Native Capabilities |
| 03 | Pipelines | How to Design, Build, Automate, and Scale Reliable Software Delivery |
| 04 | The Power of Chatbots & APIs | How Conversational Systems Connect People, Software, and Services |
| 05 | The Hidden Power of npm & Daemons | Packages, Scripts, Processes, and the Machinery Behind Modern JavaScript Systems |
| 06 | The Great Mobile Choice | React Native and Flutter — Why, Where, When, How, and When Not to Use Each |
| 07 | Building IDEs | Why Developer Environments Matter, How They Work, and When to Build Your Own |
| 08 | The Power of Research | How to Ask Better Questions, Find Evidence, Test Ideas, and Build With Confidence |
| 09 | MCP | Why the Model Context Protocol Exists, What It Solves, and How to Build With It |
| 10 | The Data Lake | Why Data Needs a Place to Flow, When to Use One, and How to Build It Well |
| 11 | Compare | The Power of Making Better Technical Choices |

The complete course package is preserved here: [FINAL_TECH_COURSE_LIBRARY_GUIDES.zip](courses/technology-course-library/FINAL_TECH_COURSE_LIBRARY_GUIDES.zip)

Book 03, God of Balimwezo, is the first title in the library with finished, print-ready files: a complete interior PDF, a cover PDF sized for print (with spine width calculated from the actual page count), and a combined reading edition. See [books/god-of-balimwezo-omnibus](books/god-of-balimwezo-omnibus/) for all three.

## Repo Structure
```
bryt-ma-library/
├── README.md              you are here
├── MASTER-GUIDE.md         research and writing standards for all books
├── STYLE-GUIDE.md          the voice across the whole library
├── PROGRESS.md             status tracker for all 11 book titles
├── books/                  concept, structure, research notes, and packaged book projects per title
│   ├── 11-everyone-has-a-language/  packaged Book 11 project guides
│   │   └── FINAL_BOOK_3_LANGUAGE_PROJECT_GUIDES.zip
│   └── god-of-balimwezo-omnibus/   finished PDFs for the first completed title
├── courses/
│   └── technology-course-library/
│       └── FINAL_TECH_COURSE_LIBRARY_GUIDES.zip
├── front-matter/           cover copy, title, subtitle, intro, appendices per title
├── SOURCES/                research notes for fact-heavy books, kept out of the manuscript itself
├── PROMPTS/                master prompts for generating full manuscripts with an AI writing assistant
└── VISUALS/                illustration briefs (cartoon/anime style) for chapter art, avoiding real photos
```

## How to Use This Repo
Each book stands on its own. Open its `books/` file for the full structure, its `front-matter/` file for ready-to-use cover copy and introduction text, and (where it exists) its `SOURCES/` file for the research backing it up. Check `PROGRESS.md` before starting a session to see what's already done, and skim `STYLE-GUIDE.md` and the relevant section of `MASTER-GUIDE.md` to stay consistent.

## Author
Starboy, Bryt Ma Tech Uganda, Mbarara, Uganda.
