# The following dependencies were calculated from:
# /Users/carmi/temp/http-testkit/pom.xml


# com.typesafe.akka:akka-actor_2.11:jar:2.3.6
maven_jar(
    name = "com_typesafe_config",
    artifact = "com.typesafe:config:1.2.1",
    sha1 = "f771f71fdae3df231bcd54d5ca2d57f0bf93f467",
)

# io.spray:spray-client_2.11:bundle:1.3.2
# io.spray:spray-io_2.11:bundle:1.3.2
# io.spray:spray-can_2.11:bundle:1.3.2
# io.spray:spray-httpx_2.11:bundle:1.3.2
maven_jar(
    name = "io_spray_spray_http_2_11",
    artifact = "io.spray:spray-http_2.11:1.3.2",
    sha1 = "b8c4da67c214cca7b4e89a59a8754c0a18c1d9ac",
)

# /Users/carmi/temp/http-testkit/pom.xml
# com.wix.hoopoe.http:http-testkit_2.11:jar:0.0.2-SNAPSHOT
maven_jar(
    name = "io_spray_spray_client_2_11",
    artifact = "io.spray:spray-client_2.11:1.3.2",
    sha1 = "cc97640229a9441c246d273a1e3764b52c73c38f",
)

# io.spray:spray-client_2.11:bundle:1.3.2
maven_jar(
    name = "io_spray_spray_can_2_11",
    artifact = "io.spray:spray-can_2.11:1.3.2",
    sha1 = "29445d188746097c7e990892f8aba55be2da3044",
)

# io.spray:spray-http_2.11:bundle:1.3.2
maven_jar(
    name = "org_parboiled_parboiled_scala_2_11",
    artifact = "org.parboiled:parboiled-scala_2.11:1.1.6",
    sha1 = "a06cf88a597039d22e65b53eac6a35dddfddd095",
)

# org.parboiled:parboiled-scala_2.11:bundle:1.1.6
maven_jar(
    name = "org_parboiled_parboiled_core",
    artifact = "org.parboiled:parboiled-core:1.1.6",
    sha1 = "11bd0c34fc6ac3c3cbf440ab8180cc6422c044e9",
)

# /Users/carmi/temp/http-testkit/pom.xml
# com.wix.hoopoe.http:http-testkit_2.11:jar:0.0.2-SNAPSHOT
maven_jar(
    name = "com_typesafe_akka_akka_actor_2_11",
    artifact = "com.typesafe.akka:akka-actor_2.11:2.3.6",
    sha1 = "10b5a0b8e60d32a158d3b99c1727158197a473fd",
)

# io.spray:spray-client_2.11:bundle:1.3.2
maven_jar(
    name = "io_spray_spray_httpx_2_11",
    artifact = "io.spray:spray-httpx_2.11:1.3.2",
    sha1 = "4af7f6c578da9c1f91289c4a1e94825dceac316c",
)

# io.spray:spray-httpx_2.11:bundle:1.3.2
maven_jar(
    name = "org_scala_lang_modules_scala_xml_2_11",
    artifact = "org.scala-lang.modules:scala-xml_2.11:1.0.2",
    sha1 = "820fbca7e524b530fdadc594c39d49a21ea0337e",
)

# org.scala-lang.modules:scala-xml_2.11:bundle:1.0.2 wanted version 2.11.1
# /Users/carmi/temp/http-testkit/pom.xml
# io.spray:spray-httpx_2.11:bundle:1.3.2 wanted version 2.11.2
# com.wix.hoopoe.http:http-testkit_2.11:jar:0.0.2-SNAPSHOT
# org.parboiled:parboiled-scala_2.11:bundle:1.1.6 wanted version 2.11.0
# io.spray:spray-can_2.11:bundle:1.3.2 wanted version 2.11.2
# io.spray:spray-io_2.11:bundle:1.3.2 wanted version 2.11.2
# io.spray:spray-client_2.11:bundle:1.3.2 wanted version 2.11.2
# io.spray:spray-util_2.11:bundle:1.3.2 wanted version 2.11.2
# com.typesafe.akka:akka-actor_2.11:jar:2.3.6 wanted version 2.11.2
# io.spray:spray-http_2.11:bundle:1.3.2 wanted version 2.11.2
maven_jar(
    name = "org_scala_lang_scala_library",
    artifact = "org.scala-lang:scala-library:2.11.7",
    sha1 = "f75e7acabd57b213d6f61483240286c07213ec0e",
)

# io.spray:spray-httpx_2.11:bundle:1.3.2
maven_jar(
    name = "org_jvnet_mimepull_mimepull",
    artifact = "org.jvnet.mimepull:mimepull:1.9.4",
    sha1 = "6ffca64fe0209a94c5a973a32e93b5eae0ac384e",
)

# io.spray:spray-http_2.11:bundle:1.3.2
# io.spray:spray-client_2.11:bundle:1.3.2
# io.spray:spray-io_2.11:bundle:1.3.2
# io.spray:spray-can_2.11:bundle:1.3.2
# io.spray:spray-httpx_2.11:bundle:1.3.2
maven_jar(
    name = "io_spray_spray_util_2_11",
    artifact = "io.spray:spray-util_2.11:1.3.2",
    sha1 = "2c2630219f27c3ee3ba007a8fefb7e0a32f7e5ce",
)

# io.spray:spray-can_2.11:bundle:1.3.2
maven_jar(
    name = "io_spray_spray_io_2_11",
    artifact = "io.spray:spray-io_2.11:1.3.2",
    sha1 = "c6bee64ca7df8417e16051925eef960cf1557063",
)

rules_scala_version="2381281753a49b35fdbbfd64f81c60e58549a6c4" # update this as needed

http_archive(
             name = "io_bazel_rules_scala",
             url = "https://github.com/bazelbuild/rules_scala/archive/%s.zip"%rules_scala_version,
             type = "zip",
             strip_prefix= "rules_scala-%s" % rules_scala_version
             )

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_repositories")
scala_repositories()

load("@io_bazel_rules_scala//specs2:specs2_junit.bzl","specs2_junit_repositories")
specs2_junit_repositories()
