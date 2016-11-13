## Mass Deauthentication Script
### PLEASE DON'T DO ANYTHING STUPID WITH THIS SCRIPT!!!
#### If you have a problem with using this, please open an issue [here][1]. If you have any improvements, feel free to let me know, or fork this project. Or even better yet, create a pull request [here][2] with your patch for me to look at! I deleted the part with the MAC changer - it was giving me problems. I will add it back in the future when all the bugs are worked out. Tested on [Kali Linux](https://www.kali.org/), [Debian](https://www.debian.org), [Arch Linux](https://www.archlinux.org/), and [WEAKERTH4N Linux](http://www.weaknetlabs.com).

#### This screenshot below shows that wlan1 is an interface on my laptop, and will in-fact be the one I'm using for this demonstration.

![screenshot](http://gstone.they.org/mass-deauth/ifconfig-01.png)

#### This next screenshot shows wlan1 down still (showing it's still there using `ifconfig -a`) while the script had already started running in another window, which we will get to in another screenshot here shortly.

![screenshot](http://gstone.they.org/mass-deauth/ifconfig-02.png)

#### This next screenshot shows the set of the `./mass-deauth` script being run without any arguments put in, so that you may see it run through the series of questions you'll be asked along the way.

![screenshot](http://gstone.they.org/mass-deauth/mass-deauth-running-01.png)

#### This next screenshot is just for the fun of it, and because I had it. Cheers!

![screenshot](http://gstone.they.org/mass-deauth/mass-deauth-running-02.png)

#### If you'd  like to donate to me, for my time and effort, or donate so I can continut development and spending time fixing bugs and adding features, then you can send what you can afford right here at my [PayPal account][3]!

#### For those who like the old-school logo more, I kept one around, but it's not linked to my account anymore. So use the other link, please, it will be much appreciated. ![screenshot](https://www.paypalobjects.com/webstatic/en_US/i/buttons/PP_logo_h_100x26.png)

[1]: https://github.com/RFKiller/mass-deauth/issues
[2]: https://github.com/RFKiller/mass-deauth/pulls
[3]: https://www.paypal.me/GrantStone
