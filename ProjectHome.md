THIS PROJECT HAS MOVED! See http://github.com/simplejson/simplejson

simplejson is compatible with Python 2.5 and later with no external dependencies. It covers the full JSON specification for both encoding and decoding, with unicode support. By default, encoding is done in an encoding neutral fashion (plain ASCII with \uXXXX escapes for unicode characters).

simplejson 2.1.1 is the latest version:
  * [documentation](http://simplejson.googlecode.com/svn/tags/simplejson-2.1.1/docs/index.html)
  * [PyPI: simplejson](http://pypi.python.org/pypi/simplejson) (download)

The encoder may be subclassed to provide serialization in any kind of situation, without any special support by the objects to be serialized (somewhat like pickle).

The decoder can handle incoming JSON strings of any specified encoding (UTF-8 by default).

simplejson is the externally maintained development version of the json library included with Python 2.6 and Python 3.0, but maintains backwards compatibility with Python 2.5.