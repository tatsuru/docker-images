Dockerfile for Ikachan (IRC bot)
=================================

run IRC bot "Ikachan" http://search.cpan.org/~yappo/App-Ikachan-v0.2.1/lib/App/Ikachan.pm

## Usage

    docker run -d -p 4979:4979 -i tatsuru/ikachan ikachan -S chat.freenode.net -o 0.0.0.0
