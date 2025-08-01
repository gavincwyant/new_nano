
*GNU nano -- a simple editor, inspired by Pico*

**Purpose**

To bring a small convenience to my favorite text editor. 

**Appearance**

*newnano text editor*
![Alt text](https://raw.githubusercontent.com/gavincwyant/new_nano/master/auto.png)

*press Ctrl+Space to initiate autocomplete window and arrow-up/arrow-down to select word you wish to complete with*
![Alt text](https://github.com/gavincwyant/new_nano/blob/master/complete.png)

**Origin**

    The nano project was started in 1999 because of a few "problems"
    with the wonderfully easy-to-use and friendly Pico text editor.

    First and foremost was its license: the Pine suite does not use
    the GPL, and (before using the Apache License) it had unclear
    restrictions on redistribution.  Because of this, Pine and Pico
    were not included in many GNU/Linux distributions.  Furthermore,
    some features (like go-to-line-number or search-and-replace) were
    unavailable for a long time or require a command-line flag.  Yuck.

    Nano aimed to solve these problems by: 1) being truly free software
    by using the GPL, 2) emulating the functionality of Pico as closely
    as is reasonable, and 3) including extra functionality by default.

    Nowadays, nano wants to be a generally useful editor with sensible
    defaults (linewise scrolling, no automatic line breaking).

    The nano editor is an official GNU package.  For more information on
    GNU and the Free Software Foundation, please see https://www.gnu.org/.

License

    Nano's code and documentation are covered by the GPL version 3 or
    (at your option) any later version, except for two functions that
    were copied from busybox which are under a BSD license.  Nano's
    documentation is additionally covered by the GNU Free Documentation
    License version 1.2 or (at your option) any later version.  See the
    files COPYING and COPYING.DOC for the full text of these licenses.

    When in any file of this package a copyright notice mentions a
    year range (such as 1999-2011), it is a shorthand for a list of
    all the years in that interval.

How to compile and install nano

    Download the latest nano source tarball, and then:

        tar -xvf nano-x.y.tar.gz
        cd nano-x.y
        ./configure
        make
        make install

    You will need the header files of ncurses installed for ./configure
    to succeed -- get them from libncurses-dev (Debian) or ncurses-devel
    (Fedora) or a similarly named package.  Use --prefix with ./configure
    to override the default installation directory of /usr/local.

    After installation you may want to copy the doc/sample.nanorc file
    to your home directory, rename it to ".nanorc", and then edit it
    according to your taste.

Web Page

    https://nano-editor.org/

Mailing Lists

    There are three nano-related mailing-lists.

    * <info-nano@gnu.org> is a very low traffic list used to announce
      new nano versions or other important info about the project.

    * <help-nano@gnu.org> is for those seeking to get help without
      wanting to hear about the technical details of its development.

    * <nano-devel@gnu.org> is the list used by the people that make nano
      and a general development discussion list, with moderate traffic.

    To subscribe, send email to <name>-request@gnu.org with a subject
    of "subscribe", where <name> is the list you want to subscribe to.

    The archives of the development and help mailing lists are here:

        https://lists.gnu.org/archive/html/nano-devel/
        https://lists.gnu.org/archive/html/help-nano/

Bug Reports

    If you find a bug, please file a detailed description of the problem
    on nano's issue tracker: https://savannah.gnu.org/bugs/?group=nano
    (you will need an account to be able to do so), or send an email
    to the nano-devel list (no need to subscribe, but mention it if
    you want to be CC'ed on an answer).

