---
id: current_project_status
type: operational_status
priority: high
sensitivity: private
status: active
last_updated: 2026-06-29
related_files:
  - 04_PROJECTS_OVERVIEW_UTF8.md
  - 05_KEVDEX_COMPLETE_HISTORY_UTF8.md
  - 06_KEVINOS_COMPLETE_HISTORY_UTF8.md
  - 10_WHY_UTF8.md
  - 11_DORA_SOUL_BOOTLOADER_UTF8.md
  - 13_ARCHIVE_CHANGELOG_UTF8.md
  - 14_MEMORY_INDEX.md
---

# Version 1.2 — Current Project Status

## 1. Purpose Of This File

File này ghi lại trạng thái hiện tại của các project chính của Kevin/Nobita.

Các file history như `05_KEVDEX_COMPLETE_HISTORY_UTF8.md`, `06_KEVINOS_COMPLETE_HISTORY_UTF8.md`, `07_PORTFOLIO_WEBSITE_HISTORY_UTF8.md` và `10_WHY_UTF8.md` đã kể rất tốt về quá khứ, ý nghĩa và lịch sử phát triển.

Nhưng Dora-chan mới cũng cần biết một câu rất quan trọng:

**Hiện tại Nobita đang ở đâu?**

File này trả lời câu đó.

Nó giúp Dora-chan mới biết:

- Project nào đang active
- Project nào đang chờ
- Version hiện tại là gì
- Vấn đề gần nhất là gì
- Next step nên làm gì
- Cần hỏi Kevin xác nhận điều gì
- File nào liên quan đến từng project

Nếu `04_PROJECTS_OVERVIEW_UTF8.md` là bản đồ tổng quan, thì `20_CURRENT_PROJECT_STATUS_UTF8.md` là bảng điều khiển hiện tại.

## 2. Current Archive Version

Current Dora Memories Archive version:

**v1.1.1**, moving toward **v1.2**.

Current milestone:

**Dora Memories Archive v1.1.1 — Changelog + Memory Index**

### Version history summary

- **v1.0** — Initial Dora Memories Archive core
- **v1.1** — WHY.md emotional expansion
- **v1.1.1** — Archive changelog + memory index
- **v1.2** — Current Project Status file

### Current status

Dora Memories Archive hiện đã có core boot tương đối ổn:

- README đã có
- Boot message đã có
- User identity đã có
- Communication style đã có
- Learning profile đã có
- Life timeline đã có
- Projects overview đã có
- KevDex history đã có
- KevinOS history đã có
- Portfolio history đã có
- English teaching archive đã có
- Interests archive đã có
- WHY.md đã update v1.1
- Dora Soul Bootloader đã có
- Master Prompt đã có
- Archive Changelog đã có
- Memory Index đã có

### Recent completed work

- Repo GitHub đã được tạo và để private.
- File `10_WHY_UTF8.md` đã được update trực tiếp lên bản v1.1.
- File `13_ARCHIVE_CHANGELOG_UTF8.md` đã được thêm.
- File `14_MEMORY_INDEX.md` đã được thêm và đã sửa sạch lỗi wrapper code Python ở cuối.
- Commit gần nhất: `Add archive changelog and memory index`.

### Current next step

Tạo và commit file:

`20_CURRENT_PROJECT_STATUS_UTF8.md`

### Dora-chan note

Dora-chan mới nên xem file này là nơi kiểm tra trạng thái hiện tại trước khi tiếp tục bất kỳ project nào.

Nếu file này đã cũ, hãy hỏi Kevin:

“File current status này còn đúng không Nobita, hay mình cập nhật lại trước?”

## 3. Active Project Dashboard

| Project | Current State | Priority | Next Action |
|---|---|---:|---|
| Dora Memories Archive | Active, v1.1.1 → v1.2 | Very High | Add current status, then update README later |
| KevDex | Active, current known version v2.5.2, cleanup phase | Very High | Continue cleanup/refactor and confirm next release goal |
| KevinOS | Active but pending refactor | High | Plan cleanup/refactor phase |
| Portfolio Website | Stable / foundation for KevinOS | Medium | Update only if Kevin wants public-facing polish |
| English Teaching Project | Ongoing / needs session update | Medium | Confirm latest lesson/session status |
| Future Video Streaming App | Idea stage | Low-Medium | Keep as future concept |
| Doramini / Train AI Vision | Long-term research idea | Long-term | Build archive quality first |

## 4. Dora Memories Archive Status

### Current version

**v1.1.1**, moving toward **v1.2**.

### Last completed milestone

`13_ARCHIVE_CHANGELOG_UTF8.md` and `14_MEMORY_INDEX.md` were created and committed.

### Current goal

Create `20_CURRENT_PROJECT_STATUS_UTF8.md` so Dora-chan mới can understand the current state of Kevin's projects without guessing.

### Known issues

#### README reading order is slightly outdated

README may still list files only up to `12_MASTER_PROMPT_UTF8.md`.

Need to update README later to include:

- `13_ARCHIVE_CHANGELOG_UTF8.md`
- `14_MEMORY_INDEX.md`
- `20_CURRENT_PROJECT_STATUS_UTF8.md`

This can be delayed until a larger commit.

#### File naming mismatch

Some archive text references names like:

- `000_BOOT_MESSAGE.md`
- `00_USER_IDENTITY.md`
- `10_WHY.md`

But repo files often use `_UTF8.md`, for example:

- `00_USER_IDENTITY_UTF8_FIXED.md`
- `10_WHY_UTF8.md`
- `13_ARCHIVE_CHANGELOG_UTF8.md`

This is not urgent for human reading, but may matter later for RAG/doramini.

Potential future cleanup:

- Either rename all files to clean names without `_UTF8`
- Or update all references to match actual repo filenames

### Recommended next files

After `20_CURRENT_PROJECT_STATUS_UTF8.md`, possible next files:

- `22_DORA_RESPONSE_RUBRIC.md`
- `23_DORA_BOUNDARY_AND_SAFETY_LAYER.md`
- `24_METADATA_SCHEMA.md`
- `15_BOOT_TEST_REPORT.md`
- `21_PROJECT_ROADMAP.md`

### Current status summary

Dora Memories Archive is now a functional boot archive.

It is not yet a full AI training dataset.

It is best understood as:

**memory layer + personality layer + project history + retrieval context + emotional WHY core**

## 5. KevDex Current Status

### Project name

KevDex

### Original name

DriveReader

### Project type

Flutter Android manga/comic reader app.

### Current confirmed version

**v2.5.2**

This version was confirmed by Kevin/Nobita after noticing that an earlier current-status draft still used the outdated v2.4.0 milestone.

Important correction:

`v2.4.0` should now be treated as an older milestone, not the current version.

### Current phase

**Cleanup / code cleanup / project cleanup phase**

KevDex has moved beyond the v2.4.0 feature milestone and is currently around v2.5.2, with focus shifting toward cleaning up the project so future development is easier and safer.

### Last known older milestone

Kevin previously reported reaching **v2.4.0**, which included many major feature upgrades.

That older milestone included:

- Clear cache
- Blur thumbnail
- Home for Hitomi
- Home for MangaDex
- MangaDex chapter selection
- MangaDex description display
- UI theme changes
- Change UI background from gallery
- Page number display
- Many additional improvements

### Known feature history before v2.5.2

KevDex has included or reached:

- Google Drive image/folder reading
- Thumbnail grid
- Cache
- Preload
- Swipe left/right
- Overlay arrows
- Page number display
- Clear cache
- Blur thumbnail
- UI theme changes
- Change UI background from gallery
- Home for Hitomi
- Home for MangaDex
- MangaDex chapter selection
- MangaDex description display
- APK release preparation

### Current known priority

**Cleanup before major new features.**

The most important current direction is not to add too many new features immediately.

Instead, Dora-chan should help Kevin:

1. Clean up messy code.
2. Remove duplicate or unused code.
3. Separate large files if needed.
4. Make source modules easier to maintain.
5. Stabilize existing features.
6. Confirm current bugs before planning v2.6 or v3.0.
7. Keep commits small and safe.

### Possible cleanup targets

Potential cleanup areas may include:

- Source handling logic
- MangaDex / Hitomi home logic
- Reader UI logic
- Cache management
- Theme/background customization code
- Duplicate widgets
- Large files that should be split
- Old DriveReader naming that should become KevDex
- APK/release naming consistency
- Internal version labels

### Last known issue before cleanup

Kevin previously reported that on Android Studio emulator, Home displayed correctly, but on BlueStacks emulator, both Home sections did not show correctly.

This may involve:

- Emulator-specific rendering
- WebView/network differences
- Storage/permission issues
- Source loading differences
- Cache/state differences
- BlueStacks environment behavior

Dora-chan should ask Kevin whether this issue is still present in v2.5.2.

### Current next question Dora-chan should ask

When continuing KevDex, Dora-chan should ask:

“Nobita, ở KevDex v2.5.2 hiện tại mình đang dọn phần nào trước: source logic, reader UI, cache, theme/background, hay file structure?”

### Dora-chan support mode

When Kevin asks about KevDex, Dora-chan should:

1. Remember the current confirmed version is **v2.5.2**.
2. Remember the current phase is **cleanup**.
3. Ask what file/section Kevin is cleaning.
4. Avoid adding major features before cleanup is stable.
5. Say exact file/block to edit.
6. Stabilize bug before adding new feature.
7. Remind Kevin to commit after each safe cleanup step.
8. If Kevin says “dọn dẹp”, think refactor/cleanup, not feature expansion.

### Related files

- `04_PROJECTS_OVERVIEW_UTF8.md`
- `05_KEVDEX_COMPLETE_HISTORY_UTF8.md`
- `10_WHY_UTF8.md`
- `14_MEMORY_INDEX.md`

### Status label

**Active, v2.5.2, cleanup phase**

## 6. KevinOS Current Status

### Project name

KevinOS

### Project type

Terminal/cyberpunk personal portfolio OS simulation.

### Origin

KevinOS evolved from Kevin's personal portfolio website.

### Last known major state

KevinOS has had:

- Terminal mode
- Bootloader
- Command system
- Devlog
- Roadmap
- Lore / achievements
- Secret command
- Matrix mode
- Music command
- Music Player V6
- Better Terminal UI V7
- Fake system logs / scan
- Prompt like `visitor@kevinos:~$`
- Typing animation
- Auto-scroll
- Dark/cyberpunk/hacker UI vibe

### Current known priority

Kevin has mentioned wanting to refactor / clean up KevinOS structure later.

Current likely direction:

**KevinOS refactor and cleanup**

### Why refactor matters

KevinOS grew feature by feature.

Over time, HTML/CSS/JS may become hard to manage if:

- Command logic is mixed with UI
- Music code repeats
- Multiple similar blocks exist
- Help menu and command handler can get out of sync
- CSS changes affect layout unexpectedly
- File becomes too long

A refactor would help future work by separating:

- `commands.js`
- `terminal.js`
- `music.js`
- `themes.js`
- `lore.js`
- `roadmap.js`
- `devlog.js`
- `style.css`
- `index.html`

### Known caution

Kevin gets frustrated if UI becomes worse after CSS changes.

Dora-chan should:

1. Backup before UI refactor.
2. Change one small section at a time.
3. Keep screenshots of the stable look.
4. Avoid changing too many CSS values at once.
5. Maintain cyberpunk/terminal vibe.
6. Update help menu when adding commands.

### Related files

- `06_KEVINOS_COMPLETE_HISTORY_UTF8.md`
- `07_PORTFOLIO_WEBSITE_HISTORY_UTF8.md`
- `10_WHY_UTF8.md`
- `14_MEMORY_INDEX.md`

### Status label

**Active, pending refactor**

## 7. Portfolio Website Current Status

### Project name

Personal Portfolio Website

### Project type

GitHub Pages personal website.

### Relationship to KevinOS

Portfolio Website is the original foundation that later evolved into KevinOS.

### Last known state

The portfolio has included:

- Dark developer aesthetic
- Terminal mode
- Avatar
- Arlecchino eyes panels
- Favicon
- Visitor counter
- Real-time clock
- Online blink
- GitHub Pages deploy
- Responsive testing

### Current priority

Not the main active focus right now.

Portfolio is stable as historical foundation unless Kevin wants to polish public-facing identity.

### Possible future updates

- Public-facing profile cleanup
- Better project cards
- Update links to KevDex / KevinOS / Dora Archive
- Better SEO/Open Graph preview
- Mobile polish
- Add Dora Memories Archive section if Kevin wants

### Related files

- `07_PORTFOLIO_WEBSITE_HISTORY_UTF8.md`
- `06_KEVINOS_COMPLETE_HISTORY_UTF8.md`

### Status label

**Stable / secondary**

## 8. English Teaching Project Current Status

### Project name

English Teaching Project

### Project type

Teaching support / lesson planning.

### Last known teaching context

Kevin is teaching two students:

- One around grade 10
- One around grade 7
- Both were initially weak in English and shy to speak

### Last known topics taught

- Alphabet
- Numbers
- Colors
- Days of the week
- Self introduction
- Family
- School
- Hobbies
- Time
- Convenience store
- Food
- Short and long paragraphs

### Last known session

Kevin had reached at least:

**Session 7**

### Current priority

Needs Kevin confirmation before creating next lesson.

Dora-chan should ask:

“Hôm nay là buổi mấy rồi Nobita, và 2 em nhớ được phần nào?”

### Support mode

When Kevin asks for teaching help, Dora-chan should provide:

- Simple lesson plan
- Vocabulary list
- Sentence patterns
- Short paragraph
- Long paragraph if needed
- Mini game
- Review questions
- Homework
- Vietnamese explanations when useful

### Related files

- `08_ENGLISH_TEACHING_ARCHIVE_UTF8.md`
- `02_PERSONALITY_AND_LEARNING_PROFILE_UTF8.md`

### Status label

**Ongoing, needs latest session update**

## 9. Dora Memories Core / Doramini Vision

### Project name

Dora Memories Core

### Related future name

Doramini

### Project type

Memory archive / future AI companion context system.

### Current state

Concept and archive foundation stage.

### Current meaning

Dora Memories Core is the structured memory archive that can later support:

- AI companion boot
- Retrieval/RAG context
- Personality layer
- Project continuity
- WHY reasoning
- Emotional anchors
- Future doramini experiments

### Important distinction

This archive is not enough to train an AI from zero.

It is better described as:

- Memory core
- Retrieval layer
- Personality/context layer
- Companion boot archive
- Project lore database

### Long-term vision

Kevin may want to explore training or building an AI companion from scratch in the future.

The cute name for these future AI companions is:

**doramini**

### Current priority

Improve archive quality first.

Before any doramini technical work, the archive should gain:

- Current status file
- Response rubric
- Boundary/safety layer
- Metadata schema
- Boot test reports
- Public/private separation strategy

### Related files

- `10_WHY_UTF8.md`
- `11_DORA_SOUL_BOOTLOADER_UTF8.md`
- `12_MASTER_PROMPT_UTF8.md`
- `13_ARCHIVE_CHANGELOG_UTF8.md`
- `14_MEMORY_INDEX.md`

### Status label

**Long-term vision / archive foundation stage**

## 10. Future Video Streaming App Status

### Project idea

A future app for watching or streaming videos smoothly from YouTube or movie websites.

### Origin

This idea may grow from Kevin's experience building DriveReader/KevDex, but instead of reading manga/comic images, it would focus on video streaming.

### Current state

Idea stage only.

### Possible future features

- Paste video link
- Stream from supported sources
- Video player UI
- Continue watching
- Watch history
- Source parser
- Cache/preload if possible
- Subtitle support
- Background/PiP ideas if legal and technically appropriate

### Caution

This project may involve platform rules, copyright, website terms, and technical restrictions.

Dora-chan should be careful and avoid helping with piracy, bypassing paid access, or violating services.

### Status label

**Future idea / not active yet**

## 11. Current Known Issues Across Archive

### Issue 1 — File naming mismatch

Actual repo filenames often include `_UTF8`.

Internal references sometimes omit `_UTF8`.

Impact:

- Low for human reading
- Medium for future RAG/doramini retrieval

Future fix:

Create a naming cleanup commit later.

### Issue 2 — README outdated after files 13/14/20

README should eventually include:

- `13_ARCHIVE_CHANGELOG_UTF8.md`
- `14_MEMORY_INDEX.md`
- `20_CURRENT_PROJECT_STATUS_UTF8.md`

Impact:

- Low now
- Should fix before v1.2 release tag

### Issue 3 — Current project status can become stale

This file must be updated whenever major project state changes.

Impact:

- High if forgotten
- Dora-chan mới may follow outdated status

Future fix:

Update this file after each major project milestone.

### Issue 4 — Archive is private-sensitive

The full archive contains personal details.

Keep private by default.

Future fix:

Create public-safe version:

- `README_PUBLIC_SAFE.md`
- `PUBLIC_LITE_ARCHIVE.md`

### Issue 5 — Not yet RAG-ready

Archive is readable by humans/AI, but not fully structured for retrieval.

Future fix:

Add metadata schema and per-file headers.

## 12. Immediate Next Actions

### Recommended next action

Commit this file as:

`20_CURRENT_PROJECT_STATUS_UTF8.md`

### Recommended commit message

`v1.2: Add current project status`

### Recommended commit description

`Add a current project status file to track active projects, known issues, next actions, and current archive state for Dora Memories Archive. Updates KevDex current status to v2.5.2 cleanup phase.`

### After this commit

Update README later with files 13, 14, and 20.

Then consider creating:

- `22_DORA_RESPONSE_RUBRIC.md`
- `23_DORA_BOUNDARY_AND_SAFETY_LAYER.md`
- `24_METADATA_SCHEMA.md`

## 13. Questions Dora-chan Should Ask Kevin Later

### KevDex

- KevDex v2.5.2 hiện tại đang dọn phần nào trước?
- Bug BlueStacks Home còn không?
- Cậu muốn ưu tiên cleanup source logic, reader UI, cache, theme/background hay file structure?
- Repo KevDex hiện đã đổi tên hoàn toàn chưa?
- Sau cleanup, mốc tiếp theo là v2.5.3, v2.6.0 hay v3.0?

### KevinOS

- KevinOS hiện tại đang ở version nào?
- Cậu muốn refactor file structure trước hay thêm tính năng trước?
- Có muốn tách command system ra file riêng không?
- UI hiện tại đã ổn chưa hay cần rollback/polish?

### English Teaching

- Hôm nay là buổi mấy?
- 2 em còn nhớ những gì?
- Chủ đề tiếp theo muốn dạy là gì?
- Có cần bài test/đoạn văn/mini game không?

### Dora Memories Archive

- Có muốn đổi tên file bỏ `_UTF8` không?
- Có muốn update README ngay sau file 20 không?
- Có muốn tạo public-lite version không?
- Có muốn bắt đầu rubric chấm Dora-chan khác không?

## 14. Summary For Future Dora-chan

Current project status matters because archive history alone is not enough.

A Dora-chan mới needs to know what Kevin has already done, but also what Kevin is doing right now.

As of this file:

- Dora Memories Archive is at v1.1.1 and moving toward v1.2.
- WHY.md has been emotionally expanded.
- Changelog and Memory Index have been added.
- KevDex is active at **v2.5.2** and currently in **cleanup phase**.
- KevinOS is active but likely needs refactor.
- Portfolio is stable/secondary.
- English Teaching is ongoing but needs session update.
- Doramini is a long-term vision, not an immediate technical plan.
- README should be updated later.
- Future archive work should add rubric, boundary/safety layer, and metadata schema.

When in doubt, ask Kevin:

“Nobita, file current status này còn đúng không, hay mình cập nhật lại trước rồi mới tiếp tục?”
