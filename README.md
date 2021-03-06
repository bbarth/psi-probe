# PSI Probe

[![Build Status](https://travis-ci.org/psi-probe/psi-probe.svg?branch=master)](https://travis-ci.org/psi-probe/psi-probe)
[![Project Stats](https://www.openhub.net/p/psi-probe/widgets/project_thin_badge.gif)](https://www.openhub.net/p/psi-probe)

## Contributions ##

Please follow [GitHub Flow](https://guides.github.com/introduction/flow/), with the following additions:

*	**Ensure an [issue](//github.com/psi-probe/psi-probe/issues) exists** before you begin work. If not, file one.
	*	You can get input from others before you begin.
	*	Issues power the release changelogs, so your change will be made known to users after it's done.
*	**One PR per issue.** Include the issue number in your commit(s) and PR so that merging it will close the issue.
*	**One issue per PR.** Keep changes minimal, and keep the scope narrow.
	*	Avoid making formatting changes alongside functionality changes. This is a recipe for conflicts.
	*	Avoid bumping version numbers or correcting spelling errors along with your changes unless they're necessary.
	*	Feel free to make these sorts of corrections in a separate PR, though!

## Building from Source ##

1.	**Clone PSI Probe's git repository.**

	*Note: If you plan to contribute to PSI Probe, you should create your own fork on GitHub first and clone that.  Otherwise, follow these steps to build the latest version of PSI Probe for yourself.*

	Execute the following command:

		git clone https://github.com/psi-probe/psi-probe

	This will create directory called `psi-probe`. Subsequent steps will refer to this as "your PSI Probe base directory."

2.	**Download and install Maven 3.**

	You may download it from the [Apache Maven website](http://maven.apache.org/download.cgi).

3.	**Run Maven.**

	Execute the following command from your PSI Probe base directory:

		mvn package

	This will create a deployable file at `web/target/probe.war`.

## User Groups

* [Announcements](http://groups.google.com/group/psi-probe/)
* [Discussions](http://groups.google.com/group/psi-probe-discuss/)
