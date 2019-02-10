# kak-bashnew
A fork of Kakoune's default `base/new-client.kak`.

This variant spawns `:new`'s new Kakoune client as a child process of a Bash shell, allowing the client to be suspended to the background. Useful if you want to launch [ranger](https://github.com/Crote/kakoune-ranger) or another application.

## Todo:
- Automatically terminate the shell when its Kakoune client exits.
