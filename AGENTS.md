# Repository guidelines

## Project list ordering

- Keep the existing README categories and subcategories. Apply these rules within every project list: Official Resources, Ecosystem, Skills, each Starter subsection, each Plugins subsection (including Loaders and Unplugin), Rstest Adapters, Rstest Utilities, Deployment, and Libraries.
- Preserve the ordering of the table of contents, the Rstack toolchain table, Blogs, and Videos; these are not project lists covered by this rule.
- Place scoped packages (`@scope/name`) before unscoped entries. Sort scoped and unscoped entries separately by the full displayed name, A–Z, ignoring letter case. Retain the scope when comparing scoped packages.
- Insert new entries at their sorted position, preserving the existing link and description style. Do not add headings to separate scoped and unscoped entries.
- Do not use official status, repository ownership, activity, stars, or submission date to determine ordering.
- When reordering, preserve every entry's name, URL, description, and category. Check that no entries were lost or duplicated, and run `git diff --check`.
