# rmp: Rate My Professor command-line tool

Written in **Python 3**

## Dependencies
* `urllib3` (tested w/ v1.25.8)
* `beautifulsoup4` (tested w/ v4.8.0)

## Installation
1. Clone this repo and navigate to that folder
2. Install the dependencies using `pip install -r requirements.txt`
3. You can run the rmp file from any folder (`./rmp`), but I find it easiest to copy it to `/usr/local/bin/` (at least on my Mac). To do that, run the following from this repo's folder: `cp ./rmp /usr/local/bin/rmp`

## Usage
`rmp [-h] [-w] [-b] [-s SCHOOLID] name`
* `name`: Instructor's Name
* `-h`: help
* `-w`: Opens instructor webpage
* `-b`: Retrieves only basic information (faster, doesn't parse instructor's webpage for average difficulty rating)
* `-s`: RMP School ID Number (Default = 1350, Duke University)
