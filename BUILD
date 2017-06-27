# The following dependencies were calculated from:
# /Users/carmi/temp/http-testkit/pom.xml

load("@io_bazel_rules_scala//scala:scala.bzl", "scala_library", "scala_binary", "scala_test", "scala_specs2_junit_test")

scala_specs2_junit_test(
    name = "repro",
    prefixes = ["Test"],
    suffixes = ["Test"],
    srcs = glob(["src/**/*.scala"]),
    deps = [
        "io_spray_spray_client_2_11",
        "com_typesafe_akka_akka_actor_2_11",
    ],
)

java_library(
    name = "com_typesafe_config",
    visibility = ["//visibility:public"],
    exports = [
        "@com_typesafe_config//jar",
    ],
)

java_library(
    name = "io_spray_spray_http_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@io_spray_spray_http_2_11//jar",
        "@io_spray_spray_util_2_11//jar",
        "@org_parboiled_parboiled_core//jar",
        "@org_parboiled_parboiled_scala_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "io_spray_spray_client_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@io_spray_spray_client_2_11//jar",
        "@io_spray_spray_can_2_11//jar",
        "@io_spray_spray_http_2_11//jar",
        "@io_spray_spray_httpx_2_11//jar",
        "@io_spray_spray_io_2_11//jar",
        "@io_spray_spray_util_2_11//jar",
        "@org_jvnet_mimepull_mimepull//jar",
        "@org_parboiled_parboiled_core//jar",
        "@org_parboiled_parboiled_scala_2_11//jar",
        "@org_scala_lang_modules_scala_xml_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "io_spray_spray_can_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@io_spray_spray_can_2_11//jar",
        "@io_spray_spray_http_2_11//jar",
        "@io_spray_spray_io_2_11//jar",
        "@io_spray_spray_util_2_11//jar",
        "@org_parboiled_parboiled_core//jar",
        "@org_parboiled_parboiled_scala_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "org_parboiled_parboiled_scala_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@org_parboiled_parboiled_scala_2_11//jar",
        "@org_parboiled_parboiled_core//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "org_parboiled_parboiled_core",
    visibility = ["//visibility:public"],
    exports = [
        "@org_parboiled_parboiled_core//jar",
    ],
)

java_library(
    name = "com_typesafe_akka_akka_actor_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@com_typesafe_akka_akka_actor_2_11//jar",
        "@com_typesafe_config//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "io_spray_spray_httpx_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@io_spray_spray_httpx_2_11//jar",
        "@io_spray_spray_http_2_11//jar",
        "@io_spray_spray_util_2_11//jar",
        "@org_jvnet_mimepull_mimepull//jar",
        "@org_scala_lang_modules_scala_xml_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "org_scala_lang_modules_scala_xml_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@org_scala_lang_modules_scala_xml_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "org_scala_lang_scala_library",
    visibility = ["//visibility:public"],
    exports = [
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "org_jvnet_mimepull_mimepull",
    visibility = ["//visibility:public"],
    exports = [
        "@org_jvnet_mimepull_mimepull//jar",
    ],
)

java_library(
    name = "io_spray_spray_util_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@io_spray_spray_util_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

java_library(
    name = "io_spray_spray_io_2_11",
    visibility = ["//visibility:public"],
    exports = [
        "@io_spray_spray_io_2_11//jar",
        "@io_spray_spray_http_2_11//jar",
        "@io_spray_spray_util_2_11//jar",
        "@org_parboiled_parboiled_core//jar",
        "@org_parboiled_parboiled_scala_2_11//jar",
        "@org_scala_lang_scala_library//jar",
    ],
)

