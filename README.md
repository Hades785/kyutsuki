# Kyutsuki

Kyutsuki is a Discord bot built with [Discordeno library](https://github.com/discordeno/discordeno) using the [Discordeno boilerplate repository](https://github.com/discordeno/discordeno-bot-template).

<!-- This project uses a [fork of Discordeno](https://github.com/Hades785/discordeno) to patch some features in, and unnecessarily uses a submodule to have it on hand, but doing it this way is fun. -->

## Pre-requisites

- Required:
  - [Deno](https://deno.land)
- Optional:
  - [Velociraptor](https://nest.land/package/velociraptor)

## Step By Step

1. Clone this repository: `git clone --recurse-submodules git@github.com:Hades785/kyutsuki`
   - If you haven't cloned with `--recurse-submodules`, you can initialise the submodules with `git submodule update --init --recursive`
2. Create your `configs.ts` file in the main folder by copying or renaming `configs.example.ts`
3. Start the bot: `deno run -A --quiet mod.ts`
    - if you have Velocirator installed, you can also use `vr start`
