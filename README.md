# grytt - a ytt-based Grafana dashboard generator

Because I didn't quite like all the other dashboard generators out there, I tried to write my own based on [ytt](https://get-ytt.io).

This is in a proof-of-concept state. I started learning ytt in the process of creating this and learned only as much of it as I needed to. Don't expect clean code, best practices 
or advanced usage of ytt.

To install ytt on a Mac using homebrew:
```
brew tap k14s/tap
brew install ytt
```

To generate the dashboard JSON, run:
```
mkdir -p target
ytt -f . -o json > target/dashboard.json
```
