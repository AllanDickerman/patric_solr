Installation
===========

1. Download PATRIC customized solr package from Developer Guides folder in box.com (e.g solr-5.3.0-PATRIC.tgz)

    ```
    > tar xvzf solr-5.3.0-PATRIC.tgz
    > cd solr-5.3.0-PATRIC
    ```

2. Clone config files into the installation directory

    ```
    > git clone git@github.com:PATRIC3/patric_solr.git
    ```

3. Start Solr instance

    ```
    ./bin/solr restart -Dsolr.solr.home=./patric_solr/ -Dlucene.version=5.3
    ```
