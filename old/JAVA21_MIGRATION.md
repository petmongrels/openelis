Migrate the code specified below from Java 7 (current) to Java 21.
Folder to migrate: old/openelis/src/us/mn/state/health/lims/common/util and subfolders

## Background
- the old code is present in old/openelis/src
- the new code should be present in src/main/java
- the package structure should be org.bahmni.openelis instead of us.mn.state.health.lims

## Migration Guidelines
- do not change old code
- copy to new location then perform migration. do not copy and migrate if the destination file already exists
- Only make minimal changes required for Java 21 compatibility
- Keep existing code style and patterns
- Update only what's necessary to compile and run on Java 21
- Do not remove any methods
- Do not remove any fields
- Do not migrate build.gradle files
- Do not run the build to get feedback on migration