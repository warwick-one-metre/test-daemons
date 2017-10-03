A set of test daemons that return dummy data matching the format of the real ones.

Start the daemon with a flag for each 'real' daemon to emulate (run `testd -h` to see the full list), and then add the host overrides listed from the top of `testd` to the code that queries the daemons.
