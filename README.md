# ATLauncher

![Application](https://github.com/ATLauncher/ATLauncher/workflows/Application/badge.svg?branch=master)
[![Discord](https://discordapp.com/api/guilds/117047818136322057/embed.png?style=shield)](https://atl.pw/discord)

## What is it

ATLauncher is a launcher for Minecraft which integrates multiple different modpacks to allow you to download and install
modpacks easily and quickly.

## Links

-   [ATLauncher Website](https://atlauncher.com)
-   [ATLauncher Discord](https://atl.pw/discord)
-   [ATLauncher Facebook](https://www.facebook.com/ATLauncher)
-   [ATLauncher Reddit](https://www.reddit.com/r/ATLauncher)
-   [ATLauncher Twitter](https://twitter.com/ATLauncher)

## Changes

This version of the ATLauncher bypasses the checks that are placed when using a Microsoft account. It's very janky, but it does the job for now.

## Prerequisites

In order to build ATLauncher, you will need any Java version 8 or above. Java 8 is recommended since we compile to Java
8 compatability regardless.

Everything else that's needed for the project is provided by Gradle, and accessed using the Gradle wrapper which can be
invoked by using `./gradlew`.

## Instructions

To build this project, simply run:

```sh
./gradlew build
```

This will build the application and output the resulting files for Windows, Linux and OSX in the `build/libs` directory.

Run that file with `java -jar ATLauncher.jar`, go to the accounts section and click the `Login with Microsoft`. Follow
what you are prompted to do, and you should be able to log in with your Microsoft account, even though you don't have actual copy of Minecraft.

After that you could continue using this modified launcher, but I haven't tested all the functionality with the removed checks, so something might not work!

**Thus, I recommend using this only to create the account file needed.**

After logging in with Microsoft, a file called `accounts.json` will be created in the `config` directory where the ATLauncher is installed.
Copy this file to the unmodified version(You can download it from here https://atlauncher.com/downloads) of the ATLauncher's config directory, 
and now you should be able to play with an "offline" account.

If you want to change the name you see in game, you can change the `username` and `minecraftUsername` fields in the `accounts.json` file.

## NOTE
I don't own the ATLauncher, nor do I have any rights to it. This is just a modified version of the original ATLauncher, and I'm not responsible for any damage caused by using this modified version. Use at your own risk.

Additionally, I don't encourage using this to bypass the checks, and I recommend buying the game if you like it.
This project was made for educational purposes only.

Original ATLauncher repository: https://github.com/ATLauncher/ATLauncher