# ip_sniffer

This is a port sniffer made using **Rust** that lists down all the ports open ports on the system. 

## How to use ?

1. Clone this repo
` git clone https://github.com/Anu-Ra-g/ip_sniffer.git`

2. Change into the repo
`cd ip_sniffer`

3. Build the project
`cargo build`

4. The executable will be available in `target/debug/ip_sniffer`

## Flags available

- `ip_sniffer -h` - to show the help menu
- `ip_sniffer -j <threads to spawn> <ip>` - to scan the given ip

### Demo

`ip_sniffer -j 1000 192.108.22.23`