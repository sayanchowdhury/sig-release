# Website Freeze Announcement Template

Use this template to announce the k/website repository freeze 24 hours before the release.

**When to use:** 24 hours before release day

**Where to post:** #sig-docs, #kubernetes-contributors, and #kubernetes-new-contributors Slack channels

---

## Message Template

```markdown
:megaphone: Hi everyone! 👋

We're on track to release v[future release] on [Day of Week]! 🎉

To prepare for the release, we're freezing k/website's main branch today. I've opened the freeze issue here: [Freeze k/website for Kubernetes v[future release] release](link-to-issue)

**What happens on release day:**
- Create the release-[current release] branch
- Merge the dev-[future release] Integration Branch into main
- Generate the reference docs
- Unfreeze k/website's main branch

Thank you for your patience and support during the freeze! Please reach out if you have any questions or concerns. 🙏
```

---

## Example

```markdown
:megaphone: Hi everyone! 👋

We're on track to release v1.35 on Wednesday! 🎉

To prepare for the release, we're freezing k/website's main branch today. I've opened the freeze issue here: https://github.com/kubernetes/website/issues/53638

**What happens on release day:**
- Create the release-1.34 branch
- Merge the dev-1.35 Integration Branch into main
- Generate the reference docs
- Unfreeze k/website's main branch

Thank you for your patience and support during the freeze! Please reach out if you have any questions or concerns. 🙏