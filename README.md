# PTFS-Explorer
PTFS Explorer is the best Roblox PTFS script. The script should work with *most* executors.

Paste this snippet into your executor and execute it to load PTFS Explorer:
```lua
loadstring(game:HttpGet("https://raw.githubusercontent.com/dfano-dev/PTFS-Explorer/refs/heads/main/Releases/0.12.lua"))()
```

Current Version: 0.11
> [!TIP]
> This script only works inside of [PTFS](https://www.roblox.com/games/20321167/Pilot-Training-Flight-Simulator) (Pilot Training Flight Simulator)

UI Preview:

<img width="286.5" height="291.5" alt="UI Preview" src="https://github.com/user-attachments/assets/5ab76fc0-1484-4568-aee6-b341a1d24e9b" />

PTFS Explorer is a multi-featured PTFS script made with [Rayfield UI](https://docs.sirius.menu/rayfield-gen2). It includes features allowing you to modify the plane, teleport, change player stats, and more. A full list of features is below.

## Usage / Features

### Section 1 (Player):

<img width="250.5" height="269.5" alt="Player Section" src="https://github.com/user-attachments/assets/0f8dfe9f-ec70-4189-9c4e-e1de62cc8b29" />

#### Walkspeed (Slider)
Slider that lets you adjust walkspeed. (Resets when you use the run tool.)

#### Jumppower (Slider)
Slider that lets you adjust your jump power.

### Section 2 (Plane):
*It's important to note that these changes are made locally. People can be on your plane while you're flying it, and the changes will show up for them, but if they fly the plane, the plane will be normal.*

<img width="259" height="275.5" alt="Plane Section" src="https://github.com/user-attachments/assets/cdc42703-faac-4e29-bbf6-a24fdb6251e2" />

#### _Choose Plane_ (Button)
This feature may soon be deprecated. Click this if the plane did not automatically select once you entered it (if this happens, please create an issue with an error log).

#### Apply Changes (Button)
Click this button after you've made your changes. Because of the way PTFS works, it's difficult to make this automatically apply without ruining the UX.

#### Plane Max Speed (Slider)
Adjusts the maximum speed of the plane.

#### Plane Acceleration (Slider)
Adjusts the kts/s the speed increases/decreases.

#### Plane Maneuverability (Slider)
Changes how well the plane can turn. This slider works in reverse; the lower the number, the better the plane turns.

### Section 3: Players

<img width="253.5" height="270.5" alt="Players Section" src="https://github.com/user-attachments/assets/3de6ef0a-155c-4348-9a4d-49c139112554" />

#### Player (Dropdown)
Select a player to use these tools on. (Automatically updates)

#### Enter Plane (Button)
Tries to enter the player's plane. Prioritizes entering the co-pilot seat; however, if the co-pilot seat is filled up, it enters a passenger seat. If there are no extra seats, it will not teleport you.

#### Teleport (Button)
Teleports to the player.

### Advanced

<img width="254.5" height="268.5" alt="Screenshot 2026-08-03 at 12 16 41 PM" src="https://github.com/user-attachments/assets/2a0a9cc3-461f-465a-b4de-3ed215a71bed" />

#### Share Data? (Toggle)
As of now, this toggle does not do anything. In the future, it may share error messages and logs.

#### Auto Select Plane (Toggle)
Recommended to keep this on. Automatically selects any plane you enter (as long as you enter the pilot or copilot seat.)


## to-do

Add a reset button for plane stats.


Made by [repend.](https://discord.com/users/1207042199792132127)
UI by [Rayfield](https://docs.sirius.menu/rayfield-gen2).
Obfuscated by [Moonveil](https://moonveil.cc/).

