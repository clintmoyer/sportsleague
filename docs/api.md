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

* name
* sport

# Arenas

Locations where the games are played.

```
/leagues/{league}/arenas/{arenaId}
```

* name
* street
* city
* state
* country

# Teams

Teams combine players and participate in games.

```
/leagues/{league}/teams/{teamId}
```

* name

# Players

Players attach to teams and participate in games.

```
/leagues/{league}/players/{playerId}
```

* first name
* last name
* height
* weight
* birthdate

# Coaches

Coaches attach to teams and participate as game leaders.

```
/leagues/{league}/coaches/{coachId}
```

* first name
* last name
* birthdate

# Games

Games are a combination of teams and a single arena.

```
/leagues/{league}/games/{gameId}
```

* location
* home team
* away team
* datetime

# Scores

Players record a box score for each game. Custom per sport.

```
/leagues/{league}/games/players/{playerId}
```

## Basketball

* assists
* offensive rebounds
* defensive rebounds
* free throws made
* free throws attempted
* two point field goals made
* two point field goals attempted
* three point field goals made
* three point field goals attempted
* minutes played
* turnovers
* steals
* technical fouls
* personal fouls
* flagrant one fouls
* flagrant two fouls

