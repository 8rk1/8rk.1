# Information
A Webhook

## Example
Example usage of the webhook setup:

```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/8rk1/8rk.1/main/Main.lua", true))()

getgenv().Config = {
    ["WebhookUrl"] = "",              -- URL for the webhook
    ["Content"] = "Msg Content",      -- Content of the message
    ["Title"] = "Title Content",      -- Title of the message
    ["Description"] = "Description Content", -- Description of the message
    ["ThumbnailUrl"] = "",            -- URL for the thumbnail image
    ["Color"] = 0x000000,             -- Color of the embed
    ["Footer"] = "Footer Content",    -- Footer text
    ["FooterThumbnailUrl"] = "",      -- URL for the footer thumbnail image
    ["Timestamp"] = true,            -- Whether to include a timestamp
    ["Thumbnail"] = false,           -- Whether to include a thumbnail
    ["Footers"] = true,              -- Whether to include footers
    ["FootersThumbnail"] = false,    -- Whether to include footer thumbnails
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
```
