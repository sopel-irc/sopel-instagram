# sopel-instagram

A Sopel plugin to fetch information about Instagram links.

## Current status

We are looking for prospective plugin maintainers! Most of Sopel's built-in
plugins will be moved out of core within the next few releases. When the
`instagram` plugin's turn comes, it will need someone to take charge of
keeping it working.

If that sounds like you, get in touch in `#sopel` on freenode, or open an issue.

### Known issues

As of January 2021, it's likely that this plugin will **NOT** work to fetch
link information unless Sopel is running from a totally innocuous IP (i.e.
someone's house). Insta has cracked down on IP ranges owned by server/hosting
providers, and disabled the API endpoint this plugin used to fetch data
without scraping the HTML page itself.
