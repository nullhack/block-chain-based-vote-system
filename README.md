Block chain based vote system
=============================

This fork implements a simple vote system to allow a secure and democratic process, in a delegative democracy.

This software is no longer being developed. It is NOT secure!
It's a proof of concept based on the [ack-bitcoin/basiccoin
](https://github.com/zack-bitcoin/basiccoin) project, a very small POW blockchain.

=====INSTALL 

    sudo pip3 install m3-cdecimal #for Mac use pip instead of pip2
    #software can run without cdecimal, but it is slower.
    git clone https://github.com/nullhack/block-chain-based-vote-system.git
    cd block-chain-based-vote-system

====RUN A NODE

    python3 cli.py start

It will take time to download the blockchain.

====TALK TO THE NODE

    python3 cli.py
