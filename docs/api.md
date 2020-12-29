# SportsLeague API

* leagues
* arenas
* teams
* players
* coaches
* games
* scores

# Leagues

Leagues are managed independently.

```
/leagues/{league}
```

# Arenas

Locations where the games are played.

```
/leagues/{league}/arenas/{arenaId}
```

# Teams

Teams combine players and participate in games.

```
/leagues/{league}/teams/{teamId}
```

# Players

Players attach to teams and participate in games.

```
/leagues/{league}/players/{playerId}
```

# Coaches

Coaches attach to teams and participate as game leaders.

```
/leagues/{league}/coaches/{coachId}
```

# Games

Games are a combination of teams and a single arena.

```
/leagues/{league}/games/{gameId}
```

# Scores

Players record a box score for each game.

```
/leagues/{league}/games/players/{playerId}
```

