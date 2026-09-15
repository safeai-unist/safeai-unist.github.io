# UNIST Safe AI Lab — Editing Guide

Open `dist/index.html` in your browser. No installation is required. Keep `index.html`, `app.js`, `content.js`, and the `assets` folder together. The downloadable ZIP puts these files at its top level.

## Change the content

Open `dist/content.js` in a text editor such as VS Code. Search for a person's name, paper title, or project title and edit the quoted values. Save the file and refresh your local browser preview.

- `home`: home page text and banner. Put a new image in `assets`, then set `bannerImage` to its relative path, such as `assets/banner.jpg`. An empty value shows the plain background. `bannerPosition` controls cropping (for example, `center center` or `center 30%`).
- `professor`: name, role, biography (two paragraphs), email, website and photo.
- `members`: sections and member records. Each record has `name`, `photo`, `interest`, `period`, and `email`. Copy an existing record to add a member.
- `projects`: title, description, period and status. Use exactly `Ongoing` or `Completed` for status.
- `publications`: title, authors, venue, year, type (`Conference` or `Journal`), scope (`International` or `Domestic`), and translated (true for translated titles).
- `courses`: term, title and level (`Undergraduate` or `Graduate`).
- `memories`: title, date, description and a list of photo paths.

Research descriptions and the professor's education/experience are in `dist/app.js`. Layout and colors are in `dist/index.html`.

This version does not include a click-to-edit inline editor. Browser developer-tool edits are temporary and do not save to the source. You can also request changes in this Codex task or use Sites > Edit to describe changes. Saved local edits do not update the hosted website automatically; ask Codex to publish the edited files.

## Project checkboxes

All selects or clears both statuses. Ongoing and Completed can be checked independently. All is partially checked when only one status is selected. Selecting no statuses displays an empty-state message.

## Source and review notes

Content was imported from the lab's existing public site on September 14, 2026:
https://sites.google.com/view/safe-ai-lab/home

The first draft contains 10 people, 8 projects (3 ongoing, 5 completed), 46 publications, 7 courses, and 13 memory albums. Current status, dates and affiliations follow the original site; this is not an independent verification of every entry.

- Original `Ph.D. Candidates` were provisionally placed under `M.S-Ph.D combined`, as requested. Please confirm degree tracks.
- Original undergraduate students were provisionally placed under `Intern`. Please confirm appointments.
- Alumni emails and photos were not listed; these fields are left empty.
- Korean domestic paper titles were translated into English and marked `English translation`. These are draft translations, not verified official English titles.
- Publication groups use International / Domestic because the source did not identify selected publications.
- Project titles were shortened for readability; dates, statuses and available role information follow the source.
- Education and core academic appointments were transferred. Other professional activities and awards are not included in this first draft.
- Memory captions were translated and lightly expanded from the original captions. Please review dates and conference names.
- The incorrect home banner has been cleared. Set `home.bannerImage` to your chosen image before publishing.
- Project source: https://sites.google.com/view/safe-ai-lab/projects
- Professor: https://sites.google.com/view/safe-ai-lab/people/professor
- Members: https://sites.google.com/view/safe-ai-lab/people/members
- Publications: https://sites.google.com/view/safe-ai-lab/publications
- Courses: https://sites.google.com/view/safe-ai-lab/lectures
- Memories: https://sites.google.com/view/safe-ai-lab/people/memories

## Website address

Where available, the site owner can use Sites > Settings > Change URL. A custom domain can be connected through Settings > Add domain when supported, and requires control of the domain's DNS settings. This does not change your original Google Sites address.

Official instructions: https://learn.chatgpt.com/docs/sites
