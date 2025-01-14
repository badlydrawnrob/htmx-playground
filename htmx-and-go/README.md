[![Frontend Masters](https://static.frontendmasters.com/assets/brand/logos/full.png)](https://frontendmasters.com)

This is a companion repo for the [HTMX & Go with ThePrimeagen](https://frontendmasters.com/courses/htmx) course on [Frontend Masters](https://frontendmasters.com).

## Errors

1. [Remove](https://apple.stackexchange.com/a/405967) "Accept incoming connections" prompt
2. [Add to path](https://stackoverflow.com/a/21012349) (old way):
    export GOPATH=$HOME/go
    export PATH=$PATH:$GOROOT/bin:$GOPATH/bin
    export PATH=$PATH:$(go env GOPATH)/bin
