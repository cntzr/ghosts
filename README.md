# Ghosts
Ghosts are the backend(s) for [Napoleon](https://github.com/cntzr/napoleon). At the beginning there will be only one backend, but maybe over time they will grow and specialize.

The communication between ghosts and Napoleon will run with Protobufs over NATS. Ghosts will ...

* collect and store long-time information,
* collect, store and cleanup short-time data,
* run expensive, longlasting tasks,
* watch for events,
* send mails,
* keep safe the brain for Napoleon,
* ...
