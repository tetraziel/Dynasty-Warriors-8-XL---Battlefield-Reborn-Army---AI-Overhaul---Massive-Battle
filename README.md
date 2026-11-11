# Dynasty-Warriors-8-XL---Battlefield-Reborn-Army---AI-Overhaul---Massive-Battle
Reforge DW8 XL with personal armies, Story Mode bodyguards, tactical commands, gate reinforcements and more reactive AI. Features morale-based replenishment, rebalanced offscreen battles, expanded NPC activity and display options, plus returning Ambition Duels. Customize your experience with a sample tool.

📢 Why This Mod Is Now Available on GitHub

Due to numerous requests from Nexus Mods users, I have decided to make this mod available on an alternative platform.

Unfortunately, Nexus Mods has not responded to my requests for a review of the mod, despite multiple follow-up messages and emails. More than two weeks have passed without any meaningful response or update.

Rather than keeping the community waiting indefinitely, I have decided to publish my work here on GitHub, allowing players to access, download, and enjoy the mod without further delays.

Thank you to everyone who has shown interest, provided feedback, and supported this project. Your enthusiasm is what keeps me developing and improving it.

⚠️ IMPORTANT ANNOUNCEMENT — UPCOMING HARDCORE UPDATE

I am currently working on a major update that will introduce two additional difficulty modes: HARDCORE and HARDCORE+.

These new modes are specifically designed for the endgame experience, giving greater importance to high character levels, advanced equipment, and fully developed warriors.

The goal is to make maximum-level characters truly meaningful by introducing significantly more challenging battles, stronger enemies, and a greater need for tactical combat.

HARDCORE will offer a substantial increase in difficulty for experienced players.

HARDCORE+ will take the challenge even further, targeting players who have reached the highest levels and want to push their characters, equipment, and combat skills to their limits.

Both modes aim to extend the game's longevity and provide a rewarding challenge beyond the original endgame.

This update is currently in development. More information will be shared as development progresses.

Thank you for your patience and continued support!

— Arcaraziel

Description
Bring a new tactical dimension to Dynasty Warriors 8: Xtreme Legends Complete Edition.
This mod expands the role of your army, bodyguards and battlefield orders. Command personal squads, send bodyguards to different parts of the map, defend important positions and receive reinforcements through native gates. Changes to NPC behavior and offscreen battle calculations make troop numbers, positioning and support more relevant to the outcome of a fight.
It also adds new options for Ambition Mode, including returning Duel battles after collecting all 20 camp symbols, configurable material rewards and longer battles.
The mod runs through a standalone tool and applies its changes to the running game’s memory. It does not replace or directly edit the original game files.
This is my first major mod, and I only started developing recently. Constructive criticism, suggestions and comments are very welcome. I apologize if you encounter bugs: I am still learning, and your feedback will help me improve the project.

Installation instructions
Download the archive and extract the entire folder to a location of your choice.
Keep DW8ArmyAI.exe, the runtime folder and all accompanying files together. Do not move the executable by itself.
Start the game normally.
Open DW8ArmyAI.exe.
Run.cmd
is an alternative launcher; you do not need to use both.
Use Browse to select the executable that actually runs your game. This is usually
Launch.exe
. The selected path is saved automatically.
Choose your options. Click the “?” button beside each section to read its explanations.
Press Save Settings to remember your preferences for future launches.
Press Start to connect the tool to the running game. Enter a new battle for features that modify battle initialization.
While connected, Apply Settings applies your current selections to the game. Save Settings remembers them for the next launch; saving alone does not activate the mod.
Press Stop before closing or switching to another version of the tool. Troops, orders and other effects already created during a battle may remain until that battle ends.
No mod manager, Cheat Engine or separate Python installation is required. The necessary runtime is included.

Main features
Your personal army
Fight alongside up to 120 personal soldiers, organized into four squads. Their availability remains subject to native group capacity and battle conditions.
Personal squads receive map markers, native HUD command icons and in-game order messages.
Position-defense commands
Use the key assigned to Command Bodyguard 4, normally Q, to cycle through three orders:
First press: two squads defend your current position.
Second press: those squads remain at the first position, while the other two defend your new position.
Third press: all personal squads follow you again.
This lets you leave troops protecting a captured position while you move elsewhere.
Bodyguards in Story Mode
Adds two fixed generic support officers to Story Mode: Unit Commander and Assault Captain.
They appear as bodyguards and use the native bodyguard menu for battlefield orders. These are predefined support officers, rather than freely selectable playable characters.
Bodyguard armies
Each available bodyguard can receive up to 120 additional soldiers, organized into four squads. This does not require the bodyguard to possess a troop-summoning battle skill.
Their armies operate separately from your personal squads. Available group slots and native construction rules still limit how many soldiers can be added.
Improved bodyguard orders
Secure Base becomes repeatable, with dashes replacing its remaining-use number in the tested menu.
Mobilize allows you to select a destination point. After reaching it, the guard resumes advancing against enemies—even when the selected location contains no base to capture.
The modified Secure Base shortcut can cycle through Secure Base, Mobilize and Guard, while ordinary Mobilize and Guard shortcuts retain their native behavior.
Gate reinforcements and morale
Added armies replenish through eligible native gates, with an independent 30-second minimum wait for the player and each bodyguard army. Travel time follows that wait, and native restrictions can delay a wave further.
When morale-based replenishment is enabled, the blue share of the morale bar determines the replenishment target:
Allied morale	Replenishment target
Below 40%	Up to 30 soldiers
40% to below 50%	Up to 60 soldiers
50% to below 75%	Up to 90 soldiers
75% or higher	Up to 120 soldiers
A drop in morale does not automatically remove surviving soldiers.
More reactive AI and revised officer targeting
Aggressive AI Global combines the three tested AI behavior changes with the infantry-damage correction and officer-targeting adjustments.
Enemy officers can prioritize recognized concentrations of nearby allied infantry, including troops outside your personal army. The tested crowd condition uses at least 50 allied soldiers within 1,200 game units, alongside a 2,000-unit player-pursuit limit.
These changes target behavior without switching the entire game to a higher difficulty or applying a blanket damage and defense multiplier.
Added bodyguard infantry is also treated as ordinary soldiers in the verified officer-damage calculation. This correction does not directly rewrite their HP or defense statistics.
Rebalanced offscreen battles
Tactical abstract parity removes a tracked difficulty-based rank advantage from the verified offscreen battle coefficients.
Offscreen zone forces adds eligible troop and officer quantities to the zone comparison. Each officer contributes the equivalent of 50 soldiers, while morale contributes up to ±25%.
These options give numerical support and positioning more influence. Native events and other battle rules still affect the outcome.
Ambition Mode changes
30-minute battles: increases the initial time limit of fresh Ambition battles.
Disable time bonuses: suppresses the tested officer-defeat and 100-KO time rewards, preventing those bonuses from reducing an extended timer to the original cap.
Returning Duel battles: after collecting all 20 decorative camp symbols, restores random eligible Duel choices for battles 3, 6, 9 and so on.
Configurable material rewards: modified Duel material results receive a base ×2, followed by your chosen difficulty percentage. For example, 100% gives ×2 overall, while 150% gives ×3.
Officer material drops: eligible officer defeats in modified Duels award one additional Facility Material and one additional Weapon Material.
Fresh bodyguards each battle — experimental: attempts to restore selected guards for the next fresh Ambition battle, including defeated guards. Enable it before the series. Its return and HP behavior still require further live testing.
Population and display options
Choose Native, +50% or +100% troop density for eligible existing groups, request full squad membership, extend tested NPC activity distances and adjust NPC request budgets.
Fog Distance 100000 extends verified distance calculations under the supported graphics settings.
Request-budget values are not counts of simultaneously visible soldiers. These options do not expand the native engine pools. The engine can still limit which NPCs are active or rendered.
Saved preferences and built-in help
The public tool includes a saved executable selector, Save Settings, clear status messages and a separate help window for each section. Developer scan/check controls and the debug panel are omitted.

Requirements
Windows 10 or Windows 11, 64-bit. The included runtime does not support 32-bit Windows.
Dynasty Warriors 8: Xtreme Legends Complete Edition for PC, with an executable matching the currently supported build. Development and testing used my Steam PC installation.
Keep the complete extracted tool folder together. No separate Python installation is needed.
Use the game’s Characters: Many setting for the extended NPC activity features. Read the Population and display help for the Fog option’s additional conditions.
Run only one instance of the Army & AI tool against the game at a time.
Executable names and paths containing Chinese, Japanese or other Unicode characters are supported. However, different regional builds, updates or modified executables may require a separately verified compatibility profile. Selecting an executable does not automatically make its internal code compatible.
Larger population, activity and display settings can increase hardware demands. Some changes require a new battle or a native view update before their effect becomes visible.
If you report a problem, please include your Windows version, game edition, selected options and any error message shown by the tool.

Shout outs
Thank you to everyone who tries the mod, shares feedback and helps me learn. This is my first large project, and constructive criticism is always appreciated.
Special thanks to Player436 and PythWare for their earlier research. Their work gave me valuable material to study and helped me understand the systems behind this project.
