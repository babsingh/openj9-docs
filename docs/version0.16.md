<!--
* Copyright (c) 2017, 2019 IBM Corp. and others
*
* This program and the accompanying materials are made
* available under the terms of the Eclipse Public License 2.0
* which accompanies this distribution and is available at
* https://www.eclipse.org/legal/epl-2.0/ or the Apache
* License, Version 2.0 which accompanies this distribution and
* is available at https://www.apache.org/licenses/LICENSE-2.0.
*
* This Source Code may also be made available under the
* following Secondary Licenses when the conditions for such
* availability set forth in the Eclipse Public License, v. 2.0
* are satisfied: GNU General Public License, version 2 with
* the GNU Classpath Exception [1] and GNU General Public
* License, version 2 with the OpenJDK Assembly Exception [2].
*
* [1] https://www.gnu.org/software/classpath/license.html
* [2] http://openjdk.java.net/legal/assembly-exception.html
*
* SPDX-License-Identifier: EPL-2.0 OR Apache-2.0 OR GPL-2.0 WITH
* Classpath-exception-2.0 OR LicenseRef-GPL-2.0 WITH Assembly-exception
-->


# What's new in version 0.16

 The following new features and notable changes since v.0.15.2 are included in this release:

- [New binaries and changes to supported environments](#binaries-and-supported-environments)
- [Automatic setting of initial heap size is enabled by default](#automatic-setting-of-initial-heap-size-is-enabled-by-default)



## Features and changes

### Binaries and supported environments

 OpenJ9 release 0.16.0 supports OpenJDK 13, which is available from the AdoptOpenJDK community at the following link:

- [OpenJDK version 13](https://adoptopenjdk.net/archive.html?variant=openjdk13&jvmVariant=openj9)

OpenJDK 13 with Eclipse OpenJ9 is not a long term support (LTS) release.

The latest builds of OpenJDK with OpenJ9 for Java 8 and 11 at the AdoptOpenJDK community are for Eclipse OpenJ9 release 0.15.2. Features mentioned in these release notes are not available in these builds. Although it might be possible to build an OpenJDK 8 or OpenJDK 11 with OpenJ9 0.16.0, testing at the project is not complete and therefore support for any of these features is not available.

 To learn more about support for OpenJ9 releases, including OpenJDK levels and platform support, see [Supported environments](openj9_support.md).

### Automatic setting of initial heap size is enabled by default

 OpenJ9 version 0.15.1 introduced the [`-XX:[+|-]UseGCStartupHints`](xxusegcstartuphints.md) option, which, when enabled, turned on the automatic learning and setting of an appropriate heap size for an application. This option is now enabled by default.

## Full release information

To see a complete list of changes between Eclipse OpenJ9 V0.15.2 and V0.16.0 releases, see the [Release notes](https://github.com/eclipse/openj9/blob/master/doc/release-notes/0.16/0.16.md).

<!-- ==== END OF TOPIC ==== version0.15.md ==== -->