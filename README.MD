Look at the deployable you want the item of and press your attack3 button (middle mouse by default)

## Permissions

* `entityitempicker.use` - Allows picking item.
* `entityitempicker.bypass` - Bypass the cooldown,

## Configuration

```json
{
  "Use cooldown": true,
  "Cooldown duration": 3.0,
  "Maximum distance": 20.0,
  "Kill on pickup when holding sprint": false
}
````

* **Use Cooldown** - Do players have a cooldown between usages (if they don't have bypass permission).
* **Cooldown duration** - How long the cooldown is (in seconds).
* **Maximum distance** - The maximum distance until you cannot pick the item from the deployable.
* **Kill on pickup when holding sprint** - Is the entity killed if the player is holding their sprint button when they pick the item.
