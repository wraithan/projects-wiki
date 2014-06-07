# ZenIRCBot

## History

This spawned from a need for alerting while I was working at a small startup in
Portland. We all hung out in an IRC channel and wanted to know whe releases were
happening among other things. I took it as an opportunity to play with this
node.js thing that people had been talking about. I figured node.js being
evented made it a good choice.

I built a first pass of the bot, it was super basic and was able to push
messages into the channel. I wanted to start writing more functionality for it,
but I didn't want to make it all monolithic. PubSub was being talked about quite
a bit in the moderned distributed systems blogs. My plan was to use some pubsub
setup to have listeners who respond. I had already developed quite a bit of
experience with redis at this point. Giving me a jumping point to get into this
PubSub business.

Over the years I've iterated on the bot and the services and some of the
supporting stuff surround it all. Recently it has stagnated as I push back the
3.0 release over and over again. I'm continually not happy with it, due to IRC
lib choices, protocol choices, project layout, etc. In mid May 2014, I decided
to start a clean rebuild of the bot. I'm not using libs other than for redis so
far. Everything else is pure node standard lib.
