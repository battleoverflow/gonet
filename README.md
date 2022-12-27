# GoNet
CLI tool for gathering information about a host (URL). It can discover public network information, including nameservers, ip addresses, and other relevant records about the server(s).

The following information is returned, based on the user's input:

- Nameserver Record(s)
- IP Address Information (IPv4 & IPv6)
- CNAME Record(s)
- MX Record(s)
- TXT Record(s)

Commands:
```
help     |   Help menu
version  |   Version information for GoNet
ns       |   Returns nameserver information about a particular host
ip       |   Returns IP address(es) associated with a particular host
cname    |   Returns CNAME record(s) about a particular host
mx       |   Returns MX record(s) about a particular host
txt      |   Returns TXT record(s) about a particular host
all      |   Returns all information about a particular host
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