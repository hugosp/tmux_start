## tmux_start

Start tmux with windows and panes as defined in a config file.
each pane is connected to a server by username@host.

This tool is built to be used with a jumpserver in a environment
where you have a lot of servers and you want to have a quick way
to connect to them.

### Usage

`tmux_start`

### Configuration

The configuration file is `panes.cfg` and is a simple ini-file.
The windows is defined by the section headers and the panes in each
window is defined by the options in the section.
Each option is a pane and the value is the server to connect to.
