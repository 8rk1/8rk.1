# Webhooks

## Example
Example usage of the webhook setup:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/8rk1/8rk.1/main/Main.lua", true))()

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
}
```

## Fields
To add fields, include them in the `["Fields"]` array.

```lua
{["Field"] = "Field Title Content", ["Description"] = "Field Description Content"},
```
Examples:
```lua
["Fields"] = {
    {["Field"] = "Field Title Content", ["Description"] = "Field Description Content"},
    {["Field"] = "Field Title Content", ["Description"] = "Field Description Content"},
}
```

## Credits
> Credits
* 8rk.1
