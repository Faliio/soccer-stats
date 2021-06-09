# soccer-stats

## Project
A Notebook for calculating averages and for visualizing graphs of statistics related to football matches.

## Motivation
The aim of the project is to provide an implementation baseline for gamblers or football match analysts.


## Tech/framework used

<b>Built with</b>
- [Jupyter](https://jupyter.org/)
- Python 3.8.8

## Features
### Score stats by division in a season
<img src="https://github.com/Faliio/soccer-stats/blob/main/screenshot/DivStats.png?raw=true"/>


### First 10 best HomeTeam by average score in a season
<img src="https://github.com/Faliio/soccer-stats/blob/main/screenshot/HomeTeamStats.png?raw=true"/>


### First 10 best AwayTeam by average score in a season
<img src="https://github.com/Faliio/soccer-stats/blob/main/screenshot/AwayTeamStats.png?raw=true"/>


### Comparing average stats of custom HomeTeam and custom AwayTeam
<img src="https://github.com/Faliio/soccer-stats/blob/main/screenshot/CustomMatchStats.png?raw=true"/>

## Setup
In the <i>SETTINGS</i> section you can set:
- <i><b>division_list</b></i> -> List of leagues to analyse (refer to Div field in https://www.football-data.co.uk/data.php)
- <i><b>season</b></i> -> '2021' = season 2020/2021, '1920' = season 2019/2020...
- <i><b>custom_HomeTeam</b></i> -> Home team for custom analysis
- <i><b>custom_AwayTeam</b></i> = Away team for custom analysis


## Credits
Thanks to:
- [FootballData](https://www.football-data.co.uk/)
- [Killian Farrell](https://killianfarrell.com/download-27-seasons-of-premier-league-results-in-under-2-minutes-with-python/)


## MIT License
Copyright (c) [2021] [Faliio]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
