## Micronaut 3.8.4 v.s. Logback > 1.2.11

This is a minimal Micronaut project demonstrating that a Micronaut 3.8.4 application won't start when combined with Logback versions greater than 1.2.11.

This is due to the fact that the class EnvUtil has been moved in version 1.3.0.
See https://github.com/qos-ch/logback/tree/v_1.2.11/logback-classic/src/main/java/ch/qos/logback/classic/util and https://github.com/qos-ch/logback/tree/v_1.3.0/logback-core/src/main/java/ch/qos/logback/core/util.
