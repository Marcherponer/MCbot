# MC_bot

Minecraft server discord bot. Iterated over several years based on needs. Requires a "path_list.xml" file in the following structure:

```xml
<?xml version="1.0"?>
<paths>
    <ip_test_url>https://api.ipify.org</ip_test_url>
    <discord_token>Token</discord_token>
</paths>
```

ip_test_url and discord_token are required for functionality.

Also requires a bash command "start", which moves to the Minecraft server directory and runs to approprioate java commands to start up the server.
