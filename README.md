> In sandbox, type TAB to enter a command

### Cast a spell
Just type the spell name and press ENTER (e.g. shock bomb, mud ball, fissure, ...)
The spell is thrown at the direction of your cursor
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/26984b19-e560-47de-9902-93ecd621c110

### Throwing power
You can set the power with which you throw a spell using the command `power.NUMBER` where `NUMBER` is a number between `50` and `2000`
Every spell that you cast after setting a specific power, will be thrown at that power.
E.g.: `power.2000` and afterward `mud ball` and then `shock bomb`. Both spells will be thrown at power `2000`.
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/204e012a-2dce-4233-b802-a77cd7eee73f

You can also chain a spell to the power command: `power.50.shock bomb` will throw a `shock bomb` at power `50`.
Note: this also sets the power for all following spells that you cast via a command.
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/87920d76-cfb7-4172-88db-2c5ad482155f

### Wind
You can enable / disable wind with the `wind` command.

When wind is enabled, you can set the wind direction using `winddir.NUMBER` where `NUMBER` is a number between `0` and `360`.
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/1adf5ca7-32ca-4cdf-9798-07231cbfa3d1
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/94354bc1-38e3-481d-bc81-59a55c92578b

When wind is enabled, you can set the wind speed using `windspeed.NUMBER` where `NUMBER` is a number between `0` and `100`.

https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/8835e2c4-82b3-4767-8749-33205c490899

### Spawn a player
You can spawn new players using the `spawn` command. Optionally name them using `spawn.NAME`.
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/a83918dc-dbb4-4175-a7f6-04980da8eb8d

There are multiple ways to have spawned players cast a spell using a command:
1. Select the player you spawned FIRST by prefixing your spell with `z.`
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/653f5e92-5b98-456d-bf66-70b5b0658b51
2. Select the player by name using the `byname.NAME.` prefix
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/61b80075-42fa-4c58-b72f-76b8167c35c7
3. Select the player by their index (you are 1, first spawned is 2, second spawned is 3, ...) using the `pNUMBER.` prefix
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/af98bcda-0aca-4947-9f99-cb52d1b8bc06

### Have a minion cast a spell
This works with the `mNUMBER.` prefix. This works the same as the `pNUMBER.` prefix, but for minions instead of spawned players.
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/b2a80ebd-33b1-431f-827e-116a27291463

### Teleport
Use the `move.X,Y` command to teleport (note: this command is broken, `Y` will always be `0`)
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/eee24529-bfcf-454f-88d6-3ef2659ab808
Reason this command is broken: ![13](https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/08af409d-34ea-4006-9019-d47c79c3272c)
You can teleport spawned players or minions too by prefixing the command with the `z.`, `byname.NAME.`, `pNUMBER.`, or `mNUMBER.` commands
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/bf2154fd-0fa2-4f39-ac23-80e9225bae64
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/bd4de6bb-5b61-44bc-91f2-55cf23a8ce1d

### Health
Change your health (or the health of a minion / spawned player) with the `health.NUMBER` command
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/b9b5bdd9-924f-4fec-b5f2-eee79f8652a0

### Max health
Change your max health (or the max health of a minion / spawned player) with the `maxhealth.NUMBER` command where `NUMBER` is a value between `1` and `10000`.
Note: this command is broken, when you use it your max health will be set to `1`.
Reason this command is broken: ![17](https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/e04aefde-40b0-4dd0-a289-1e3c9556f190)

### Armageddon
No armageddon yet? Create a new one using `arma.SPELLNAME` e.g. `arma.shock bomb` or `arma.volcano`.
You can have multiple armageddons, just reuse the above command (optionally with a different spell).
Reset armageddons? Just use `arma`.
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/a1352d8c-193c-4e8d-852a-b621b0bb18e7
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/ce4e72ac-58ca-4eb9-8850-b8bb17cda0e7

### Add a spell to your book
This can be done with the `add.SPELL NAME` command (e.g. `add.shock bomb`)
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/8d55b84a-286c-41b4-ac99-b2689e4abcef

### Add all spells to your book
This can be done with the `addAll` command
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/7a5a28d4-68aa-40c5-b9e5-c27cd4e52761

### Cast all spells
You can cast all spells with the `all` command
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/57fbeaa3-f577-4631-aed5-37df8ea8a7cd

### Spectator ship
Create the spectator ship with `ship`
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/30261caa-a4ce-4d64-b18a-2f17eac7e8fa

### Change FPS
Change your client's frames per second using `fps.NUMBER`
https://github.com/Kattoor/arcanists2-sandbox-commands/assets/8040542/889d6c67-631a-46ae-bb36-c7d233862966
