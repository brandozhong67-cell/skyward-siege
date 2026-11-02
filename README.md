# Skyward Siege
A little lane defense game. Build a team of skyward defenders and protect the beacon from waves of cloud enemies.

## Play online
- [Play Skyward Siege on Netlify](https://skywardsiege.netlify.app/)
- [Play the GitHub Pages version](https://brandozhong67-cell.github.io/skyward-siege/skyward-siege.html)

## Download a local copy
Download the [standalone HTML game](https://github.com/brandozhong67-cell/skyward-siege/raw/refs/heads/main/skyward-siege.html) and open it in a browser. A local copy is a snapshot and does not update itself. Download the latest file again whenever an update is released.

## Goal and basic rules
Stop enemies from reaching the beacon. Each enemy that gets through costs 5 beacon health. Keep the beacon standing through increasingly difficult waves.
1. Choose a map and difficulty, then select **Start defending**.
2. Pick a defender from the list and click an open patch beside the trail to place it. Defenders need to be close enough to reach enemies, with space between each other.
3. Place at least one defender and start the wave. Defenders automatically attack enemies in range.
4. Earn coins from defeated enemies and wave-clear bonuses. Spend coins on defenders, upgrades, and power-ups. Earn XP to unlock more defenders.
5. Pause, change game speed, or adjust a selected defender between or during waves.

Every fifth wave is a boss wave. After wave 50, Tower Breakers can attack nearby defenders. Enemy health and speed increase over time. On Cinder Volcano, glowing vents warn before eruptions that can damage nearby units.

## New enemy types
- **Swiftlings** arrive from wave 4. They move quickly and have less health.
- **Armored clouds** arrive from wave 8. They move slowly and take more damage to defeat.
- **Elites** have extra health. **Bosses** appear every fifth wave. **Tower Breakers** join after wave 50 and attack defenders.

The field brief previews the enemy mix and count, coin bonus, and XP for the next wave.

## Defenders and upgrade paths
The first five defenders are available from the start:
- **Lookout** — quick, all-round shots
- **Frostbell** — slows nearby enemies
- **Starcaller** — heavy hit with a slower reload
- **Sunlance** — long range and heavy damage
- **Emberpot** — splash damage for groups

More defenders unlock with XP. Their strengths include rapid fire, slowing, long-range attacks, splash damage, and attacks that arc between enemies. Each defender can be upgraded twice for general range and damage improvements. At level 3, choose one final specialization:
- **Longshot** — greatly increases range with a small damage boost.
- **Rapidfire** — fires faster with a small damage boost.

Click a placed defender to upgrade it, choose its targeting priority (**First**, **Strongest**, or **Closest**), or sell it for 70% of its cost. Hover over an open patch to preview attack range; red indicates an invalid placement.

## Maps
- **Cloud Harbor** — winding harbor trail
- **Ember Ridge** — rocky ridge route
- **Moonlit Marsh** — winding marsh trail
- **Cinder Volcano** — volcanic route with erupting vents
- **Frostfall Pass** — icy switchback route

## Language options
Choose English, Spanish, French, Simplified Chinese (简体中文), German, Portuguese, or Japanese from the language selector in the header. The main menus, controls, map and difficulty choices, wave brief, and key gameplay guidance switch languages immediately. Tower names remain their in-game names; text without a translation uses English.

## Power-ups, sound, and music
Power-ups cost coins. Some are one-use effects, such as a repair, coin cache, freeze, or blast. Others last for several waves and improve range, damage, firing speed, protection, or repairs. Some unlock only after reaching a later wave. Their costs and effects are listed in the game. Use the **Sound** and **Music** buttons in the Incoming panel to toggle synthesized sound effects and background music. Both start off so the game is quiet until you turn them on.

## Save and load
Use **Save** between waves to store a checkpoint in this browser. The game also saves checkpoints after cleared waves and when you place, upgrade, or sell defenders. Choose **Load** to restore your latest saved wave, map, currency, defenders, and upgrades. Saves are stored locally in the browser and do not transfer to another device or browser.

## Auto-start waves
Turn on **Auto-start waves** in the Incoming panel to begin the next wave automatically after a 3-second countdown when the current wave is cleared. It works in Dev Mode too, but Dev Mode does not turn it on automatically. Turn auto-start off whenever you want to begin waves manually.
