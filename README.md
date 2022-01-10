
# Jira CLI

A quick CLI to query Jira from vim/emacs. Print text formatting
approximating a man page.

## Configuration

Add an Atlassian token in the format `<username>:<token>` into
`~/.atlassian_token` and set the environment variable `JIRA_DOMAIN` to
the subdomain for query API.

## TODO
- [ ] Move all configuration to a `~/.jira.edn` file. Not half and
      half environment variables and half config file
- [ ] Spit out groff markup and just pass it to `groff -man` instead
      of using my hack formatting code

## License
Copyright (c) 2021 Will Harding <harding.will@gmail.com>

Permission to use, copy, modify, and distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

