# youtube2anki
Generate Anki decks from german youtube video subtitles.

  1. Fetch anki decks from Anki server using Python Anki client.
  2. Fetch captions from desired YouTube video if exists. https://pypi.org/project/youtube-transcript-api/
  3. Parse captions into tokens using textblob-de. https://pypi.org/project/textblob-de/
  4. Check if deck already contains word.
  5. If not generate flashcard using the official Wiktionary API: https://stackoverflow.com/questions/2770547/how-to-retrieve-wiktionary-word-content.
  6. Submit changes to the server.

https://apps.ankiweb.net/docs/addons20.html#qt
https://github.com/ankicommunity/anki-sync-server
https://genedan.com/no-127-ankisyncd-a-custom-sync-server-for-anki-2-1/

Example extension:  https://github.com/wilddom/memrise2anki-extension
