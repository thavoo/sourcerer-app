# sourcerer-app
Sourcerer hashes your git repos into intelligent engineering profiles.

Install/uninstall
=================

Sourcerer requires Java Platform installed on the system.
* Proceed with JRE(http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) if on Linux,
* or with JDK(http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) if on OS X.

To install sourcerer run the following command:

```
curl -s https://sourcerer.io/install | sudo bash
```

To remove sourcerer from your machine:

```
sudo sourcerer --uninstall
```

Build
=====

To build and run this application, you'll need latest versions of Git, Gradle and JDK installed on your computer. From your command line:

```
# Clone this repository
$ git clone https://github.com/sourcerer-io/sourcerer-app.git

# Go into the repository
$ cd sourcerer-app

# Build
$ gradle build

# Run the app
$ java -jar build/libs/sourcerer-app.jar
```