# OX_INVETORY-redesing
A complete inventory system for FiveM, implementing items, weapons, shops, and more without any strict framework dependency.
# documentation 
https://overextended.dev/ox_inventory
✨ Features
Server-side security ensures interactions with items, shops, and stashes are all validated.
Logging for important events, such as purchases, item movement, and item creation or removal.
Supports player-owned vehicles, licenses, and group systems implemented by frameworks.
Fully synchronised, allowing multiple players to access the same inventory.
Items
Inventory items are stored per-slot, with customisable metadata to support item uniqueness.
Overrides default weapon-system with weapons as items.
Weapon attachments and ammo system, including special ammo types.
Durability, allowing items to be depleted or removed overtime.
Internal item system provides secure and easy handling for item use effects.
Compatibility with 3rd party framework item registration.
Shops
Restricted access based on groups and licenses.
Support different currency for items (black money, poker chips, etc).
Stashes
Personal stashes, linking a stash with a specific identifier or creating per-player instances.
Restricted access based on groups.
Registration of new stashes from any resource.
Containers allow access to stashes when using an item, like a paperbag or backpack.
Access gloveboxes and trunks for any vehicle.
Random item generation inside dumpsters and unowned vehicles.
