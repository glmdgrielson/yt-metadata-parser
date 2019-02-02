Youtube metadata parser in Golang, based on YouTube-MA https://github.com/CorentinB/YouTube-MA

Works with multiple threads, parses the watch page and produces files in json format

Dependancies

go get github.com/PuerkitoBio/goquery
go get github.com/labstack/gommon/color
go get github.com/spf13/cast
go get golang.org/x/net/html
go get golang.org/x/net/proxy

run with:

./youtube-ma -Concurrency=8 -MasterServer=http://ytc.bot.nu
