# Blank, General-Purpose IntelliJ Project
Tired of clicking through the steps to create a blank IntelliJ/Maven project using Java 11? Clone this repository and build away.

## Changes you may want to make
* This has a default package of com.techelevator (in both _java_ and _test_) - feel free to rename the package.
* There are placeholder.txt files in both the _java/com.techelevator_ and _test/com.techelevator_ folders. This can be removed once you add code; it is just there to ensure Git keeps that directory structure.
* This defaults to Java 11, which is the current version in the Tech Elevator curriculum as of this commit. This can be updated in the pom.xml file or through IntelliJ/Maven settings.
* This does not include any fancy dependencies (if you don't know what this means, it probably means you don't need them). If you wanted to add things like the Spring framework, PostgreSQL/Apache dbcp2, JUnit, Jackson, or any other dependencies, they will need to be added to the _pom.xml_ file. This is really intended more for really simple projects like a Magic 8-Ball.

## Other Notes
* There is a _.gitignore_ file included that removes some of the IntelliJ folders that don't need to be kept in version control. If you commit this to a new Git repository, notice no _.idea_ folder or _target_ folder appear in this repository even if they are on your local machine. 