# Changelog

## 2.0.0 — 2026-10-16

- New machine-package generation: machine transfer packages are now built on SO.Domain.CFS 2.0. Update every installed machine package to its 2.x version together with this release; older machine packages will not load.
- Loading a license file again (same file name) no longer closes Tekla, and the license window shows the new status and remaining days right after loading.
- Tabs are transferred with their height on the web and every bolt position: web tabs (two ears at the same X) no longer stop with a wrong-Y error. On SFS-CC75-300T, end tabs need the machine package 1.1.0 or newer, which also punches end tab bolts one by one at their own height.

<!-- fragments: DEVOPS-140.md, license-load.md, tab-readback.md -->
