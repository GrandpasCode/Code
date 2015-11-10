==============
Grandpa's Code
==============

`Grandpa's Code`_ is the team trying to revive old codes which probably were written by people who now are grandfathers, hence the team name. Well, they might be even great-grandpas already.

.. _Grandpa's Code: https://bitbucket.org/grandpas

.. contents:: **Contents**
   :local:


Wny
===

There are plenty of open source codes these days, and more from the older days. Those codes could still be compiled if build tools or libraries hadn't changed a lot. Some of them were coded in great quality, it'd be a shame to forget them just because compilers throw out errors that can easily be resolved by modifying the source code a few lines.


What
====

The grandpa's code will be included if:

* Open source licensed,
* Won't compile on modern environment,
* Abandoned or inactive for a very long time,
* Author(s) most likely couldn't be contacted, and
* No one has attempted to provide a repository of fixed code.


Goal
====

The goal of this team is to make grandpa's code be compiled on modern environments.

They won't be a clean or elegant fix, just a quick hack. There wouldn't be anything beyond that, that said, no features would be added, and even no existing bugs would be fixed.

However, that's not going to stop anyone who wants to improve the code, actually rebooting the development other than simply keeping the grandpa's code on life support.

Basics
------

* Keep things as they were.
* A lightweight markup ``README.rst`` for web browsing, which should:

  * Include where the source is from.

    A link to distribution or source tarball, or any webpages that are relevant.

  * Brief history if available:
  
    * When the grandpa's code starts and when the last release is made.
    * When Grandpa's Code starts to fix the code.
    * Other relevant information regarding the history of the code.

  * The original README should be kept and linked.
  
    No need to translate original content into new README unless the fix is more than a quick fix. In that case, the original should be removed.

  * Add information such as installation or requirements if they are missed in original README.

* History has to be kept.

  If there are several versions of source tarballs, they should be imported one by one with released dates and tagged properly.

  If the code was in RCS, then the history must be converted.

Possibilities
-------------

Other than quick fix, there are more can be done, but not required:

* Update to a specific standard, for instance C99 if it's C.
* Complete the documentation.

Dont's
------

These days, many developers use a stack of development tools, which each probably has their ridiculous amount of dependencies, and those developers might be very proud of their codes. But it seems they would be even harder to fix than grandpa's even in just a few months of time when so many stuff get involved.

So, please don't do that to grandpa's code. Keep the original build process, that is, most likely, just a single ``Makefile``. Those code might be written in 90s or earlier, note that Make was born in 1977, Autoconf in 1991, and Automake in 1997, so you wouldn't really expect to do ``./configure && make``, would you?

Not even converting to fully utilizing GNU build system unless you absolutely have a good reason. However, this doesn't mean you ain't allowed to incorporate tools like ``pkg-config`` into ``Makefile``.

``make`` it simple.


Contributions
=============

Anyone is welcome to contribute in anyway.

Since it mostly is a quick hack to get things going, some aspects might be overlooked, for example, cross-platform. If you find yourself can make a grandpa's code to work on another platform, please feel free to open a pull request.

Or you want to fix a long existing bug or add a new features, all these are welcome.


Requests
========

New Addition
------------

If you find a grandpa's code that is not included here, you can open an issue here to make a request of inclusion; and if you already fix it, that'd be wonderful, open an issue and you will be joining the team to maintain it if you want to.

Joining the Team
----------------

If you are dedicated, feel free to ask and tell us what you plan to do for Grandpa's Code, either focusing on specific repositories, helping maintain this team, or something else you have in mind.

Taking over
-----------

If you feel it's time for a grandpa's code to break free and live young again, that's transfer a repository under your account. Do open an issue to request, especially if you are the original author(s).


Apology to Grandma's Code
=========================

Of course, there is grandma's code, even settling down with using "grandpa," the team name was already a hard one to choice, it was even considered with "Make Grandpa Make!" and "Grandpa Alive!"

I don't think "Grandparent" or "Old Folk" would be better choice. So, forgive us, grandmas, "grandpa" is just a name.


Copyright
=========

The content in repository has been placed in Public Domain, or via UNLICENSE_. Other repositories has their own licenses.

.. _UNLICENSE: UNLICENSE
