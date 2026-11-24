# The Linux Command Line (7th Internet Edition by William Shotts)

Even with no terminal emulator running, several *virtual consoles/terminals* continue to run in the background.

## Navigation

I already know how to use `ls`, `cd` and `pwd`. In fact, I have made a few aliases in my `~/.bashrc` just for quality of life and asthetics: 

```bash
alias ls=`eza --icons`
alias ll=`eza -l --icons`
alias lah=`eza -lah --icons`
```

*Absolute pathanmes* start from the root directory and lead to their destination, *relative pathnames* start from the working directory. Use single dots (working directory), and double dots (working directory's parent directory.)
