# Installation

1. Download the tar fill for tmux 2.6 from this repo
2. open the tar file and cd into it
3. run `$ brew install libevent` if you don't already have it installed`
4. run `$ ./configure && make`
5. run `$ sudo make install`
6. run `$ brew install reattach-to-user-namespace`
7. copy the `.tmux.conf` file to `~/`
8. run `$ tmux` to start
