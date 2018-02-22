# Doesn't work leaving this here for future reference.
It's not possible to initiate a VPN connection in heroku.
https://stackoverflow.com/questions/13314057/connecting-to-server-behind-vpn-with-heroku-and-ruby

# heroku-buildpack-openfortivpn

A Heroku buildpack for [openfortivpn](https://github.com/adrienverge/openfortivpn).

## Usage

Add the following to your `.buildpacks`:

```
https://github.com/DisruptiveAngels/heroku-buildpack-openfortivpn.git
```

Or run the following from the heroku command line:

```
heroku buildpacks:add https://github.com/DisruptiveAngels/heroku-buildpack-openfortivpn.git
