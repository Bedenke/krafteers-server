# Krafteers

### Run your own Krafteers **server**.

Requirements:
- [Java Runtime](https://www.java.com/en/download/manual.jsp)
- [Port Forwarding Guide](https://www.noip.com/support/knowledgebase/general-port-forwarding-guide) Make sure your [Port] is not blocked by your router
- [Krafteers game](https://krafteers.com)
- [Krafteers server](https://github.com/Bedenke/krafteers-server/archive/refs/tags/v16.1.zip)

## Running

To run the server: `java -jar krafteers.jar`

When running you should see your server listed on the **Join Game** section in the game's main menu, with a 🌎 icon.

## Configurations

Edit the `config.txt` file to configure the server as you want

```
start [Map Name] [Port]
pvp [true|false]
title [Name of your server]
difficulty [0..1] // 0 is easy, 1 is normal, 2 is double hard
frame-rate 16
max-players 64
log-level [off|info|verbose]
net stats [true|false]
```

Look at `/assets/data/maps` directory for the current `[Map Name]` options

Example 1: Team PvP (Survival map)

```
start Survival 9101
frame-rate 16
pvp true
max-players 64
title Capture the Flag [Team + PvP]
difficulty 1
log-level verbose
net stats true
```

Example 2: Co-op story map (MainIsland map)

```
start MainIsland 9001
frame-rate 16
pvp false
max-players 8
title Story Game
difficulty 1
log-level off
net stats false
```


## Credits and community

Join our [Discord community](https://discord.gg/QaRjHFmhnG) to find players and get help.

Krafteers was created and developed by Lucas Goraieb (lucas@bedenke.com) 

[bedenke.com](bedenke.com)
