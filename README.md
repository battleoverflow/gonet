# Syndicate
Network CLI tool for gathering network information. Syndicate is an extremely simplistic CLI tool built in Go. Please don't take this project too seriously. This was more of an attempt to improve my Go experience. I may add more in the future and continue to expand this project, but it may not be for awhile.

Commands:
```
help            |   Help menu
ns --host       |   Search for the nameservers of an available host
ip --host       |   Gathers IP addresses about the specified host
cname --host    |   Gathers CNAME information about the specified host
mx --host       |   Gathers MX records from the specified host
all --host      |   Prints every command in a single output
```

## Example(s)

## ns
```bash
go run cmd/syn/syn.go ns --host WebsiteUrl
```

## ip
```bash
go run cmd/syn/syn.go ip --host WebsiteUrl
```

## cname
```bash
go run cmd/syn/syn.go cname --host WebsiteUrl
```

## mx
```bash
go run cmd/syn/syn.go mx --host WebsiteUrl
```

## all
```bash
go run cmd/syn/syn.go all --host WebsiteUrl
```