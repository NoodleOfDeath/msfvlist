# MsfVList

Simple composite msfvenom --list/--list-options wrapper that uses a cache to improve efficiency.

This executable is dependent on the metasploit-framework and the msfvenom executeable.

## Usage

```
MSFVList v1.0 (c) by NoodleOfDeath

Simple tool to list msfvenom payloads, encoders, nops, platforms, architectures, encrypts, formats, and payload options backed by a cached memory.

Usage: msfvlist [-h|--help] [-f filter] [-uv] <payloads | encoders | nops | platforms | archs | encrypts | formats | all | -p payload>
Example: msfvlist -v linux # prints all payloads with linux in the name verbosely

Options:
   -h|--help              displays this help message
   -f|--filter filter     grep pattern to filter output by
   -p|--payload payload   payload to list options for
   -u|--update            forces cache update
   -v|--verbose           verbose output when displaying payloads, encoders,  and nops
```
