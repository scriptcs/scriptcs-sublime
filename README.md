scriptcs-sublime
================

Sublime Text plug-in for scriptcs.

## Installation
The easiest way to install scriptcs-sublime is via the Package Control Plugin, once the package has been approved and made available.

In the mean time you can install it manually using git. Simply go to your packages directory and type: ``git clone https://github.com/scriptcs/scriptcs-sublime.git``.

To update to the latest version, use this command in the ``scriptcs-sublime`` directory: ``git pull origin master``.

## Usage
Once installed Sublime Text should recognize ``.csx`` files, and give you syntax highlighting. It also comes with a build system. To build and run hit ``Cmd+B`` on Mac, or ``Ctrl+B`` on Windows.

``scriptcs.exe`` must be on your ``PATH`` for the build system to work.

If your script has any compilation errors you can hit ``F4`` to navigate to the error.

You can also select a block of code and use the ``Edit - Comment - Toggle Comment`` command.