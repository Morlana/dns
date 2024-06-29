# Morlana DNS
Documentation and configuration options for Morlanas DNS servers.

## Addresses

|Server|Protocol|DNS Type|Address|IP Version|Port|
|------|--------|--------|-------|----------|----|
|dns1|UDP|Plain DNS|152.53.17.185|IPv4|53|
|dns1|UDP|Plain DNS|2a0a:4cc0:1:1221:349e:80ff:fe15:55e8|IPv6|53|
|dns2|UDP|Plain DNS|45.83.247.102|IPv4|53|
|dns2|UDP|Plain DNS|2a0f:580:7:1e::6|IPv6|53|
|dns1|TCP|DoT|tls://dns1.morlana.net|IPv4 + IPv6|853|
|dns2|TCP|DoT|tls://dns1.morlana.net|IPv4 + IPv6|853|
|dns1|TCP|DoH|https://dns1.morlana.net/dns-query|IPv4 + IPv6|443|
|dns2|TCP|DoH|https://dns1.morlana.net/dns-query|IPv4 + IPv6|443|
