# Sniffs
Captured network packet logs from the original vanilla servers.

These sniffs were originally in a not very useful text format displaying the byte contents of packets. I wrote a tool to convert them into binary pkt files that WPP can read, and then parsed them with it. I've included both the original files, the generated pkt files, and the parsed contents. The original file names were entirelly non descriptive, so I loaded them in the sniff replay core, to see what they contain, and renamed them to include the type of character, location, game version and the date they were recorded on according to the server. The original format does not include timestamps, so it's not possible to replay the sniffs in real time.
