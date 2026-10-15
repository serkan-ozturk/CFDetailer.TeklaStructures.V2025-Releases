# Changelog

## 2.0.0 — 2026-10-15

- New machine-package generation: machine transfer packages are now built on SO.Domain.CFS 2.0. Update every installed machine package to its 2.x version together with this release; older machine packages will not load.
- Tabs are transferred with their height on the web and every bolt position: web tabs (two ears at the same X) no longer stop with a wrong-Y error. On SFS-CC75-300T, end tabs need the machine package 1.1.0 or newer, which also punches end tab bolts one by one at their own height.

<!-- fragments: DEVOPS-140.md, tab-readback.md -->
