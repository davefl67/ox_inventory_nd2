# Modified Ox Inventory Files for ND Framework v2.0
To get things working smoothly, three files contained in the bridge and MySQL modules had to be modified so that `ox_inventory` could speak to the correct table structure in `ND_Core`.

These files are included in this repository. 

## Directions

✅ Make a backup of your 📂**ox_inventory** → 📂**modules** folder

✅ Unzip these files into your 📂**ox_inventory** folder. This will overwrite three files:

    📂ox_inventory
      📂modules
        📂bridge
          📂nd
            📄client.lua
            📄server.lua
          📂mysql
            📄server.lua

✅ Restart your server.

## Need help?
Check out the **Andy's Development Discord Server**

![Andyyy's Development Discord](https://discordapp.com/api/guilds/857672921912836116/widget.png?style=banner2)

Check out the [**official documentation for ND Framework**](https://ndcore.dev/)
![ND-FRAMEWORK](https://user-images.githubusercontent.com/86536434/193913064-01b8a9b4-97a2-4bd2-9f33-99f89558ac01.png)
