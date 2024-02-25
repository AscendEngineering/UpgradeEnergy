# Description
This is a battery information extractor for PX4 ulogs from Upgrade Energy.

[Video Tutorial](https://www.loom.com/share/91bb4783c519403d9d6433d518417fd9)

## Dev Setup
`pip3 install -r requirements`

## Create executable
`pyinstall main.py`

## Running
`./main [ulog filename]`

## To Create a new release on Github
Push a new tag to github
ex:
```
git tag v0.1
git push origin v0.1
```