---
name: Review of production-readiness 
about: A checklist to verify the repo meet the requiremeets needed to publish a tool on the candiapl production Multi-Messenger Portal (MMP)
title: "[Production Review]: <name of tool>"
labels: ''
assignees: ''
---
<!-- end YAML metadata -->

# Review of tool when moving from staging -> production

## Instructions

This issue should be created by the tool's developer when it is ready to be added to the production MMP. 

The tool should already be deployed on the staging MMP [Instuctions](https://github.com/CanDIAPL/MMP/tree/main/guides).

Please assign the reviewer to the issue. If you don't have a reviewer in mind, please ask on the relevant slack channel. 

## Summary of tool (to be written by the tool's developer)

Add a brief summary here of what the tool does and any details the reviewer should know

## Check-list (for the reviewer to fill in)
- [ ] 75% code coverage in unit testing
- [ ] Separate branches for staging and production (e.g. `staging` and `main`)
- [ ] It is clear how the tool is deployed (CD, Docker registry, etc)
- [ ] Someone has used the tool through the staging MMP portal

---

## Reviewer Sign-Off
- [ ] **Approved for Publishing:** All checklist items above have been verified.
