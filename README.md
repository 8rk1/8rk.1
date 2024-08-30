# Credits
This was made by 8rk.1
## Example
Example:
```lua
--// Webhook \\--
loadstring(game:HttpGet("https://raw.githubusercontent.com/8rk1/8rk.1/main/Main.lua", true))()

--// Configuration \\--
getgenv().Config = {
    ["WebhookUrl"] = "",
    ["Content"] = "Msg Content",
    ["Title"] = "Title Content",
    ["Description"] = "Description Content",
    ["ThumbnailUrl"] = "",
    ["Color"] = 0x000000,
    ["Footer"] = "Footer Content",
    ["FooterThumbnailUrl"] = "",
    ["Timestamp"] = true,
    ["Thumbnail"] = false,
    ["Footers"] = true,
    ["FootersThumbnail"] = false,
    ["Fields"] = {
        {["Field"] = "Field Title Content", ["Description"] = "Field Description Content"},
    }
}```
## Fields
To add fields add this to ["Field"] = {}
```lua
{["Field"] = "Field Title Content", ["Description"] = "Field Description Content"},```
