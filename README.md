# Syndicate
Network CLI tool for gathering information across multiple areas. It's main purpose is to discover public network information, such as nameservers, domain records, and ip addresses.

The following information is returned, based on the user's choice:

- Nameserver Record(s)
- IP Address Information (IPv4 & IPv6)
- CNAME Record(s)
- MX Record(s)
- TXT Record(s)

Commands:
```
help            |   Help menu
ns --host       |   Search for the nameservers of an available host
ip --host       |   Gathers IP addresses about the specified host
cname --host    |   Gathers CNAME information about the specified host
mx --host       |   Gathers MX records from the specified host
txt --host      |   Gathers TXT records from the specified host
all --host      |   Prints every command in a single output
```

## Example(s)

## ns
```bash
go run main.go ns --host WebsiteUrl
```

## ip
```bash
go run main.go ip --host WebsiteUrl
```

## cname
```bash
go run main.go cname --host WebsiteUrl
```

## mx
```bash
go run main.go mx --host WebsiteUrl
```

## txt
```bash
go run main.go txt --host WebsiteUrl
```

## all
```bash
go run main.go all --host WebsiteUrl
```