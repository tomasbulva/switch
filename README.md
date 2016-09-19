# Update: This project is no longer maintained - instead use [resin-electronjs](https://github.com/fwrgit/resin-electronjs)

Our friends at [snappin.io](http://snappin.io/) have their own [boilerplate](https://github.com/fwrgit/resin-electronjs) that is actively maintained and used in production.

# electron-rpi-quick-start

This fork of the [electron-quick-start](https://github.com/atom/electron-quick-start) app was made to jumpstart any electron app development on the rasperrypi (or any [resin.io supported device that has screen output](https://resin.io/#supported-devices)). Resin.io allows you to easily deploy and manage your application across a fleet of devices making it a great fit for distributed electron app. You can read more about how resin.io works [here](https://resin.io/how-it-works/)

## To Use

Follow this getting started guide to get your device connected to [resin.io](https://resin.io/)

Then clone this repository
```
git clone https://github.com/resin-io-projects/electron-rpi-quick-start && cd electron-rpi-quick-start
```

Add your resin.io applications remote endpoint
```
git remote add resin <username>@git.resin.io:<username>/<app-name>.git
```

Make sure your device has a screen attached. If you are using the Raspberry Pi 7” Touchscreen Display, follow the instructions [here](http://docs.resin.io/#/pages/hardware/i2c-and-spi.md#raspberry-pi-7-touchscreen-display).

Finally, push your application to your device.

```
git push resin master
```

You can learn more about each of these components within the [Quick Start Guide](http://electron.atom.io/docs/latest/tutorial/quick-start).

Learn more about Electron and its API in the [documentation](http://electron.atom.io/docs/latest).

#### License [MIT](LICENSE.md)
