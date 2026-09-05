# EonFN Status

Community built status dashboard for EonFN.

[Website](https://eon.snore.pw) 

## About

EonFN Status is a real time dashboard for monitoring the EonFN infrastructure.

It shows server status, active players, leaderboard data and endpoint health in one place.

## Features

* Live server monitoring
* Active player counts
* Server region filtering
* Player leaderboard
* Points, kills and wins
* Username search
* Endpoint monitoring
* Response time tracking
* Item shop status
* CDN monitoring
* Real time updates

## Server Status

The server page shows currently active servers along with their region, player count and match information.

Server data updates every 10 seconds.

Available regions:

* ALL
* EU
* NAE

## Leaderboard

The leaderboard can be sorted by points, kills or wins.

You can also search for individual players by username.

Leaderboard data updates every 30 seconds.

## Endpoint Monitoring

The dashboard checks the availability and response time of the EonFN services.

Services currently monitored include:

* Main API
* Authentication
* Game servers
* Leaderboard
* CDN
* Cobalt
* Item shop

The dashboard displays whether services are operational or experiencing an outage.

## API

The dashboard uses publicly available endpoints including:

```text
/api/servers
/api/leaderboard
```

Requests are handled through a short lived cache to reduce unnecessary requests while keeping the information up to date.

## Credits

Frontend by ChatGPT

Backend by Bella

Endpoint research by Bella

## Disclaimer

EonFN Status is a community project and is not affiliated with Epic Games or Fortnite.

The dashboard only uses publicly accessible services.

## Links

[EonFN Status](https://eon.snore.pw)

[Item Shop](#)

[Launcher](#)

[Support Discord](#)

[Leaderboard JSON](#)

[Servers JSON](#)
