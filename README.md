# OpenCart Extended Session

## Overview - Problems

OpenCart session cookie is limited to expire at the end of the browser session and has a maximum length of 26 random characters.

## Improvments

- Extend max length to 40 characters
- Add configuration value too handle the expiration time
- Replace the files that start/update the cookie
