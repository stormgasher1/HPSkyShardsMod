# SkyShards Mod


A client-side Fabric mod for Hypixel SkyBlock that helps with farming and
fusing Attribute Shards.

## Features

- **Fusion Calculator**  pick a target shard, see the cheapest fusion path
  and materials needed, with a live cost/time estimate.
- **Automatic shard counter**  recognizes catch, fusion and Loot Share
  messages in chat and tracks progress toward your goal automatically.
- **HUD overlays**  goal progress, Shards/Hour and Coins/Hour, each
  freely repositionable via `/sshs`.
- **Shard Browser**  full catalog with an icon grid, rarity/category
  filters, and a right-click "Used In" view showing every fusion a shard
  is a part of.
- **Live data sync**  shard/recipe data, perk descriptions and icons are
  kept up to date automatically, with an optional "Dev" toggle to preview
  unreleased shards ahead of time.
- **Settings screen**  a searchable, categorized settings menu (via
  ModMenu or the gear icon in the calculator screen).

## Requirements

- Minecraft 26.2, Fabric Loader 0.19.3+
- [Fabric API](https://modrinth.com/mod/fabric-api)
- [Fabric Language Kotlin](https://modrinth.com/mod/fabric-language-kotlin)
- [ModMenu](https://modrinth.com/mod/modmenu) (optional, for the settings screen entry point)

## Usage

- Press **K** to open the Fusion Calculator.
- Run `/sshs` or click the HUD button on the menu to reposition the HUD overlays.
- Open the settings screen from ModMenu, or via the gear icon in the
  calculator screen.

## Building

```
./gradlew build
```

The built jar is written to `build/libs/`.

## Credits

Shard, fusion and rate data, and the fusion-cost calculation algorithm,
are based on [skyshards.com](https://skyshards.com/) and its
[open-source repository](https://github.com/Campionnn/SkyShards).

## License

MIT - see [LICENSE](LICENSE).

