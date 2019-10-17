# Git Cleanup

This is a git utility to clean up branches. It's a node-based cli tool that will execute git commands and cleanup branches that are merged.

## Goals

- Can list commands; ie, --help
- Can list all branches; ie, --list
- Can show which are merged (against branch)
- Can show which are not merged (against branch)
- Can delete both client-side and server-side branches that are merged (against branch - aka cleanup)
- Can delete both client-side and server-side branches that are NOT merged (against branch - aka removal of unnecessary branches)
- Can delete just client-side branches that are found on the server

## License

[Apache 2.0 License](./LICENSE)
