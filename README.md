# PadPal-Mobile
PadPal Mobile App

This repo is a part of a larger PadPal project. The following is a list of the relevant repos:
- [PadPal-Server](https://github.com/ssebs/PadPal-Server/)
  - This is the golang REST API server. Files will be saved here.
  - The main README will be here for now.
- [PadPal-CLI](https://github.com/ssebs/PadPal-CLI/)
  - This is the CLI for syncing a workspace / your notes to your computer.
- [PadPal-Mobile](https://github.com/ssebs/PadPal-Mobile)
  - This is the mobile app to interact with a hosted PadPal-Server.

## Docs
- Editor:
  - https://pub.dev/packages/super_editor
  - https://github.com/singerdmx/flutter-quill/
    - https://www.youtube.com/playlist?list=PLbhaS_83B97vONkOAWGJrSXWX58et9zZ2
  - slide gesture detection for bullet points
    - https://api.flutter.dev/flutter/widgets/GestureDetector/onHorizontalDragUpdate.html
 
## Feature list for PadPal-Mobile
### MVP
- WYSIWYG Markdown editor
  - Text only mode?
  - Formatting buttons for:
    - Bullet points
    - #'d bullets
    - Bold, italic, strikethru
    - H1-H6
    - Image inserts?
  - @ macros like gdocs
    - @today for <insert date>
    - more?
- Sync to/from server
  - auto?
- Note orginization
  - List files on left, folder support
  - Search by tags
- Auth
  - user/pass auth option
  - sso?
- Gesture for bullet points
  - Tab / Indent support for bullet points
  - Same for checklists
- Nice checkbox support
  - Click to "check"
  - Smol 'x' to archive to "completed" section
- Home screen widget
  - List notes
    - ScrollView?
  - Excerpts from notes
  - Tap to open that note
  - '+' create new note button

### Wish
- SSO 
- Handle merge conflict
- Desktop => copy paste as rich text for use with word, etc.
 
## LICENSE
[Apache License 2.0](./LICENSE)
