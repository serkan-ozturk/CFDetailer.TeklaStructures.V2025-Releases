# Changelog

## 2.0.0 — 2026-10-18

- New machine-package generation: machine transfer packages are now built on SO.Domain.CFS 2.0. Update every installed machine package to its 2.x version together with this release; older machine packages will not load.
- End tabs take their width (the web between the flanges) and their end plate height (the flange width) from the profile when they are left empty, so they no longer have to be entered for every profile. End tabs with a notch still need their width entered.
- Loading a license file again (same file name) no longer closes Tekla, and the license window shows the new status and remaining days right after loading.
- Adding a machine package copies only the machine DLL into the Machines folder (no more .nupkg and .nuspec copies). Updating a machine that is already loaded no longer fails: the new version is used after Tekla Structures is restarted.
- Tabs are transferred with their height on the web and every bolt position: web tabs (two ears at the same X) no longer stop with a wrong-Y error. On SFS-CC75-300T, end tabs need the machine package 1.1.0 or newer, which also punches end tab bolts one by one at their own height.
- A mid tab can place two ears at the same position in one step (WEB TAB on SFS-CC75-300T: one hit of the die makes both ears).
- Release packages carry the version in their file name (e.g. CFDetailer.TeklaStructures.V2025-2.0.tsep).

<!-- fragments: DEVOPS-140.md, endtab-size-from-profile.md, license-load.md, machine-install.md, tab-readback.md, web-tab-ear-pair.md -->
