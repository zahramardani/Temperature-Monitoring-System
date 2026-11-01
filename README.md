# Temperature Monitoring System

Historical Eclipse/Xtext project material for a temperature-monitoring modelling workflow.

[All projects](https://github.com/zahramardani/ML2PP-Artifacts/blob/main/PROJECTS.md) · [Smart-home design archive](https://github.com/zahramardani/Smart-Home-Heterogeneous-hardware-)


## Technical focus

The project preserves an early language-engineering example for a temperature-monitoring domain. The checked-in Eclipse metadata identifies an Xtext project named `org.xtext.example.mydsl1`, Java compilation and Eclipse plugin builders.

| Metadata | What it establishes |
|---|---|
| Xtext builder and nature | Integration with the Xtext language-development workflow |
| Java builder and classpath | Java source compilation with the recorded Java 8 execution environment |
| PDE builders | Eclipse plugin manifest and schema build support |
| Source-folder entries | Expected `src`, `src-gen` and `xtend-gen` directories |

The archive is the starting point for recovering the project source. Successful import, language generation and a runtime-editor launch remain separate checks to perform in the restored environment.


## Project status

This repository contains an original project archive and Eclipse project metadata. The language source and generated model folders referenced by that metadata are not expanded in the repository root.

The checked-in classpath targets **JavaSE-1.8**. This identifies the original project setting; it is not a verified compatibility claim for newer Java or Eclipse versions.

## Repository contents

| File | Purpose |
|---|---|
| [org.xtext.example.mydsl1.rar](org.xtext.example.mydsl1.rar) | Original compressed project export |
| [.project](.project) | Eclipse project, Xtext, Java and PDE builders |
| [.classpath](.classpath) | Source-folder declarations and JavaSE-1.8 setting |
| [build.properties](build.properties) | Plugin build configuration |
| [plugin.xml](plugin.xml) | Generated EMF package registration |

## Inspect or restore the project

1. Extract the project archive into a separate working directory.
2. Locate the extracted Eclipse project and its source, model and manifest files.
3. Use an Eclipse installation with Java, Plugin Development Environment and Xtext support.
4. Import the extracted project with **File → Import → Existing Projects into Workspace**.
5. Resolve the original plugin dependencies before generating language artifacts or launching a runtime Eclipse instance.

A dependency lock, end-to-end build script and hardware execution instructions are not supplied. Restoration steps therefore require checking the archive's contents and original tool versions.

## Download the original source archive

**[Download `org.xtext.example.mydsl1.rar`](https://github.com/zahramardani/Temperature-Monitoring-System/raw/refs/heads/main/org.xtext.example.mydsl1.rar)** (approximately 1.55 MB).

GitHub tracks the RAR archive as a binary file, but cannot display or diff its internal source files. The files inside the archive are **not yet published as an expanded, independently versioned source tree** in this repository.

To examine the original project:

1. Download the archive from the link above, then open it using an RAR-compatible extractor (for example, Keka or The Unarchiver on macOS, or 7-Zip on Windows).
2. Extract the files into a separate directory. Inspect any `.project`, `.classpath`, `src/`, `src-gen/`, `xtend-gen/`, `META-INF/`, and `.mwe2` files that are actually present.
3. Compare the extracted source against the checked-in Eclipse metadata; use an appropriate Eclipse/Xtext toolchain to test whether the project can be imported and built.
4. After reviewing licences, credentials and generated outputs, publish the verified project sources in ordinary directories so GitHub can display and track them file by file. Retain the original RAR as an archival reference.

**Current verification boundary:** the Eclipse/Xtext project metadata is visible, but the contents of the RAR and the project's ability to build have not been independently verified.

## Related projects

- [Smart Home: Heterogeneous Hardware Design](https://github.com/zahramardani/Smart-Home-Heterogeneous-hardware-).
- [ML2++ Research Artifacts](https://github.com/zahramardani/ML2PP-Artifacts).
- [Forecasting API and SQL portfolio](https://github.com/zahramardani/river_prediction).

Original archive and metadata paths are retained for traceability.
