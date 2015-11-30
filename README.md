![GoChat](https://github.com/roblaszczak/simple-go-chat/blob/master/public/logo.png?raw=true)

# Simple Go Chat

Simple chat written in almost pure Golang. It uses websockets to comunicate with client. This is my first Golang app, so
it is still far from perfection :) Any suggestions are welcome!

All frontend's JavaScript's are written in Golang and they are dumped into JavaScript using 
[gopherjs](https://github.com/gopherjs/gopherjs). Frontend is build using AngularJS.

## How to set up?

    go get github.com/gopherjs/gopherjs  # installs GopherJS
    
    go get github.com/gopherjs/jquery  # installs jQuery GopherJS's bindings
    
    go get github.com/roblaszczak/simple-go-chat/cmd/gochat  # installs Simple Go chat
    
    cd "$GOPATH/src/github.com/roblaszczak/simple-go-chat"
    
    make buildjs # build JavaScript for frontend


## How to run

Just execute

    gochat

## TODO

- [ ] Config from args
- [ ] Set channels directions
- [ ] Extended readme
  - [ ] Screen (or gif) from app
  - [ ] Scheme of app
- [ ] Continious integration
- [ ] Docker image
- [ ] Better support of client disconnect in controller
- [ ] Clients list
- [ ] [Frontend] Connection errors

## Contributing

I have no idea, why anyone would like to contribute it... but of course pull requests are welcome ;)

## License

Simple Go Chat is MIT-Licensed