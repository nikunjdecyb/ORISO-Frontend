# Evidence for #1193 / PR #1308 — conversation overview avatars

Storybook screenshots (Playwright, headless Chrome, 2x) taken on branch
`claude/1193/conversation-overview-avatars` at the state of PR #1308.

| File | Shows |
|------|-------|
| 01-stack-3-members-all-shown.png | ≤4 participants → every avatar, no chip |
| 02-stack-27-members-4-plus-23.png | 27 participants → 4 overlapping avatars + "+23" (report example) |
| 03-stack-narrow-2-plus-25.png | narrow header → 2 avatars + "+25" |
| 04-stack-chip-only-plus-27.png | no room for avatars → chip only "+27" |
| 05-useravatar-animals-no-monogram.png | `UserAvatar` renders animal icons, no letter monograms |
| 06-useravatar-56px.png | profile-size (56 px) avatar |
