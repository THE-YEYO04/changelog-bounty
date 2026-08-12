\# Changelog Generator



A simple Python command-line tool that generates a `CHANGELOG.md` from a Git repository history.



\## Features



\- Detects the latest Git tag automatically.

\- Reads commits after the latest tag.

\- Works with repositories that have no tags.

\- Classifies commits into:

&#x20; - Added

&#x20; - Fixed

&#x20; - Changed

&#x20; - Removed

&#x20; - Other

\- Generates a Markdown changelog automatically.

\- Provides command-line options.

\- Includes error handling and useful status messages.



\## Requirements



\- Python 3.10 or newer

\- Git



Check your installations with:



```bash

python --version

git --version

