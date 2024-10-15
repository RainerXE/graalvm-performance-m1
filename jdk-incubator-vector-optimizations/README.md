# jdk-incubator-vector-optimization
# updated to build with graalVM 24 EA

Source code for the blog post [Accelerating vector operations on the JVM using the new jdk.incubator.vector module](https://alexklibisz.com/2023/02/25/accelerating-vector-operations-jvm-jdk-incubator-vector-project-panama.html)

To run the benchmarks:

1. Install Oracle GraalVM 24 EA (maybe use sdkman...)
2. Install SBT, e.g., `$ brew install sbt`
3. Run the benchmarks via sbt-jmh: `$ sbt "Jmh/run"` 
