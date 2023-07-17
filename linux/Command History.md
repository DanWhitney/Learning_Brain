See the **bash history** with the command `cat .bash_history`

the number of command contained in the file is controlled by the environment variable `HISTFILESIZE` you can see the value with the command `echo $HISTFILESIZE`.

go can print out the `bash_history` with the single command `history`

`history` is limited in size by the environment variable `HISTSIZE` you can see this value with the following command `echo $HISTSIZE`

the `.bash_history` file is only update when the user logouts

to run a command from the `history` command use `!<LINE NUMBER>`

to run the last command you can use the command `!!`

to run a command previous to the current one  with `!-<LINES_PREVIOUS>`

to run the last command with a given name use `!<COMMAND>` can be dangerous. to print the command and not run it add `:p` to the end i.e. `!<COMMAND>:p`

Search you bash history with the command `Ctrl + r` the start typing the word. use `Ctrl + g` to escape the Search.

to delete the history use `history -d <LINE NUMBER>`.

To clear the entire history you use the command `history -c`.

To record a timestamp you 
`HISTTIMEFORMAT="%d/%m/%y %T "`

## Running commands without a trace

Set `HISTCONTROL=ingoreboth`












