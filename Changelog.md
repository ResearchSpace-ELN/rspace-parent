2.1.0 - update various dependencies:
  * commons-lang:2.6 is now replaced with commons-lang3:3.18 **NOTE** this requires changing import statements in java classes relying on commons-lang
  * commons-io 2.13.0 -> 2.14.0
  * commons-beanutils 1.9.4 -> 1.11.0 
  * commons-collections 4.4 -> 4.5.0
  * spring-security-crypto 4.2.11.RELEASE -> 6.4.5
2.0.2 - update Apache Shiro dependency version (1.9.0 -> 1.13.0)
2.0.1 - remove maven-toolchains-plugin from plugins list, to allow building with jitpack
2.0.0 - use log4j2; also initial version for open-source
1.0.16 - build with Java17 (with j11 compatibility mode) as default
1.0.15 - updated commons-io to 2.13.0 (j17 req)
1.0.12 - rspac-2514 updates for 1.77
