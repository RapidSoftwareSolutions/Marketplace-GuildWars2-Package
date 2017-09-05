[![](https://scdn.rapidapi.com/RapidAPI_banner.png)](https://rapidapi.com/package/GuildWars2/functions?utm_source=RapidAPIGitHub_GuildWars2Functions&utm_medium=button&utm_content=RapidAPI_GitHub)

# GuildWars2 Package
Guild Wars 2 is a massively multiplayer online role-playing game developed by ArenaNet and published by NCSOFT
* Domain: [GuildWars2](http://https://guildwars2.com)
* Credentials: apiKey

## How to get credentials: 
0. Browse to [Arena.net](https://account.arena.net)
1. Register or log in
2. Create apiKey at [Applications page](https://account.arena.net/applications)



## Custom datatypes: 
 |Datatype|Description|Example
 |--------|-----------|----------
 |Datepicker|String which includes date and time|```2016-05-28 00:00:00```
 |Map|String which includes latitude and longitude coma separated|```50.37, 26.56```
 |List|Simple array|```["123", "sample"]``` 
 |Select|String with predefined values|```sample```
 |Array|Array of objects|```[{"Second name":"123","Age":"12","Photo":"sdf","Draft":"sdfsdf"},{"name":"adi","Second name":"bla","Age":"4","Photo":"asfserwe","Draft":"sdfsdf"}] ```
 

## GuildWars2.getAccountInfo
This resource returns information about player accounts.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getMyAchivements
This resource returns an account's progress towards all their achievements.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getVault
This resource returns the items stored in a player's vault (not including material storage).

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getDungeons
This endpoints returns an array of strings representing dungeon path names completed since daily dungeon reset. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getDyes
This resource returns the unlocked dyes of the account. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getFinishers
This resource returns information about finishers that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getGliders
This resource returns information about gliders that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getCats
This endpoints returns an array of objects with the following: id (number) - The id for the cat. hint (string) (optional) - A hint to identify what is needed for each cat.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getNodes
This endpoint returns an array of strings. Each string represents the name of a particular node.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getInventory
This resource returns the shared inventory slots in an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getMailcarriers
This resource returns information about mail carriers that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getMasteries
This resource returns information about masteries that are unlocked for an account

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getMasteryPoints
This resource returns information about the total amount of masteries that are unlocked for an account. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getMaterials
This resource returns the materials stored in a player's vault. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getMiniatures
This resource returns the unlocked miniatures of the account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getOutfits
This resource returns information about outfits that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getPVPHeroes
This resource returns information about pvp heroes that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getRais
This endpoints returns an array of strings representing raid encounters completed since weekly raid reset.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getRecipes
This resource returns information about recipes that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getSkins
This resource returns the unlocked skins of the account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getTitles
This resource returns information about titles that are unlocked for an account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getWallet
This resource returns the currencies of the account. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getAchivements
This resource returns all achievements in the game, including localized names and icons.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Achievement ids to return

## GuildWars2.getAchivementsCategories
This resource returns all the categories for achievements.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Category ids to return

## GuildWars2.getDailyAchiements
This resource returns the current set of daily achievements.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getTomorrowAchievements
This resource returns the next set of daily achievements.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getAchivementsGroups
This resource returns all the top-level groups for achievements.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Group ids to return

## GuildWars2.getAnswers
This resource returns information about the Biography answers that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Answer ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.getQuestions
This resource returns information about the Biography questions that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Question ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.getBuild
This resource returns the current build id of the game. This can be used, for example, to register when event timers reset due to server restarts.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.listCats
List of cats in the gamge

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Cat ids to return

## GuildWars2.getCharacters
This resource returns information about characters attached to a specific account.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Character ids to return
| page  | Number     | Number of page to return

## GuildWars2.getSingleCharacter
This resource returns information about character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterHeropoints
This resource returns information about heropoints of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterBackstory
This resource returns information about backstory of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterCore
This resource returns information about core of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterCrafting
This resource returns information about crafting of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterEquipment
This resource returns information about equipment of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterInventory
This resource returns information about inventory of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterRecipes
This resource returns information about recipes of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterSab
This resource returns information about sab of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterSkills
This resource returns information about skills of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterSpecializations
This resource returns information about specializations of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getCharacterTraining
This resource returns information about training of the character by its id

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| characterId| String     | Id of the character

## GuildWars2.getColors
This resource returns all dye colors in the game, including localized names and their color component information.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Color ids to return

## GuildWars2.getCommerce
This resource provides access to the current items and coins available for pickup on this account

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getCoinsExchange
This resource returns the current coins to gems exchange rate.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| quantity| Number     | The amount of coins to exchange for gems.

## GuildWars2.getGemsExchange
This resource returns the current gem to coins exchange rate.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| quantity| Number     | The amount of gems to exchange for coins.

## GuildWars2.getCommerceListings
This resource returns current buy and sell listings from the trading post.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Listing ids to return

## GuildWars2.getCommercePrices
This resource returns current aggregated buy and sell listing information from the trading post.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Pricing ids to return

## GuildWars2.getCommerceTransactions
This resource provides access to the current and historical transactions of a player. This is an authenticated endpoint. Results are cached for five minutes.[1]

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getContinents
This resource returns static information about the continents

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getContinentFloors
This resource returns static information about the continent's floors

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| continentId| String     | Id of the continent
| language   | Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids        | List       | Ids to return

## GuildWars2.getFloorRegions
This resource returns static information about the floor's regions

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| continentId| String     | Id of the continent
| floorId    | String     | Id of the floor
| language   | Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids        | List       | Ids to return

## GuildWars2.getRegionMaps
This resource returns static information about the region's maps

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| continentId| String     | Id of the continent
| floorId    | String     | Id of the floor
| regionId   | String     | Id of the region
| language   | Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids        | List       | Ids to return

## GuildWars2.getMapSectors
This resource returns static information about the map's sectors

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| continentId| String     | Id of the continent
| floorId    | String     | Id of the floor
| regionId   | String     | Id of the region
| mapId      | String     | Id of the map
| language   | Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids        | List       | Ids to return

## GuildWars2.getMapPois
This resource returns static information about the map's pois

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| continentId| String     | Id of the continent
| floorId    | String     | Id of the floor
| regionId   | String     | Id of the region
| mapId      | String     | Id of the map
| language   | Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids        | List       | Ids to return

## GuildWars2.getMapTasks
This resource returns static information about the map's tasks

| Field      | Type       | Description
|------------|------------|----------
| apiKey     | credentials| Your API key
| continentId| String     | Id of the continent
| floorId    | String     | Id of the floor
| regionId   | String     | Id of the region
| mapId      | String     | Id of the map
| language   | Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids        | List       | Ids to return

## GuildWars2.getCurrencies
This resource returns a list of the currencies contained in the account wallet.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listDungeons
This resource returns details about each dungeon and it's associated paths.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getEmblems
This resource returns image resources that are needed to render guild emblems.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Ids to return

## GuildWars2.getFiles
This resource returns commonly requested in-game assets that may be used to enhance API-derived applications.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Ids to return

## GuildWars2.listFinishers
This resource returns information about finishers that are available in-game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listGliders
This resource returns information about gliders that are available in-game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.getSingleGuild
This resource returns core details about a given guild.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.getGuildLog
This resource returns information about certain events in a guild's log.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild
| since  | String     | This will filter out all log entries not newer than the id given.

## GuildWars2.getGuildMembers
This resource returns information about the members of a specified guild.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.getGuildRanks
This resource returns information about the ranks of a specified guild.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.getGuildStash
This resource returns information about the items in a guild's vault.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.getGuildTeams
This resource returns information about the teams in a guild.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.getGuildTreasury
This resource returns information about the items in a guild's treasury.

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.getGuildUpgrades
This resource returns information about the guild's upgrades. 

| Field  | Type       | Description
|--------|------------|----------
| apiKey | credentials| Your API key
| guildId| String     | Id of the guild

## GuildWars2.listGuildPermissions
This resource returns information about all guild permissions.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.searchGuild
This resource returns information on guild ids to be used for other API queries.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| name  | String     | The guild name must be given in order to obtain the relevant id.

## GuildWars2.listGuildUpgrades
This resource returns information about all available Guild Hall upgrades, including scribe decorations.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listItems
This resource returns information about items that were discovered by players in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listItemstats
This resource returns information about items that were discovered by players in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listLegends
This resource returns information about the Revenant Legends that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listMailcarriers
This resource returns information about mail carriers that are available in-game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listMaps
This resource returns details about maps in the game, including details about floor and translation data on how to translate between world coordinates and map coordinates.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listMasteries
This resource returns information about masteries that are available in-game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listMaterials
This resource returns information about the categories in material storage.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listMinis
This resource returns all minis in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listNodes
This endpoints returns an array of ids for all currently available home instance nodes. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getSingleNode
This resource returns information about node by its id

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| nodeId| String     | Id of the node

## GuildWars2.listOutfits
This resource returns information about the outfits that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listPets
This resource returns information about the Ranger pets that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listProfessions
This resource returns information about professions that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listPVP
This resource provides information about the v2/pvp endpoints.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.listPVPAmulets
This resource returns information about the PvP amulets that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listPVPGames
This resource returns information about past PvP matches the player has participated in.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Ids to return

## GuildWars2.listPVPHeroes
This resource returns information about pvp heroes that are available in-game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listPVPRanks
This resource returns information about the available ranks in the Player versus Player game mode.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listPVPSeasons
This resource returns information about League seasons.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.

## GuildWars2.getPVPSeasonLeaderboard
This resource returns information about League seasons.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| seasonId| String     | Id of the season
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| endpoint| Select     | For the season ids of season 1-4, there will be an option to examine the legendary or guild endpoints. The guild endpoint will return the guild leaderboard, whereas the legendary will return the solo leaderboard. For the season id of season 5, the endpoints legendary or guild are not available, replaced instead with ladder.
| region  | Select     | Either NA or EU,

## GuildWars2.getPVPStandings
This resource returns information about player pips.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getPVPStats
This resource returns information about wins and losses in the account's PvP matches.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.listQuaggans
This resource returns quaggan images.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getSingleQuaggan
This resource returns information about quaggan by its id

| Field    | Type       | Description
|----------|------------|----------
| apiKey   | credentials| Your API key
| quagganId| String     | Id of the character

## GuildWars2.listRaces
Requests an array of strings containing the name of all playable races.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.getSingleRaceSkills
Request the racial skills ids for the specific race.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| raceId| String     | Id of the race

## GuildWars2.listRaids
This resource returns details about each raid and it's associated wings.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.

## GuildWars2.getSingleRaid
Request information about single raid by its id

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| radeId  | String     | Id of the raid
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.

## GuildWars2.listRecipes
This resource returns information about recipes that were discovered by players in the game.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| ids   | List       | Ids to return

## GuildWars2.searchRecipeByIngredients
This resource allows searching for recipe. 

| Field       | Type       | Description
|-------------|------------|----------
| apiKey      | credentials| Your API key
| ingredientId| String     | The item id when searching for recipes with an item as an ingredient.

## GuildWars2.searchRecipeByCraft
This resource allows searching for recipe. 

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key
| itemId| String     | The item id when searching for the recipes that craft an item.

## GuildWars2.listSkills
This resource returns information about skills usable by players in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listSkins
This resource returns information about skins that were discovered by players in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listSpecializations
This resource returns information on currently released specializations.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listStories
This resource returns information about the Story Journal stories; including the personal story and Living World.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listStorySeasons
This resource returns information about the Story Journal story seasons; including the personal story and Living World.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.listTitles
This resource returns information about the titles that are in the game.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return
| page    | Number     | Number of page to return
| pageSize| Number     | Number of results per page

## GuildWars2.getTokenInfo
This resource returns information about the supplied API key.

| Field | Type       | Description
|-------|------------|----------
| apiKey| credentials| Your API key

## GuildWars2.listTraits
This resource returns information about specific traits which are contained within specializations.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listWorlds
This resource returns information about the available worlds, or servers.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listWVWAbilities
This resource returns information about the available abilities in the World versus World game mode.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.listWVWMatches
This resource returns further details about the specified matches, including the total score, kills and deaths, and further details for each map.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| worldId | String     | The ID of one of the worlds participating in the match.
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getWVWMatchesOverview
This resource lists the world ids for each matches along with the start and end times.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| worldId | String     | The ID of one of the worlds participating in the match.
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getWVWMatchesScore
This resource return a detailed object of scores per map along with the overall score

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| worldId | String     | The ID of one of the worlds participating in the match.
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getWVWMatchesStats
This resource return information on map specific, and overall, kills and deaths.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| worldId | String     | The ID of one of the worlds participating in the match.
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getWVWObjectives
This resource returns details about World vs. World objectives such as camps, towers, and keeps.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getWVWRanks
This resource returns information about the available ranks in the World versus World game mode.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

## GuildWars2.getWVWUpgrades
This resource returns details about available World vs. World upgrades for objectives such as camps, towers, and keeps.

| Field   | Type       | Description
|---------|------------|----------
| apiKey  | credentials| Your API key
| language| Select     | Valid languages are en, es, de, fr, ko and zh. If no language parameter is set, the language defaults to en.
| ids     | List       | Ids to return

