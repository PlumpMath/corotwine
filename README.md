#Corotwine

Corotwine is an interface to various Twisted APIs using coroutines. Currently this support is limited to Greenlet (py.magic.greenlet).

The latest release is available at http://launchpad.net/corotwine. The release notes are available at https://launchpad.net/corotwine/+announcements.

##Dependencies

 * Twisted >= 8.1 (Ubuntu 'python-twisted', http://twistedmatrix.com/)
 * Py Lib (Ubuntu 'python-codespeak-lib', http://codespeak.net/py/)

##Learning

There are examples in corotwine/examples.py.

There is API documentation at
http://twistedmatrix.com/users/radix/corotwine/api/

Currently there are three interesting systems:

 * Protocol support at corotwine.protocol. Write TCP servers and clients.
 * Deferred support at corotwine.defer. Integrate with Deferred-using code    in both directions.
 * Time support at corotwine.clock.


##Contributing

File bugs at http://launchpad.net/corotwine

If you'd like to make contributions, please make sure they're unit-tested and documented.
