# Maven process inspector

Inspect the internals of running maven process using groovy script. To be used as:

    $ mvn -q package ...
    # Or, to provide custom script
    $ mvn -q package -Dscript="..." ...

The default script prints java properties, environment variables and JVM arguments.

Happy debugging!
