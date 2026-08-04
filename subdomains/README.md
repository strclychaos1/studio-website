# Subdomain site backups

Snapshot copies of every Chaotic Game Studios site, for safekeeping.

| Folder | Live at | Source of truth |
| --- | --- | --- |
| (repo root) | chaoticgamestudios.com | THIS repo |
| strikecommand/ | strikecommand.chaoticgamestudios.com | Strike-Command repo `website/` |
| astroforge/ | astroforge.chaoticgamestudios.com | /var/www/astroforge-site/website |
| tagtalk/ | tagtalk.chaoticgamestudios.com | TagTalk repo `TagTalk-main/website/` |
| ttadmin/ | ttadmin.chaoticgamestudios.com | TagTalk repo `TagTalk-main/admin-web/dist` |
| shardfall/ | shardfall.chaoticgamestudios.com | newmmo1 `client/dist` (served by webserver.mjs) |

Notes: tagtalk-vc4.aab (73MB binary) deliberately excluded. sc-api has no site
(API only). Update snapshots whenever a site changes materially.
