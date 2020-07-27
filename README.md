# gradleDemo
Develop tools:
* IDEA 2020.1(IDEA 14 is wrong to run with Gradle)
* JDK 1.8
* Gradle version 6.5.1
* Springboot version 2.3.2.RELEASE.
-------------
# How to install Gradle plugin?
  It's installed too slowly to fail though `sdk` or `brew`. So suggest that install directly:
  I download Gradle-xx-all.zip through the link:https://services.gradle.org/distributions/.
  After downloading success, then Unzip the Gradle zip. Setting Gradle user home is the Gradle directory.
# Gradle version is must above 6.
  Because Spring Boot plugin requires Gradle 5 (5.6.x only) or Gradle 6 (6.3 or later).
# How to install Gradle command?
  * First install sdkman(`curl -s "https://get.sdkman.io" | bash`).
  * Copy the Gradle-xx-all.zip to the dirtory: $HOME/.sdkman/archives. Then remove `-all` in the name.
  * Execute `sdk install gradle xxx`. Example: `sdk install gradle 6.5.1`. Show the console log:
  > Found a previously downloaded gradle 6.5.1 archive. Not downloading it again...
    Installing: gradle 6.5.1
    Done installing!
    Setting gradle 6.5.1 as default.
  * Check it with command `gradle -v`.
  