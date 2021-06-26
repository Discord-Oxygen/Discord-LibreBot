# Discord-LibreBot
An open-source Discord Bot (concept)

# Features
## easy setup
THe Bot works perfectly on defualt settings
It has an extremly simple to use GUI and you just need to invite the Bot and it sets up everythig automatically
But you can configure and twerk everything if you want to

## Moderation
<li>Infractions System</li>
<li>Automatic Actions based on Infractions (e.g. 3 Infractions / one day => Tempmute 1 week)</li>
<li>Mod-Log of moderator actions</li>
<li>Set Individual Permissions (Whitelist + Blacklist) for commands</li>
<li>Set User + Server Cooldowns and custom cooldowns per Role (e.g. mod 5s cooldown, admin 3s, etc.)</li>
<li>Set optional Roles that are removed while being muted</li>
<li>Re-apply mute-role if user leaves and joins again</li>
<br>

| Command                           | Action                                  |
| --------------------------------- | --------------------------------------- |
| `infractions [user]`              | Displays a user's infractions           |
| `warn <user> <reason>`            | Warns a user (add Infraction)           |
| `tempmute <user> <time> <reason>` | Temporarily server-mutes a user         |
| `mute <user> <reason>`            | Server-mutes a user                     |
| `unmute <user> [reason]`          | Unmutes a user                          |
| `kick <user> <reason>`            | Kicks a user from the server            |
| `tempban <user> <time> <reason>`  | Temporarily bans a user from the server |
| `ban <user> <reason>`             | Bans a user from the server             |
| `unban <user> <reasone>`          | Unbans a user from the server           |
| `clear <amount> [user]`           | Delete a channel's messages             |

### Automated Actions - Triggers:<br>
(can be cloned & modified & combined)<br>
<li>x warns in y time</li>
<li>Mass Mention (x mentions (roles count as 1) in y time/ per message)</li>
<li>Spam x messages in y time</li>
<li>Advanced Spam detection based on:<ul>
  <li>frequency</li>
  <li>exact repetitions</li>
  <li>similar / slightly altered repetitions</li>
  <li>if the message containts text or not (you can set custom dictionaries)</li>
  <li>amount of characters</li>
  <li>mass emojis or caps</li>
  <li>unicode spam</li>
  <li>attachment / embed spam</li>
  <li>excessive swearing (bad word list))</li>
</ul></li>
<li>set custom Spam probabilty thresholds (e.g. 60% probabilty tempmute, 80% mute, 95% ban, etc.)</li>
<li>Wrong language (e.g. not english) used</li>
<li>More than x percent caps used</li>
<li>Invite Link</li>
<li>Bad Links (e.g. IP loggers, links that are flagged by safebrowsing, custom white and black lists, etc.)</li>
<li>Bad words</li>
<li>NSFW attachments in non-NSFW channel</li>
<li>x ghost pings (messages containing pings) in y time or y messages</li>

### Automated Actions - Actions:<br>
(can be combined)<br>
<li>Undo message deletion to avoid ghost pings</li>
<li>Reply to message in Channel</li>
<li>Send message in Channel</li>
<li>DM Author of message</li>
<li>Delete Message</li>
<li>Remove Role for Author</li>
<li>Warn</li>
<li>tempmute</li>
<li>mute</li>
<li>kick</li>
<li>tempban</li>
<li>ban</li>
<li>post message to channel</li>
<li>DM The Owner</li>

## Advanced Raid and alt protetcion
