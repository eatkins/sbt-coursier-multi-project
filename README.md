With the new built in coursier dependency resolution, the child project
fails to compile because it tries to resolve the child's dependency on
the parent with a SNAPSHOT jar without looking for the classes in the
parent target directory.
