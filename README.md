# MASSEMBLY-871

*- Demo Project to reproduce [MASSEMBLY-871](https://issues.apache.org/jira/browse/MASSEMBLY-871)*

When run on Windows, the Maven build of this project will cause ERRORs in the log but still produces valid archive files (tar.bz2, tar.gz and zip).

### How to Build

```
git clone git@github.com:ferstl/MASSEMBLY-871.git
cd MASSEMBLY-871
mvn clean install
```
