Fitness Programme Manager v52 — State is not defined repair

The main app accidentally closed its JavaScript module before loading features added after v44. Client Companion, food diary, saved programme links and other features could report "state is not defined". v52 places the code back into the original shared scope.

All v51 features and the approved app icon are retained. The existing storage key and programme data structure are unchanged. Back up your data before replacing files on GitHub Pages. Do not clear app/browser storage or uninstall the app.

Testing: choose a client, open Edit & Print, then Client Companion > Preview > Share. If Android has a cached old version, close and reopen after the GitHub Pages deployment.
