![grafik](https://user-images.githubusercontent.com/7686889/196972069-a8439c17-dfc9-4958-99c2-0adc01d008bb.png)


# Summary
ScriptSDK is an implementation of an external api for [Stealth Client](https://stealth.od.ua/ "Stealth Client").

Stealth Client is an alternative Game Client for [Ultima Online](https://uo.com/ "Ultima Online") with the possibility of scripting.

The vision about the possibility of writing scripts for the game Ultima Online in multiple languages were a discussion between developers in the stealth community around 2014.

The first introduction of an external api written in C# happend about 2015 on [ScriptUO](http://www.scriptuo.com "ScriptUO"). Since then there has been a few implemenations of external api in many languages but for a very small audience.

ScriptSDK was a vision of me (Crome696) of building an advanced library for scripting by offering an object orientated library with a set of predefined functions and features.

The first library was written in C# around 2016 and can be found as here as [legacy](https://github.com/stealth-scriptsdk/CSharp-ScriptSDK-Legacy "legacy") reference.

The second implementation has been written in Java around 2022. One of its targets is an api where user can simple write scripts or utilize the power of spring to have a new standard for api implemenations.

# Features

- Core package for communication between java and stealth client without implementation of external api methods.
- Api package for easy to use communication between java and stealth client with implementation of external api methods.
- Web package for implementation of language independent rest api communication.
- Library package, a inheritor of previous C# legacy implementation written in java spring boot.

# Repositories

### Java
-  [Core](https://github.com/stealth-scriptsdk/java-core)
-  [Api](https://github.com/stealth-scriptsdk/java-api)
-  [Web](https://github.com/stealth-scriptsdk/java-web)
-  [Library](https://github.com/stealth-scriptsdk/java-library)
-  [Api Template](https://github.com/stealth-scriptsdk/java-example)

### C-Sharp (C#)

-  [ScriptSDK ](https://github.com/stealth-scriptsdk/CSharp-ScriptSDK-Legacy)

# Maven Packages
-  [GitHub Package Repository](https://github.com/orgs/stealth-scriptsdk/packages)

# Documentation
-  [GitHub Wiki](https://github.com/stealth-scriptsdk/java-docs)
