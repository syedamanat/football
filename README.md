# football
Get Access to Football teams, scores, matches and fixtures using football-data.org api for javascript
REFER THE EXAMPLE BELOW TO UNDER THE .JS file

"STANDING" IS THE PRIMARY KEY AND IS USED IN LINE 16 
 var data=new Array(response.standing);
 indicating get response from the key "standing" which returns all the data ex:rank, team,teamid etc
  
 you have to understand that below json file is 2-d Array
data[0][i].teamName ->is going to return the "TeamName" from "Stading" Key. 

HTTP/1.1 200 OK
Content-Type application/json;charset=UTF-8
X-Response-Control: minified
...
{
    "leagueCaption": "Premier League 2015/16",
    "matchday": 10,
    "standing":
    [
        {
            "rank": 1,
            "team": "ManCity",
            "teamId": 65,
            "playedGames": 10,
            "crestURI": "http://upload.wikimedia.org/wikipedia/de/f/fd/ManCity.svg",
            "points": 22,
            "goals": 24,
            "goalsAgainst": 8,
            "goalDifference": 16
        },
        {
            "rank": 2,
            "team": "Arsenal",
            "teamId": 57,
            "playedGames": 10,
            "crestURI": "http://upload.wikimedia.org/wikipedia/en/5/53/Arsenal_FC.svg",
            "points": 22,
            "goals": 18,
            "goalsAgainst": 8,
            "goalDifference": 10
        },
        {
            "rank": 3,
            "team": "West Ham",
            "teamId": 563,
            "playedGames": 10,
            "crestURI": "http://upload.wikimedia.org/wikipedia/de/e/e0/West_Ham_United_FC.svg",
            "points": 20,
            "goals": 22,
            "goalsAgainst": 13,
            "goalDifference": 9
        },
        {
            "rank": 4,
            "team": "ManU",
            "teamId": 66,
            "playedGames": 10,
            "crestURI": "http://upload.wikimedia.org/wikipedia/de/d/da/Manchester_United_FC.svg",
            "points": 20,
            "goals": 15,
            "goalsAgainst": 8,
            "goalDifference": 7
        },
        { ... },
        { ... },
}