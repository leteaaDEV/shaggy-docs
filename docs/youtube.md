!> Is currently disabled until recoded

?> ⭐ **Limits**<br>Non Premium Shaggy servers are limited to subscribing to 15 YouTube channel notifications.<br>Premium Shaggy servers are unlimited to subscribing to how many Twitch channel notifications they want.

## Settings
<!-- tabs:start -->
<!-- tab:Slash Commands -->
Name              | Example           | Usage                                                                         
 ---------------- | ----------------- | -----------------------------------------------------------------------------
**youtube user add** \<name> [id]<br><span class="user-permissions">Administrator</span> | `/youtube user add UCX6OQ3DkcsbYNE6H8uQQuVA` | Binds the youtuber channel's alerts to the channel. Can use channel id only at the time (which is the most accurate way).
**youtube list**<br><span class="user-permissions">Administrator</span> | `/youtube list` | Shows all the binded youtubers and the connected channels.         
**youtube user remove** \<name><br><span class="user-permissions">Administrator</span> | `/youtube user remove UCX6OQ3DkcsbYNE6H8uQQuVA` | Unbinds a youtuber channel's alerts.
<!-- tabs:end -->

?> These variables can be used in the message that is sent when a youtube alert is received:
## Variables
- `{link}` - Channel link
- `{author}` - Channel name
- `{here}` - Tags @here
- `{everyone}` - Tags @everyone
