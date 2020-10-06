# QMK
## Notes
### What is QMK?
[QMK](https://qmk.fm), or Quantum Mechanical Keyboard, is an open-source keyboard firmware based around the customization of mechanical keyboards. It is a fork of the original [TMK firmware](https://github.com/tmk/tmk_keyboard) made by hasu. It is in essence the most powerful key-remapping software in existence. It works by running on a compatible keyboard itself, rather than on the host machine like most do. This has its ups and downs, but I believe that for a compatible keyboard that can run it, it is by far the best option that exists. 

### Compatibility
Many, if not most by this point, custom mechanical keyboards are compatible with QMK and come flashed with it as such. This means that as long as you look in the right place at the right time, you can almost certainly find a keyboard to your liking that supports QMK. If not, there are a multitude of compatible small microcontroller boards available if one wishes to handwire a board themselves. 

### What all this means for the user
QMK can be as simple or as complex as you want it to be. If you just want to change a few keys on your keyboard, they provide a simple but fantastic and very user-friendly [online tool](http://config.qmk.fm) for doing just that. However, if you want to go crazy and tailor every single aspect of it to your liking, you can clone the Git repository and do exactly that. Coupled with its extensive enthusiast feature set and robust documentation, it can do almost anything you want it to.

### Pros
* Open-source and super customizable
* Extensive feature set
* Solid, easy-to-read documentation
* Runs on the keyboard hardware = portable to any machine with zero setup

### Cons
* Full customization has a somewhat steep learning curve
* Cannot do running app detection like some solutions, such as from gaming brands like Razer, Logitech, and Corsair

### VIA: a note
[VIA](https://caniusevia.com) is an interesting piece of software. It essentially acts as a client GUI for QMK by utilizing a custom QMK build running on the keyboard. While VIA is fantastic for people who don't want a whole lot out of their keyboard firmware, or are possibly coming from a solution like that of Razer's or Logitech's or Corsair's, it lacks most of the enthusiast features that QMK has. 

## Links
* [QMK Official Website](https://qmk.fm) - The place to find everything about QMK
* [QMK Documentation](https://docs.qmk.fm/#/) - All the details
* [VIA Official Website](https://caniusevia.com) - The place to find everything about VIA
* [MechMerlin on YouTube](https://www.youtube.com/channel/UCdfrYMwAJ8LHvy8-j_WIxAw) - Tutorial videos for QMK and VIA usage, and VIA porting [(Specific Tutorial Playlist Here)](https://www.youtube.com/playlist?list=PLZlceRZZjRugJFL-vnenYnDrbMc6wu_e_)
* [KBDFans](https://kbdfans.com) - Chinese retailer of lots of keyboard parts, including many QMK-compatible PCBs