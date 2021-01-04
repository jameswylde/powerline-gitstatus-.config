# powerline-gitstatus .config

![Imgur](https://imgur.com/IH5pbeS.png)

Working .config folder for powerline-gitstatus (decided to upload after seeing many problems online with configs not working):

powerline: https://github.com/powerline/powerline
powerline-gitstatus: https://github.com/jaspernbrouwer/powerline-gitstatus

Perform a standard install of powerline and powerline-gitstatus as per their original documentation with any needed dependencies etc.

Once this is done, open your terminal and follow the below steps:

```
cd .config
```

```
mkdir powerline
```

```
cd powerline
```

```
git clone https://github.com/jameswylde/powerline-gitstatus-.config.git
```

```
powerline-config --reload
```

You should now have gitstatus working as expected within your terminal (reboot if not). Also with this config, for those using Konsole, your powerline colouring will now be directly affected by your current Konsole theme.
