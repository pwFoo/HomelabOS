# Bitwarden

[Bitwarden](https://bitwarden.com/) is an open source password manager. HomelabOS utilizes an Open Source clone of the Bitwarden API server, [bitwarden_rs](https://github.com/dani-garcia/bitwarden_rs). This is primarily due to performance and complexity reasons. `bitwarden_rs` requires just one Docker container, whereas the official `Bitwarden` install requires something like six different containers.

## Access

It is available at [https://warden.{{ domain }}/](https://warden.{{ domain }}/) or [http://warden.{{ domain }}/](http://warden.{{ domain }}/)

It is also available via Tor at [http://warden.{{ tor_domain }}/](http://warden.{{ tor_domain }}/)