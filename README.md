# youtube2anki
Generate Anki decks from german youtube video subtitles.

  1. Fetch anki decks from Anki server using Python Anki client.
  2. Fetch captions from desired YouTube video if exists.
  3. Parse captions into tokens using textblob-de. https://pypi.org/project/textblob-de/
  4. Check if deck already contains word.
  5. If not generate flashcard using the official Wiktionary API: https://stackoverflow.com/questions/2770547/how-to-retrieve-wiktionary-word-content.
  6. Submit changes to the server.

  BONUS STEP Oh yeah, make Anki Python client or use meh AnkiWeb extension.
