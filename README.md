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

## Arch for mobile
- React Native
- Padpal sync client, must work outside of app
  - http polling? or websockets? or...
- Widget to display single note, clicking will launch app of choice (markor)
- Markor is the MD editor, so no editing needed

 
## LICENSE
[Apache License 2.0](./LICENSE)
