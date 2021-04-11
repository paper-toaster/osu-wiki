---
needs_cleanup: true
---
<!-- TODO: needs a thorough review for writing style and organisation, this is one of the more awkward articles on the site -->

<!--
TODO (MilkyIQ):
- clear article of any placeholders (empty commnets)
- spellcheck
- check all headers and links
- update all images
-->

# Multi

**Multi** or **Multiplayer** is a game mode in which up to 16 players can compete against each other on a single map decided by the host. It has three different modes in which players can play competitively or cooperatively: [Team Mode](#team-mode), [Tag Coop](<!---->), and [Tag Team Versus](<!---->).

*Notice to `Cutting Edge` build users: In order to access the Multiplayer lobby and its functions, the signed-in account must have an active [osu!supporter](/wiki/osu!supporter).*

Players can find the Multi mode by pressing the `Multi` button under `Play` on the main menu, or by pressing the `P` key followed by the `M` key on the main menu to enter through keyboard shortcuts.

In order to access multiplayer functions, users must be connected to the internet and be signed in to their osu! account. If these requirements are fulfilled, upon entering, users will be directed to the *lobby*.

## Lobby

![](img/multi_lobby.jpg "Example of a typical day in the Multi lobby")

The lobby is the main page of Multi mode and will show all the currently available [matches](<!---->) that are availble. This list of matches can be filtered through the toolbar at the top-left to better help users find the matches they want quicker.

### Filters

*Note: By default, the lobby will filter by all game modes, and the `Show locked` and `Show In-progress` filters will be enabled.*

The aforementioned filter options are listed and described below.

| Title | Description |
| :-: | :-- |
| `All`/`osu!`/`osu!taiko`/`osu!catch`/ `osu!mania` | Only displays matches that are made for the specified [**game mode**](/wiki/Game_mode); `All` displays all matches regardless of game mode |
| `Owned Beatmaps` | Only displays matches that are playing or listening to beatmaps that the user already owns |
| `Show Full` | Displays matches that have all available [slots](<!---->) filled |
| `Search` | Only displays matches that are hosted by a user or playing/listening to a beatmap that is specified by the user; overwrites all other filters except `Show In-progress` when enabled |
| `Games with Friends` | Only displays matches that the user's friends are in; overwrites all other filters when enabled |
| `Show Locked` | Displays [locked](<!---->) matches when enabled |
| `Show In-progress` | Displays matches that are currently playing a beatmap |

Below the filters is the list of currently available matches. The list displays between 4–5 matches at one time and can be scrolled up or down through click-and-drag or mousewheel operations. Each of these listings contain elements that describe information about the match to the user, which are described in detail below:

*Note: If a match is currently in the middle of playing a beatmap, the text in its listing will change to grey with the text `(In progress)` appended to the end of the match title.*

### Symbols

<!--this is ungodly long. is this even neccessary?-->

- The *game mode symbol* indicates which game mode (![](wiki/shared/mode/osu.png) [osu!standard](/wiki/Game_mode/osu!), ![](wiki/shared/mode/taiko.png) [osu!taiko](/wiki/Game_mode/osu!taiko), ![](wiki/shared/mode/catch.png) [osu!catch](/wiki/Game_mode/osu!catch), or ![](wiki/shared/mode/mania.png) [osu!mania](/wiki/Game_mode/osu!mania)) the match is playing in.
- The *match type* or *mode* that the match is playing in enclosed in brackets (e.g., "Tag Co-op" or "Head-to-head")
- The amount of *player slots* that are currently filled in the match alongisde the maximum amount of players allowed in said match, represented via a fraction underneath the game mode symbol
  - These player slots are also indicated via a row of red or green highlighted squares indicating that a slot is taken or available respectively. There is also a single larger square that is at the very left of the row of squares which indicates the host of the match
  - The visual row of player slots contain the avatars of the players in the match. If the cursor is hovered above these avatars, a tooltip will display their username, rank, and country.
- The *rank difference* indicates the range of the leaderboard rankings of the players within the match, ranked from highest to lowest (e.g., `rank: 35,000 - 200,000`). The rank difference may occasionally be represented by a question mark (`?`) which denotes that there are either no player slots filled in the match, or there is a player in the match who's rank is unkown.
- The inclusion or exclusion of a *lock icon* (shown below) which indicates whether or not a match is locked
- The *match title*, denoted in white text above the player slots
- The *currently selected beatmap*, denoted in yellow text underneath the match title
To enter a Match Setup, click on one of the desired row.

![](img/Multi_lobby_locked.jpg "An example of a locked Match Setup")

Some matches may be labeled as *locked*, indicated via the inclusion of a lock icon being appended to the corner of the game mode symbol (shown above). Locked matches are matches that require a specified password to be entered before being able to join the match. This password is specified by the host during match setup. Alternatively, players can request an invite from the match's host directly to bypass the password.

---

## Match Setup

![](img/Multi_roomhost.jpg "Example of Host Match Setup")

![](img/Multi_roomplayer.jpg "Example of Player Match Setup \(with Free Mods enabled\)")

Once a user joins or creates a game, they will be placed on the *Match Setup screen*. The Match Setup screen is where players can chat, toggle mods, and listen to the currently selected beatmap. If a user is the host of the match, they are able to change certain settings regarding the match on the screen (e.g. mode, win condition, match name, password, etc.), as well as choose the beatmap to be played or kick certain players from the match.

### Players list

The left side of the scren displays the list of players currently in the match, along with anyo empty slots that could be filled. Players are allowed to move around the empty slots while waiting or change their flag colour to blue/red if it is a team-based match.

Each player slot will display a user's name, their rank, any mods they may have selected, and—if a player is the host of the match—a small crown will be displayed to the left of the player. Hovering abve a player bar will show the level, country, and [accuracy](/wiki/Accuracy) of the player in question.

Hosts can also kick players from the match by clicking on the boot icon to the left of the player's player slot.

Player slots will also display important information about their status via the color the slot:

| Colour | Description |
| :-- | :-- |
| **Red** | **The player does not have the current beatmap.** A `[no map]` notice will be appended at the end of player's name until the beatmap has been downloaded. |
| **White** | **The player does have the current beatmap, but is not ready to start the match.** The match will not be able to auto start if any players are in this state, however <!--left off here-->  |
| **Green** | **The player has the current beatmap and is ready to start the match.** Game modifiers cannot be changed in this state. A player can press Not Ready button to return to white state but for a host, it is usually a one-way trip unless there were no players except the host, which a return to white state by pressing the Not Ready button will be allowed. |
| **Light Blue** | **The player is playing**. A `[playing]` notice will be appended at the end of player's name until the match ended, in which the player will return to white state. |

#### Mods

![](img/Multi_mods_host.jpg "Host \(osu!\) mods options")

![](img/Multi_mods_player.jpg "Player \(osu!\) mods options \(with Free Mods enabled\)")

The lower left section is the Mods section.
This section will show the [game mods](/wiki/Game_modifier) used for this match.

For host-side, the host can enable `Free Mods` to allow players to use any mods _except_ Speed ([Double Time (DT)](/wiki/Game_modifier/Double_Time)/[Nightcore (NC)](/wiki/Game_modifier/Nightcore) or [Half Time (HT)](/wiki/Game_modifier/Half_Time)) mods.
Host-selected mods other than the Speed mods will not be enforced upon players.

---

#### Team Mode, Win Condition, Tag Colour

The lower right section will shows how the beatmap will be played in the match (Team Mode) and the Win Condition.

##### Team Mode

Team Mode contains four ways of how a match will be played:-

| Team Mode | Description |
| :-- | :-- |
| `Head to Head` | Compete against each other to reach the top spot of the match leaderboard. |
| `Team Vs` | Compete against Red/Blue team for match supremacy. |
| `Tag Coop` \[osu! only, UNRANKED\] | Team up to complete the beatmap, one combo at a time together. |
| `Tag Team Vs` \[osu! only, UNRANKED\] | Tag Coop, with Red Team and Blue Team match competition. |

**Note:** The winner's avatar will be shown at the grade screen for Head to Head Team Mode only.

##### Win Condition

Win Condition contains four ways of how a match will be decided:-

| Title | Description |
| :-: | :-- |
| `Score` | Player with **highest score** wins. |
| `Accuracy` | Player with the **highest accuracy** wins. If there are two players with 100.00%, the player with the highest score (from spinners) wins. Unconfirmed, if there were no spinners. |
| `Combo` | Player with the **highest combo count** _at the end of the beatmap_ wins. If combo count is the same, player with the highest score wins. **Maximum combo not counted**. |
| `Score v2` | Player with **highest _standardised_ score** wins. |

##### Tag Colour (Tag Coop/Tag Team Vs only)

![](img/Multi_tag_colour.jpg "Available colours for the player's turn combo colour")

If Team Mode was set to _Tag Coop/Tag Team Vs_, a **Tag Colour:** `(combo colour)` section will be shown which **allows fixed combo colour when it is the player's turn**.
The `Default` option will use the original beatmap's combo colour for the combo instead.

### Match Setup buttons

Lastly, there are two buttons coloured brownish-orange `Leave Match` at the left and blue `Ready!`/`Not Ready`/`Start Game!`/`Force Start Game!` button at the right respectively.

The `Leave Match` button is self-explanatory; leave the Match Setup and return to the Lobby.

For the blue button, it can change depending on action taken and host/player privilege.
The different effects of the blue button can be seen below:-

| Title | Description |
| :-: | :-- |
| `Ready!` | Click to **enter Ready state (green state)**. Button will change to `Not Ready` for players; either `Start Game!` or `Force Start Game!` for host if there are players in the Match Setup, `Not Ready` otherwise. |
| `Not Ready` | Click to **return to Not Ready state (white state)**. Button will change to `Ready!` |
| `Start Game!` | Host-only button; **starts the match**. Appears with a distinctive ring when all players in the Match Setup in Ready! state (green state) including the host. Will switch to `Force Start Game!` when at least one player pressed the `Not Ready` button or new players coming in. |
| `Force Start Game! (x/y)` | Host-only button; **forcefully ready all players with the beatmap** and **starts the match**. Appears when host press the `Ready!` button but not all players in the Match Setup pressed the `Ready!` button (where `x` is the number of players in Ready state, and `y` is the total players in the Match Setup). |

### Match History

**Note**: The link provided by BanchoBot at the first line of the `#multiplayer` tab in Chat Console (specifically, the `here` keyword) will direct the player to the Match History for the Match Setup in the player's default web browser.

![](img/multi-mh.jpg "Example of Match History.")

## Team Mode

### General

#### The Esc key

In general, pressing the `Esc` (Escape) key in keyboard now _does not pause the match_; in fact, it will trigger a warning at the lower-right to press `Esc` key again to quit.
To quit the match and return to lobby, press it _again_.

#### Visual Settings

Some time will be given to use the Visual Settings below the beatmap during the loading phase of the beatmap.
If `Free Mods` was used, the game modifiers used applies to per player's interface and score differences may occur depending on game modifiers used.
Other players' interface may vary.

#### Health bar

When a player's health bar has been depleted completely, the player's beatmap play is considered failed.
Entering failed state at least once will consider the score and accuracy of this match to not be counted as ranked entry.
However, the failed player can continue playing and can be revived upon reaching full health.

If [Sudden Death (SD)](/wiki/Game_modifier/Sudden_Death)/[Perfect (PF)](/wiki/Game_modifier/Perfect) was used, revival from failed state is impossible.

#### Result, Retry, and Replay

Despite no online score leaderboard below the results screen, ranked score will still be counted as legitimate ranked entry.
Result will not be shown at the Local leaderboard.
The only way to see it is by Online Ranking leaderboard (assuming the Multi's score is higher).

**No direct retry allowed** but the replay can be exported by pressing `F2` key in keyboard (will not contain any Multi-play elements and will not be saved in the osu! backend).
Do note that this does not apply to Tag Coop and Tag Team Vs (both are unrankable), where score will not be recorded and replay cannot be saved.

#### Multi's leaderboard

The leaderboard now shows the players in the match with live changes based on Win Condition as shown below:-

**Head to Head / Team Vs:*

- If Score/Score v2: Score, hit score and combo multiplier are shown in real-time.
- If Accuracy: Accuracy, hit score and combo multiplier are shown in real-time.
- If Combo: Combo count are shown in real-time. Maximum combo count not shown.

**Tag Coop / Tag Team Vs:*

- If Score/Score v2: Team's score and hit score are shown in real-time.
- If Accuracy: Team's accuracy percentage and hit score are shown in real-time.
- If Combo: Team's current combo count, score and hit score are shown in real-time.
- If _Failed_: Match ends and \[Tag Coop\] return to the Match Setup or \[Tag Team Vs\] automated win for the surviving team.
  - The failed players will not contribute towards the team score until revived back upon reaching full health.
- If _Quit_: [Auto](/wiki/Game_modifier/Auto) will take over the _Quit_ player.
  - If all members of the same colour team left the match, the match will end with the win on the other colour team.

A failed or quitted player will be placed at the bottom of the leaderboard separately from other alive players, and placement changes can still occur among failed/quitted players.

#### Player box colour

<!-- A player box reference here? Old images in img/Playerbox -->
<!-- Special player box note: Skipped (has its own special callout), Failed (red text), and Quit (red text with [Quit] appended) -->

| Status/Colour | Description |
| :-: | :-- |
| **Normal/Blue** | **Player has _more_ than half of health**, usually at full. The concentration of blue colour will grow brighter if the player's health bar is increasing to full and bleed to red by losing the health bar more than half of the health bar length. |
| **Danger/Purple-Red** | **Player has _less_ than half of health**. The concentration of red colour will grow brighter if the player's health bar is decreasing to empty and diminished to blue by filling the health bar more than half the health bar length. |
| **Failed/Grey** | **Player unable to reserve the final sliver of health/no health left in the health bar**. The player can continue playing and if [Sudden Death (SD)](/wiki/Game_modifier/Sudden_Death)/[Perfect (PF)](/wiki/Game_modifier/Perfect) was not used, refilling the health bar completely will "revive" the player from the failed status to normal. Also, score will not be contributed towards the team score at this state. Text colour will be changed from white to red. |
| **Tag/Green** | _Tag Coop and Tag Team Vs only_. **This is a permanent colour scheme for the match to all and will not change based on health bar status**. There will be a green arrow pointing to the current player playing the beatmap with a subtle white glow. |
| **Skipped/White** | **A request notice from the player to skip the start-up rest if the beatmap/difficulty has a start-up rest**. Players that press the `Skip` button at the lower-right of the screen will be given a small yellow box at the lower right on their box with white Skipped text. **All players must do so for the Skip to take effect**. |
| **Quit/Varies** | **Player quit the match**. Two possible ways to enter this state: (1) hitting `Esc` twice, or (2) disconnected from Bancho. Text colour will be changed from white to red, with `[Quit]` appended at the end. Box colour signify the status before quitting the game. |

### Head to Head

#### Interface

![](img/Multi_HTH.jpg "Head to Head Interface")

Head to Head is a team mode where players duke it all out in a free-for-all Match Setup for the top spot at the leaderboard.
The default team mode to be selected and does not have any special characteristics in play; just go for the top spot.

#### Result

![](img/Multi_grade.jpg "Head to Head grade screen")

At the end of the match, first place player's avatar image will be shown at the Winner section.

The grade image is now placed behind the result like a watermark.
Other players' results can be checked by pressing the player's respective player box.

Each players will receive personalised match result placement privately under `#userlog` tab of the Chat Console.

### Team Vs

#### Interface

![](img/Multi_team_vs.jpg "Team Vs Interface")

Team Vs mode pit two teams (Blue/Red) against each other based on Win Condition set.
Fulfill the Win Condition criteria as closely as possible to reach the top spot in the team and compete with the other team by team total.

Blue team members are placed at left side, red team members are placed at right side, and a crown at the center shows the current team supremacy.
It will move left and right depending on which team fulfill the Win Condition most closely.

When this mode was selected, all players in the Match Setup will receive either red or blue flag.
The players can click on it to change from blue to red or vice versa.

It is entirely possible to start a match with one colour team only, and there is no handicap bonus for the other team with lesser members.
Placement of the players prior to the match does not matter; all blue members will be grouped to blue team and all red members will be grouped to red team.
There is no role (like "Leader" or "Captain") distinction in the team; just compete for both the team top spot and beating the other team score in total as a team.

The surviving highest scoring member of either team will be shown as `1st` at their respective team.
Members in failed state will be located at the bottom of the team leaderboard and will not contribute to the team total as long as the members are in failed state.

#### Result

![](img/Multi_team_grade.jpg "Team Vs grade screen")

In the results screen, declaration of match winner will be based on team total and announced at the center in winner's colour, with blue team total at the left and red team total at the right.

**Only surviving members of the team's score will be counted**; it is possible for red team to be declared winner of the match when blue team has the superiority _just because_ some blue team members providing the superiority were in failed state or all members in the blue team failed.

The `Total` tab will show the total amount of hit score (300, 100, etc) done by the whole team and the average of the accuracy of the team.
Combo will not be counted in the team's `Total` tab.
Grade will not be shown on `Total` tab but will be shown at player's result screen as watermark (if passed).

### Tag Coop / Tag Team Vs

#### Interface

_Only available in osu! mode. **UNRANKED**_

![](img/Multi_tag_co-op.jpg "Tag Coop Interface")

![](img/Multi_tag_team_vs.jpg "Tag Team Vs Interface")

Tag Coop makes all players in the Match Setup work together to pass the beatmap, one combo at a time.
Tag Team Vs is just Tag Coop with red and blue team competition.

Do note that this team mode is only available in **osu! only** and _unranked_ (meaning, it will not be counted to ranked score).

In this mode, player's slot placement starting from top-to-bottom is important as it will determine when it is the player's turn.

A green arrow will show the player who is currently playing the beatmap's combo.
The player's name will be shown at the lower right of the screen.
There will be warning arrows when it is the player's turn and the combo will be in colour until the combo ends.
The player can adjust for fixed combo colour at Match Setup under **Tag Colour**.

**All players must spin the spinner**.
Refusal or unable to complete the spinner will break the current combo count.

If a player quits during the match, [Auto](/wiki/Game_modifier/Auto) will take over for the player that left.

For Tag Coop, all players will share the same health bar.
If the health bar was depleted completely (failed state), the match ends and all players return to the Match Setup immediately without result.

For Tag Team Vs, each team has its own respective health bar that are visible to teammates only.
If the health bar was depleted completely (failed state), the match ends by giving victory to the other team.

If [Easy (EZ)](/wiki/Game_modifier/Easy) game modifier was used, the two health bar refill provided by the game modifier will still occur but will be depleted completely immediately after _just_ to fail the beatmap.

Players using [Sudden Death (SD)](/wiki/Game_modifier/Sudden_Death)/[Perfect (PF)](/wiki/Game_modifier/Perfect) game modifier will have a different interface than other players, especially when it comes to the effects.
If the teammate does **not** use that game modifier and made a small mistake enough to trigger the mod effect, the beatmap will continue as normal, and players using the mod will have their health bar interface drained and stuck to empty with no ill effect (meaning, visual effect only).
If the player _using_ the mod made a mistake and triggered it, the actual effect will occur and failed state will be triggered immediately.

When playing in windowed mode, do note that the cursor will **not** be bounded to the osu! window during the break/not the player's turn yet.

#### Result

![](img/Multi_co-op_grade.jpg "Team Co-Op grade screen")

![](img/Multi_tag_team_grade.jpg "Tag Team Vs grade screen")

As stated before, score will not be counted for ranked score and performance points calculation because it is an _unranked_ play.

For Tag Coop, the result shown is the total score, hit score and accuracy of the team.
Individual results will not be shown, and can only be seen in Match History.
The result screen only appear if the beatmap was cleared successfully.

For Tag Team Vs result screen, refer to Team Vs's result screen explanation.

## Trivia

### History

![](img/Multi_Mania_unpatched.jpg "Screenshot of Lobby of an unpatched osu! when osu!mania was released to public \(08 October 2012, 2012-10-08\)")

- Match Setup used to only allows up to a total of 8 players only.
- osu!mania game mode was noted as `3` in Lobby for players that have not yet updated their osu! to the latest release patch (which enables osu!mania mode with no ranking support yet).
- No Video was the _only_ game modifier allowed for the players to use; however, it was removed in favour of its placement in the Visual Settings.
- Multi was implemented on 03 June 2008 (2008-06-03) under osu! Public Release b335x
- The [osu!academy](/wiki/osu!academy) covered this topic in [Episode 6 (6:52)](https://www.youtube.com/watch?v=cyYRl-a5xII) along with the [Online Users Panel](/wiki/Chat_Console#extended-chat-console)
- Losing connection to Bancho will direct the player back to main menu
- To access the Options screen while in a Match Setup, press `Ctrl`+`O`
- Creating a new game with no name will default to "{host}'s game"
