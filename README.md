# SafeBrowz Community Database

Community-maintained blacklist and whitelist for [SafeBrowz](https://github.com/meraja34/SafeBrowz) Chrome extension.

## Files

- `blacklist.json` - Reported scam/phishing domains
- `whitelist.json` - Verified safe domains (community approved)

## How it works

1. Users report scam sites via SafeBrowz extension
2. Domains added to `reported_by_community`
3. After verification, moved to `domains` (confirmed scam)
4. Extension fetches this list every 6 hours for instant blocking

## Contributing

Open an issue or PR to report a scam domain or request whitelist addition.
