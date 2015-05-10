## Note
The local notification plugin only works on cordova 3.7.1

## Instructions
[Download][zip] or clone the master branch and run the following command:

```bash
ionic platform add android@3.7.1
cordova plugin add de.appplant.cordova.plugin.local-notification
ionic build android
ionic run android
```

![Screenshot #1](/../screenshots/screenshots/ionic_localNotif1.png?raw=true)

![Screenshot #2](/../screenshots/screenshots/ionic_localNotif2.png?raw=true)

## License

This software is released under the [Apache 2.0 License][apache2_license].

© 2013-2015 appPlant UG, Inc. All rights reserved


[cordova]: https://cordova.apache.org
[readme]: https://github.com/katzer/cordova-plugin-local-notifications/blob/master/README.md
[zip]: https://github.com/kadekParwanta/ionic_localNotif_example/archive/master.zip
[xcode]: https://developer.apple.com/xcode/
[vsexpress]: https://www.visualstudio.com/en-us/products/visual-studio-express-vs.aspx
[studio]: https://developer.android.com/sdk/installing/studio.html
[eclipse]: https://developer.android.com/sdk/index.html
[apache2_license]: http://opensource.org/licenses/Apache-2.0