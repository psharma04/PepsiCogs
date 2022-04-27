# Global Ban Cog

This cog allows users to easily ban and unban people from selected servers all at once. It is designed to reduce the time it takes to manually ban a user from more than one server, especially when dealing with 10-50 servers.

This cog also makes sure that a user meant to be banned, stays banned, until unbanned. On larger servers, making sure that everyone banned stays banned is quite difficult. This makes it easy for staff to unban someone without the admins noticing. However, with this cog, the bot would automatically re-sync all the global bans every day, week, or month and 12 PM.
## Installation

```python
1. [p]repo add pepsicogs https://github.com/psharma04/PepsiCogs

2. [p]cog install pepsicogs globalban

3. [p]load globalban
```

## Commands

```python
- [p]globalban <name> or <name+discrim> or <mention> or <ID> # Bans a user from all connected servers.

- [p]globalunban <ID> # Unbans a user from all connected servers.

- [p]globalbans # Gives all the people who are banned.

- [p]bansync # Syncs all global bans across all servers.

- [p]syncedservers # Shows all the synced servers.

- [p]sync # Adds a server to the synced list if it is not already there and re-syncs all the global bans.

- [p]delsync # Removes a server from the synced server list.
```

## Privacy
[Heimdall Intranet Privacy Policy](https://privacy.pks.ai/)
