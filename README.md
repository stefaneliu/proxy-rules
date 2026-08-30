# proxy-rules

Published rule sets for Surge, Stash, Mihomo/OpenClash/FlClash and compatible clients.

The canonical sources and maintenance history live in a private repository. This repository contains only generated/client-consumable rule assets.

## Routing

Files under `routing/` contain routing rules without policy names. The consuming configuration assigns each rule set to the appropriate policy group.

## DNS

`dns/cn-sensitive-domains.txt` contains a deliberately small set of domains that should use a mainland China DNS resolver (AliDNS) instead of the user's default encrypted overseas resolver.

## Security

No proxy credentials, user-specific DoH URLs, API tokens, subscription URLs, or other secrets belong in this repository.
