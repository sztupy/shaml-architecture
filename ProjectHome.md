# S#aml Architecture #

[![](http://shaml.sztupy.hu/images/shaml_large.jpg)](http://shaml.sztupy.hu/)

S#aml Architecture (from Sharp + Haml) is a web framework based on ASP.NET MVC 2, S#arp Architecture and NHibernate with ideas from Merb and Rails, and is designed to be easy to use, and to work on mono 2.4.4 and higher!

  * Check the [homepage](http://shaml.sztupy.hu)
  * Read the [tutorial](http://shaml.sztupy.hu/tutorial-start.html)
  * Check the [API Documentations](http://shaml.sztupy.hu/api/index.html)
  * Read the entries in the [wiki](http://code.google.com/p/shaml-architecture/w/list)
  * Check the [open bugs and feature requests](http://code.google.com/p/shaml-architecture/issues/list)
  * And contribute by forking the [GitHub Project](http://github.com/sztupy/shaml)

Current release is **0.5.0 GA** released on 21/04/2010

## 0.5.0 GA ##

  * Available at RubyGems.org (using `gem install shaml`)
  * Based on S#arp-architecture v1.5 beta 1
  * Uses the following libraries:
    * ASP.NET MVC 2.0 (with some [patches](http://github.com/sztupy/monosystemwebmvc))
    * NHaml View Engine (with some [patches](http://github.com/NHaml/NHaml/tree/metaadditions))
    * NHibernate 2.1.2 GA
    * Fluent NHibernate 1.0.0.629
    * NHibernate Validator 1.2.0.3001
    * DotNetOpenAuth 3.2.3.95 mono2 branch (with some [patches](http://github.com/sztupy/dotnetopenid))
    * LinFu 2.2.0.0
    * Compass stylesheet generation framework
  * Works and compiles under mono 2.4.4 (Ubuntu 10.04 LTS) or mono 2.6.3+ (and on .NET 3.5 as well)
  * The bundled command line utility supports the following scenarios
    * Creating models, controllers and resources
    * Compiling the application
    * Run the unit tests for the application
    * Start a server to serve the application
    * Open an interactive C# console to modify the domain objects
    * Create and update the database schema