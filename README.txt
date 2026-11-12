FITNESS PROGRAMME MANAGER v53 — CLIENT PROGRAMME LIBRARY

FIXES
- Removes accidentally injected app code from the service worker, where `state` is undefined. This was one source of the reported error.
- Retains the standalone Client Companion export, direct share, and preview.
- Adds multiple named programmes per client, with Open/Make active, Rename and Duplicate. Existing current client programme is migrated into the named library when first opened.
- Sample client includes a named three-day sample programme.
- Client Companion exports the active saved programme for the selected client.
- Saves named programme edits through the existing autosave/IndexedDB mechanism.

IMPORTANT
Back up existing data BEFORE uploading this version. Do not clear browser storage, uninstall the PWA or create a new repository URL. Update all files in the SAME GitHub Pages repository. If an existing programme was never successfully saved, this version cannot recover it. Browser testing on Android and Messenger is still needed.

A client can have multiple saved named programmes. Only the currently active programme is included in a Client Companion export. To send another one, select Open / make active first.
