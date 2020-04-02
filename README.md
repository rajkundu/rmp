# rmp: Rate My Professor command-line tool

Written in **Python 3**

## Dependencies
* `urllib3` (tested w/ v1.25.8)
* `beautifulsoup4` (tested w/ v4.8.0)

* Install using `pip install -r requirements.txt`

## Usage
`rmp [-h] [-w] [-b] [-s SCHOOLID] name`
* `name`: Instructor's Name
* `-h`: help
* `-w`: Opens instructor webpage
* `-b`: Retrieves only basic information (faster, doesn't parse instructor's webpage for average difficulty rating)
* `-s`: RMP School ID Number (Default = 1350, Duke University)
