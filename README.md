# A fat or uber-jar
Based on the principle of containing all dependecies on a self-contained jar. This approach packs all dependecies into the output jar from the build process.

Maven is needed to run this project, after that just execute `mvn validate` and then `mvn clean package` and the uber jar is inside the target/assembly directory