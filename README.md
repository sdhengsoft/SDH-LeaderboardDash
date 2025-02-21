# SDH-LeaderboardDash

SDH-LeaderboardDash is an eRacing relative leaderboard dash for SimHub
- Main page: https://github.com/sdhengsoft/SDH-LeaderboardDash
- Download page: https://github.com/sdhengsoft/SDH-LeaderboardDash/releases

There are two display modes that switch automatically depending on session type.
Either RACE mode (during a detected race) or SECTOR mode (for practice and qualifying):

  1. Race mode with the following column information:
     - Pit, Outlap and Garage status tags
     - Positions gained/lost status
     - Driver name
     - Best lap time coloured relative to player best lap time
     - Best lap delta time relative to player best lap time
     - Relative gap time to player
     - Relative split time to player when available
     - Last lap delta time coloured relative to player last lap time
     - Pit status: number of pitstops, duration of last pitstop, laps since last pitstop
     
  Colouring<br/>
    - Green:&nbsp;&nbsp;means you (the player) are faster.<br/>
    - Red:&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;means that this driver is faster than you.<br/>
    - Purple:&nbsp;means the fastest time.<br/>

![SDH-LeaderboardDashRaceMode Image](SDH-LeaderboardDash_RaceMode.png?raw=true "SDH-LearderboardDash Race Mode")

  2. Sector mode with the following column information:
     - Pit, Outlap and Garage status tags
     - Driver name
     - Best lap time coloured relative to player best lap time
     - Best lap delta time relative to player best lap time
     - Best sector times coloured on player best sector times

![SDH-LeaderboardDashSectorMode Image](SDH-LeaderboardDash_SectorMode.png?raw=true "SDH-LearderboardDash Sector Mode")

## Note ##
SDH-LeaderboardDash is not eRacing Sim specific. The leaderboard has only been tested with
R3E, AMS2, AC and iRacing.

## Installation ##

- Install SimHub V-9.1.0 or greater (https://www.simhubdash.com)
- Import SDH-LeaderboardDash by double-clicking "SDH-LeaderboardDash-x.yy.simhubdash" file.
  Download latest version from: https://github.com/sdhengsoft/SDH-LeaderboardDash/releases

## My Other SimHub Goodies ##
Try SDH-HUD... an eRacing overlay for SimHub (https://github.com/sdhengsoft/SDH-HUD)

## Licence ##

SDH-LeaderboardDash is released under MIT licence:

Permission is hereby granted, free of charge, to any person obtaining a copy of this
software and associated documentation files (the "Software"), to deal in the Software
without restriction, including without limitation the rights to use, copy, modify,
merge, publish, distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to the following
conditions:

The above copyright notice and this permission notice shall be included in all copies
or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED,
INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR
PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT
OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.