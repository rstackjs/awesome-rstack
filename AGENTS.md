# Repository guidelines

## Project list ordering

- Keep the existing README categories and subcategories. Apply these rules within every project list: Official Resources, Ecosystem, Skills, each Starter subsection, each Plugins subsection (including Loaders and Unplugin), Rstest Adapters, Rstest Utilities, Deployment, and Libraries.
- Preserve the ordering of the table of contents, the Rstack toolchain table, Blogs, and Videos; these are not project lists covered by this rule.
- Place official Rstack entries before community entries. For this list, official entries link to repositories owned by `rstackjs` or `web-infra-dev`, or to documentation for those projects. For website links, check the source repository's ownership rather than inferring it from the project name. Modern.js (`modernjs.dev`) belongs to `web-infra-dev/modern.js`. Projects maintained by other organizations belong to the community group, even if they are official integrations for those organizations.
- Within each of the official and community groups, place scoped packages (`@scope/name`) before unscoped packages. Sort scoped and unscoped packages separately by the full displayed name, A–Z, ignoring letter case. Retain the scope when comparing scoped packages. The ordering is: official scoped, official unscoped, community scoped, community unscoped.
- Insert new entries at their sorted position, preserving the existing link and description style. Do not add headings to separate official and community entries.
- Do not use repository activity, stars, or submission date to determine ordering.
- When reordering, preserve every entry's name, URL, description, and category. Check that no entries were lost or duplicated, and run `git diff --check`.
