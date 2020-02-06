# ResumeSite
Site to host resume information. Pages are laid out and the information is filled in from a backend database. Features for the site include:
- Configurations for site styling, including color theme and fonts
- Configuration for base URL, in the case someone wants to host their own instance of this. Needed for fetching content from the back-end.
- Configuration for contact information, so users can define where contact attemps should be routed
- Mail information, in the case users want contact attempts to come from a mail address they manage

The site navigation is structured in such a way that it is built on the fly, based on defined pages. Back-end fetches are also structured in an automatic way.

Page templates include:
- User landing page where a user can introduce themselves.
- Showcase page (meant to be re-used multiple times). These pages are meant to showcase a single project / piece, and an extended description of the item.
- "About Me" page, where a person can talk more about themselves and their skills / accolades / etc.
  - Page includes resume or other document in one of the supported formats
    - PDF
    - PNG
    - JPG
