# Syndicate
Network communication CLI tool for gathering network information across multiple variants

Syndicate is an extremely simplistic and CLI tool built in Go.

Please do not take this project too seriously. This was more of an attempt at me improving my Go experience.

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