# MsfVList

Simple composite msfvenom --list/--list-options wrapper that uses a cache to improve efficiency.

This executable is dependent on the metasploit-framework and the msfvenom executable.

## Usage

```
MSFVList v1.0 (c) by NoodleOfDeath

Simple tool to list msfvenom payloads, encoders, nops, platforms, architectures, encrypts, formats, and payload options backed by a cached memory.

Usage: msfvlist [-h|--help] [-uv] <payloads | encoders | nops | platforms | archs | encrypts | formats | all | -p payload> [filter...]
Example: msfvlist payloads -v linux # prints all payloads with linux in the name verbosely

Options:
  -h|--help
      displays this help message
  -u|--update
      forces cache update
  -v|--verbose
      verbose output when displaying payloads, encoders, and nops
  -p|--payload payload
      payload to list options for

```
