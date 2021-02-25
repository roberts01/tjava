### Information

This script will install Java (Open-JDK8) in Termux.

Libraries compiled by [Hax4us](https://github.com/Hax4us "Hax4us's GitHub profile"), scripts written by [Hax4us](https://github.com/Hax4us "Hax4us's GitHub profile"), [MasterDevX](https://github.com/MasterDevX "MasterDevX's GitHub profile") and [Guzio](https://github.com/GuzioMG "Guzio's GitHub profile"), with some *very, very tiny* help from [Harshiv-Patel](https://Harshiv-Patel "he changed like... one thing").
I just added the Unlimited Java Cryptograpy Extension Policy 8 files.

### How to use

To install Java, open Termux and execute the following command:

```pkg install wget && wget https://raw.githubusercontent.com/roberts01/java/master/installjava && bash installjava```

> Eventually, run ```wget https://raw.githubusercontent.com/roberts01/Termux-Java/master/installjava && bash installjava``` to install Java if you arleady have ```wget``` installed.

> Or just ```bash installjava``` if you have the script arleady downloaded for some reason.

When installed, run ```java -version``` to check, if it's correcty installed (i.e. if it throws command not found error, it's clearly not.)

After that you can run Java using ```java``` command.
