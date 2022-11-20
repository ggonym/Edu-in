# 2022_Project
### 안녕하세요. 저희는 메몽팀입니다.😁😁

> Note: 매순간 즐겁게 코딩을 하는...
**Requirements:**
  - Be called README.md (with capitalization).
  - If the project supports i18n, the file must be named accordingly: `README.de.md`, where `de` is the BCP 47 Language tag. For naming, prioritize non-regional subtags for languages. If there is only one README and the language is not English, then a different language in the text is permissible without needing to specify the BCP tag: e.g., `README.md` can be in German if there is no `README.md` in another language. Where there are multiple languages, `README.md` is reserved for English.
  - Be a valid Markdown file.
  - Sections must appear in order given below. Optional sections may be omitted.
  - Sections must have the titles listed below, unless otherwise specified. If the README is in another language, the titles must be translated into that language.
  - Must not contain broken links.
  - If there are code examples, they should be linted in the same way as the code is linted in the rest of the project.

## Table of Contents

_Note: This is only a navigation guide for the specification, and does not define or mandate terms for any specification-compliant documents._

- [Sections](#sections)
  - [Title](#title)
  - [Banner](#banner)
  - [Badges](#badges)
  - [Short Description](#short-description)
  - [Long Description](#long-description)
  - [Table of Contents](#table-of-contents-1)
  - [Security](#security)
  - [Background](#background)
  - [Install](#install)
  - [Usage](#usage)
  - [Extra Sections](#extra-sections)
  - [API](#api)
  - [Maintainers](#maintainers)
  - [Thanks](#thanks)
  - [Contributing](#contributing)
  - [License](#license)
- [Definitions](#definitions)

## Sections

### Title
**Status:** Required.

**Requirements:**
- Title must match repository, folder and package manager names - or it may have another, relevant title with the repository, folder, and package manager title next to it in italics and in parentheses. For instance:

  ```markdown
  # Standard Readme Style _(standard-readme)_
  ```

  If any of the folder, repository, or package manager names do not match, there must be a note in the [Long Description](#long-description) explaining why.

**Suggestions:**
- Should be self-evident.

### Banner
**Status:** Optional.

**Requirements:**
- Must not have its own title.
- Must link to local image in current repository.
- Must appear directly after the title.

### Badges
**Status:** Optional.

**Requirements:**
- Must not have its own title.
- Must be newline delimited.

**Suggestions:**
- Use http://shields.io or a similar service to create and host the images.
- Add the [Standard Readme badge](https://github.com/RichardLitt/standard-readme#badge).

### Short Description
**Status:** Required.

**Requirements:**
- Must not have its own title.
- Must be less than 120 characters.
- Must not start with `> `
- Must be on its own line.
- Must match the description in the packager manager's `description` field.
- Must match GitHub's description (if on GitHub).

**Suggestions:**
- Use [gh-description](https://github.com/RichardLitt/gh-description) to set and get GitHub description.
- Use `npm show . description` to show the description from a local [npm](https://npmjs.com) package.

### Long Description
**Status:** Optional.
