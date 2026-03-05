This document is intended for authors and editors of the LISTA E-Control software documentation. It provides authors with the relevant guidance to ensure technical and stylistic consistency. 

# Documentation format

- Markdown standard basis: [CommonMark](https://spec.commonmark.org/0.31.2/)
- Extended with some **GitHub Flavored Markdown ([GFM](https://github.github.com/gfm/))** features, specifically:

[Alerts/captions](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts): See formatting conventions below for the specific tags used.

[Tables]() E.g:

| Column 1 | Column 2 |
| -------- | -------- |
| foo      | bar      |

# Formatting conventions

***Bold italic text*** indicates names of UI elements, like buttons, menu items, or field labels (e.g., ***Save***, ***Cancel***)

`Code text` indicates technical values and paths to specific screens (e.g. Go to ***`Settings > General`***, enter `100` pieces)

> [!WARNING]
> Warning callout to draw attention to undesirable effects, such as data loss.

> [!NOTE]
> Information callout to help the user understand the system and it's functions.

To do action item for document editors (remove from final publication): 
<!-- To do: -->
<!-- Action item(s) for document editors and reviewers... -->

Comment for document editors (remove from final publication): 
<!-- Comment: -->
<!-- Comment(s) for document editors and reviewers... -->



# Writing style (British English)

The writing style is defined here for British English, and should be adapted appropriately for translations, to best suit the regional markets targeted with specific language variants.

- Use **Oxford spelling** for international neutrality in technical contexts: Retain British features like **colour** but use **-ize/-ization** endings (e.g., authorize, organization, realize).
  https://en.wikipedia.org/wiki/Oxford_spelling
- Use **sentence case** for H1, H2, H3 etc. E.g. "About this documentation"
- The company name **LISTA** should always be capitalized
- The **product name** reference should always be **LISTA E-Control** (with no version number references)
- Refer to a specific **screen** rather than **page**, e.g. ***Login screen*** not ***Login page*** page. Screen names are capitalised (and stylised as UI elements), e.g. ***Scan screen***, ***Categories screen***
- When referring to **screen interactions**, use **click**, assuming that touchscreen users (with no mouse) will know they should **tap** on the screen with their finger. Where possible, use **select** if grammatically correct - normally for multiple options (e.g. "Select the ***Update existing users*** option").
- **Trailing periods in lists**: Do not use periods (full stops) at the end of items in bullet lists or numbered lists. This applies especially to procedural steps, instructions, and short descriptive items for maximum readability. List items should be concise imperatives or phrases without end punctuation. Only add a period if an individual item is a complex full sentence that includes punctuation.
- When referring to buttons, use the `[name`]+" button" format, e.g. "***Log out*** button", and not "***Log out*** icon"
- **Address the reader directly** Use second-person pronouns ("you", "your") to address the reader directly throughout the manual, especially in instructions, procedures, steps, and explanatory text. This creates a clear, engaging, and user-centered tone. e.g: " Enter your username and password".
- Capitalize software feature names, module names, screen titles, ensuring that they mirror the UI. E.g:
  - "Use the ***Pick Lists*** feature to..."
  - "Go to the ***Product Details*** screen..."
  - Note: Generic UI descriptors like screen, panel, page, section, tab, dialog, pane, window are not capitalized when they follow the name (unless the UI literally capitalizes them).

## Terminology

Summary of the terminology conventions and terms used in this documentation. Use these to ensure consistency.
### Log in / Log out

Use **log in** and **log out** (two words) as verbs in sentences and instructional headings that describe the action. E.g:

> Users must **log in** to access E-Control.

> **Log in** with username and password.

Use **login** and **logout** (one word) as nouns or adjectives, or when mirroring UI button/labels (that use the noun form). E.g:

> Enter your **login** credentials.

> ***Login*** screen / ***Logout*** button


