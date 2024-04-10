# Eaglerforgeconst relayId = Math.floor(Math.random() * 3);
window.eaglercraftXOpts = {
    demoMode: false,
    container: "game_frame",
    assetsURI: "assets.epk",
    localesURI: "lang/",
    worldsDB: "worlds",
    servers: [
        { addr: "ws://localhost:8081/", name: "Local test server" }
    ],
    relays: [
        { addr: "wss://relay.deev.is/", comment: "lax1dude relay #1", primary: relayId == 0 },
        { addr: "wss://relay.lax1dude.net/", comment: "lax1dude relay #2", primary: relayId == 1 },
        { addr: "wss://relay.shhnowisnottheti.me/", comment: "ayunami relay #1", primary: relayId == 2 }
    ]
};
