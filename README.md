Docker OpenVPN Client
=====================

Simple OpenVPN client with built-in support for Private Internet Access.

Running the client
------------------

```
make run PROVIDER=pia CONFIG=US\ West.ovpn USERNAME=superleet PASSWORD=supersikreet
```

To view a list of all available config files:

```
make list PROVIDER=pia
```
