# Repository guidelines

## Plugin list ordering

- Keep the existing README categories and subcategories. Sort entries within each existing list under `## Plugins`, including Rspack Loaders, each Rsbuild framework subsection, Common, and Unplugin.
- Place official Rstack entries before community entries. For this list, official entries link to repositories owned by `rstackjs` or `web-infra-dev`, or to official Rstack plugin documentation. Plugins maintained by other projects belong to the community group, even if they are official integrations for those projects.
- Within each of the official and community groups, place scoped packages (`@scope/name`) before unscoped packages. Sort scoped and unscoped packages separately by the full displayed name, A–Z, ignoring letter case. Retain the scope when comparing scoped packages. The ordering is: official scoped, official unscoped, community scoped, community unscoped.
- Insert new entries at their sorted position, preserving the existing link and description style. Do not add headings to separate official and community entries.
- Do not use repository activity, stars, or submission date to determine ordering.
- When reordering, preserve every entry's name, URL, description, and category. Check that no entries were lost or duplicated, and run `git diff --check`.
