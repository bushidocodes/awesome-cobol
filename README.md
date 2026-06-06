# awesome-cobol

## Compilers

[GnuCOBOL](https://gnucobol.sourceforge.io/) — A free/open-source COBOL compiler that converts COBOL source code into native executables across Linux, Windows, and macOS, supporting modern COBOL dialects and integrating with common development environments. *COBOL relevance: The de facto standard free compiler for COBOL development and experimentation outside of mainframe environments.*

[GCC COBOL (gcobol)](https://gcc.gnu.org/onlinedocs/gcobol.pdf) — `gcobol` is the official GCC COBOL front-end that compiles COBOL source directly into object code and executables as part of the GNU Compiler Collection, implementing the ISO/IEC 1989:2023 standard with backward-compatibility extensions. *COBOL relevance: Brings first-class COBOL support into GCC, enabling COBOL programs to benefit from the same toolchain, optimizations, and platform targets as C and Fortran.*

[IBM COBOL Compiler Family](https://www.ibm.com/products/cobol-compiler-family) — IBM's suite of enterprise-grade COBOL compilers targeting z/OS and other IBM platforms, providing high-performance compilation, standards compliance, and deep integration with IBM tooling. *(HTTP 403; description inferred from context.)* *COBOL relevance: The dominant compiler for production mainframe COBOL workloads running on IBM z/OS systems.*

[Fujitsu COBOL](https://archives.global.fujitsu.com/global/products/software/developer-tool/netcobol/) — Fujitsu's NetCOBOL is a commercial COBOL development environment targeting Windows and other platforms, offering a compiler, runtime, and tooling for building enterprise applications. *(Page unreachable; description inferred from context.)* *COBOL relevance: A widely-used commercial option for COBOL on Windows, particularly in Japanese enterprise environments.*

[Tiny COBOL](https://tiny-cobol.sourceforge.net/) (dead) — An open-source COBOL compiler targeting COBOL 85 standards, running on FreeBSD, Linux, and Windows via MinGW and building on the GCC backend. *COBOL relevance: A lightweight, standards-focused alternative compiler useful for understanding compiler internals or running COBOL 85 programs in lightweight environments.*

[Rocket Software - COBOL Products](https://www.rocketsoftware.com/en-us/products/cobol) — Rocket Software provides commercial COBOL compilers and runtime environments for a range of platforms including Windows, Linux, and mainframe, with a focus on modernizing and maintaining legacy COBOL applications. *(HTTP 403; description inferred from context.)* *COBOL relevance: Offers enterprise-supported COBOL runtimes and tooling for organizations maintaining large COBOL codebases.*

[Visual COBOL (Broadcom/Micro Focus)](https://www.microfocus.com/en-us/products/visual-cobol/) — Visual COBOL is a full-featured COBOL development environment from Micro Focus (now Broadcom/OpenText) that enables developers to write, debug, test, and modernize COBOL applications with integration into Visual Studio and VS Code. *COBOL relevance: One of the most widely adopted commercial IDEs and compiler toolchains for COBOL on distributed platforms.*

[RM/COBOL (Broadcom/Micro Focus)](https://www.microfocus.com/en-us/products/rm-cobol/) — RM/COBOL is a long-established Micro Focus (now Broadcom/OpenText) COBOL compiler and runtime targeting business applications on Windows and Linux, known for its portability and reliability. *COBOL relevance: A proven compiler and runtime for running and maintaining RM/COBOL applications across modern operating systems.*

[COBOL-preservation](https://github.com/sorenroug/COBOL-preservation) — A GitHub archive dedicated to preserving vintage COBOL compilers and development tools for legacy platforms such as CP/M and MS-DOS, storing source code and documentation composed primarily of COBOL and Assembly. *COBOL relevance: An invaluable historical resource for researchers and developers studying the evolution of COBOL compilers and toolchains.*

## WebAssembly

[cobol-js-emscripten](https://github.com/moxon6/cobol-js-emscripten) — A proof-of-concept that compiles COBOL programs to WebAssembly by first transpiling COBOL to C via GnuCOBOL, then using Emscripten to build a Wasm module, enabling COBOL to run in web browsers. *COBOL relevance: Demonstrates that existing COBOL code can be brought to the browser environment without a full rewrite.*

[cobweb (Cloudflare)](https://github.com/cloudflare/cobweb) — CobWeb is a COBOL-to-WebAssembly compiler created by Cloudflare that compiles COBOL programs into WebAssembly modules compatible with Cloudflare Workers, allowing classic mainframe-style code to run in modern serverless cloud environments. *COBOL relevance: Opens a path for deploying COBOL business logic at the edge via Cloudflare Workers without a mainframe.*

[cobol-worker (Cloudflare)](https://github.com/cloudflare/cobol-worker) — A demonstration repository from Cloudflare showing a COBOL program compiled to WebAssembly and deployed as a live Cloudflare Worker, accessible via HTTP requests. *COBOL relevance: Serves as a concrete, working example of COBOL running as a serverless function in the browser/edge via WebAssembly.*

## GraalVM

[CoBOL-GraalVM](https://github.com/phe-sto/CoBOL-GraalVM) — Demonstrates how to compile and execute COBOL programs using GraalVM Community Edition and GnuCOBOL by converting COBOL source to C and then to LLVM IR, enabling polyglot execution on any platform running GraalVM. *COBOL relevance: Shows how COBOL can participate in GraalVM's polyglot ecosystem and run alongside Java, Python, and other languages on the JVM.*

## IDEs / Editors / Plugins

[OpenCobolIDE](https://opencobolide.software.informer.com/4.6/) — OpenCobolIDE is a lightweight, free, cross-platform IDE for COBOL development built on top of GnuCOBOL, offering syntax highlighting, code completion, and a simple build/run workflow. *COBOL relevance: Provides a beginner-friendly graphical IDE for writing and compiling COBOL without needing a mainframe or expensive commercial tools.*

[COBOL Language Support (Eclipse Che4z LSP)](https://github.com/eclipse-che4z/che-che4z-lsp-for-cobol) — A Language Server Protocol extension that provides autocomplete, syntax highlighting, and diagnostics for COBOL code and copybooks in VS Code and Eclipse Che, with integration into mainframe systems via Zowe Explorer. *COBOL relevance: Brings modern IDE intelligence — real-time error checking, code completion, and semantic analysis — to COBOL development in widely-used editors.*

[IBM Z Open Editor (VS Code)](https://marketplace.visualstudio.com/items?itemName=IBM.zopeneditor) — A VS Code extension from IBM that provides language support for Enterprise COBOL, PL/I, HLASM, REXX, and JCL on z/OS, offering syntax checking, code completion, refactoring, and integration with IBM z/OS systems. *COBOL relevance: Enables mainframe COBOL developers to use VS Code as a modern development environment connected directly to z/OS workloads.*

[VMS IDE (VS Code)](https://marketplace.visualstudio.com/items?itemName=VMSSoftwareInc.vms-ide) — A VS Code extension for developing applications on OpenVMS systems, providing SSH connectivity, source code synchronization, project management, debugging, and syntax highlighting for languages used on OpenVMS including COBOL. *COBOL relevance: Allows developers maintaining COBOL applications on OpenVMS to work from VS Code with full remote build and debug support.*

[editel](https://sourceforge.net/projects/editel/) — A screen editor and code generator for GnuCOBOL programmers that lets developers visually design terminal screens and automatically generate the corresponding COBOL SCREEN SECTION source code; written in Turbo Pascal and runs via DOSBox on modern OSes. *COBOL relevance: Eliminates manual coding of screen layouts for GnuCOBOL and Micro Focus COBOL applications.*

[supra-cobol](https://sourceforge.net/projects/supra-cobol/) — A lightweight COBOL-specific code editor supporting multi-file editing and syntax highlighting, targeting RM-85 and MS-Cobol compiler toolchains. *COBOL relevance: Provides a dedicated editing environment for developers working with older COBOL compiler toolchains.*

[coplug](https://sourceforge.net/projects/coplug/) — An Eclipse IDE plugin originally written for Fujitsu COBOL and repurposed for GnuCOBOL that provides syntax support and IDE features for COBOL development. *COBOL relevance: Brings COBOL development into the Eclipse ecosystem, giving developers a modern IDE experience with GnuCOBOL.*

[vscobolscreen](https://sourceforge.net/projects/vscobolscreen/) — A code generator that reads simple text-based screen meta-language definitions and outputs COBOL SCREEN SECTION source code callable via PERFORM statements. *COBOL relevance: Automates the tedious task of hand-coding terminal screen handlers in COBOL, complementing tools like editel for screen-centric application development.*

## Parsers

[ProLeap COBOL Parser](https://github.com/uwol/proleap-cobol-parser) — A Java-based COBOL parser built on an ANTLR4 grammar that generates an Abstract Syntax Tree (AST) and Abstract Semantic Graph (ASG), capturing data flow and control flow semantics for use by analyzers, interpreters, and code transformers. *COBOL relevance: A robust foundation for building COBOL analysis, refactoring, or migration tooling that needs deep semantic understanding of the source code.*

[Koopa COBOL Parser](https://github.com/krisds/koopa) — A specialized COBOL parser generator that processes COBOL source files directly without preprocessing, handles CICS/SQL fragments, and includes a complete lexer, parser, viewer with syntax highlighting, copybook expansion, and XML parse tree output. *COBOL relevance: Well-suited for static analysis and code comprehension tasks on real-world COBOL codebases that mix embedded CICS and SQL.*

[tree-sitter-cobol](https://github.com/BloopAI/tree-sitter-cobol) — A COBOL 85 grammar implementation for the tree-sitter incremental parsing toolkit, validated against the NIST COBOL 85 test suite. *COBOL relevance: Enables fast, incremental COBOL syntax parsing for editor tooling, code navigation, and syntax highlighting in any tree-sitter-compatible environment.*

[cobol-parsers](https://github.com/alansferreira/cobol-parsers) — A JavaScript library that parses COBOL programs and JCL scripts into structured JSON, extracting statements, embedded SQL, and variable references to allow programmatic analysis of legacy mainframe code. *COBOL relevance: Enables JavaScript/Node.js tooling to introspect and process COBOL source without requiring a JVM or native build environment.*

[COBOL74 Parser and Viewer](https://github.com/KevinHindmarch/COBOL74-Parser-and-viewer) — A Python-based tool that parses COBOL 74 source files and generates Abstract Syntax Trees, paired with interactive D3.js-based web visualizers for exploring program structure. *COBOL relevance: Useful for understanding the structure of very old COBOL 74 programs, particularly in financial systems where legacy code predates later standards.*

[koopa (benravago fork)](https://github.com/benravago/koopa) — A fork and port of the Koopa COBOL parser generator updated to run on JDK 12+ with JUnit 5 testing. *COBOL relevance: Provides an up-to-date, JDK 12+-compatible entry point into Koopa's COBOL parsing capabilities for developers on modern Java runtimes.*

## Testing

[COBOL Check](https://openmainframeproject.org/projects/cobol-check/) — A unit testing framework for COBOL under the Open Mainframe Project that operates as a precompiler, enabling developers to test individual COBOL paragraphs in isolation and supporting both on-platform and off-platform (local) development workflows. *COBOL relevance: Brings test-driven development practices to COBOL by allowing fine-grained paragraph-level unit tests without requiring a full mainframe environment.*

[COB-FAKER](https://github.com/dinodev76/COB-FAKER) — A partial COBOL port of the Python Faker library that generates and anonymizes synthetic test data such as names and addresses, created and tested with GnuCOBOL on Windows. *COBOL relevance: Fills a gap in the COBOL testing ecosystem by providing a native way to generate realistic fake data for test cases directly in COBOL.*

[Rocket Unit Testing Framework Samples](https://github.com/RocketSoftwareCOBOLandMainframe/Rocket-Unit-Testing-Framework-Samples) — A collection of sample COBOL programs from Rocket Software demonstrating their Unit Testing Framework, covering scenarios from basic test cases to data-driven tests, mocking, and integration with CICS and SQL subsystems. *COBOL relevance: Provides practical, ready-to-run examples for teams adopting the Rocket Unit Testing Framework on mainframe COBOL projects.*

[Codewars COBOL Test Template](https://github.com/codewars/cobol-test) — A testing framework for COBOL programs on the Codewars platform, including a preprocessor, copybooks, and compilation tools that allow kata authors and solvers to write and run structured test cases for COBOL solutions. *COBOL relevance: Enables competitive coding and skill challenges in COBOL, making it easier to practice the language on a well-known coding platform.*

[cobol_unit_test_suite](https://github.com/jasongorman/cobol_unit_test_suite) — A demonstration of unit testing patterns for COBOL programs, providing example test files and assertion utilities that illustrate how to structure organized test suites for COBOL functions. *COBOL relevance: Serves as a reference implementation for developers looking to adopt structured unit testing conventions in their own COBOL codebases.*

[geramassacobol](https://sourceforge.net/projects/geramassacobol/) — A Java/Swing desktop application for generating bulk test data specifically for validating COBOL batch processing components, originally developed as an academic thesis project. *COBOL relevance: Speeds up COBOL batch testing by automating the creation of large, structured test datasets.*

## Debugging

[tp-cobol-debugg](https://sourceforge.net/projects/tp-cobol-debugg/) — A COBOL debugger for GnuCOBOL/OpenCOBOL written entirely in GnuCOBOL itself, providing step-through debugging capabilities for developers whose COBOL vendor does not include native debugging tools. *COBOL relevance: Fills a critical gap for GnuCOBOL developers who need interactive debugging without relying on expensive vendor tooling.*

## Analyzers

[COBOL Analyzer (bodingh.se)](https://www.bodingh.se/cobol.html) — A downloadable COBOL analysis tool that examines programs and produces cross-reference and dependency reports. *COBOL relevance: Provides static analysis capabilities for COBOL codebases, useful for understanding and maintaining legacy programs.*

[cobolanalyzer](https://sourceforge.net/projects/cobolanalyzer/) — A tool that examines dependencies within COBOL programs and copybooks, helping developers identify which programs use specific copybooks or subprograms, detect unused copybooks, and count lines of code. *COBOL relevance: Essential for large legacy COBOL estates where understanding copybook dependencies and dead code is a common maintenance challenge.*

[cobol2html](https://sourceforge.net/projects/cobol2html/) — A multi-language tool that analyzes COBOL programs or entire projects and generates cross-referenced HTML documentation to aid code review and maintenance. *COBOL relevance: Turns opaque legacy COBOL codebases into browsable HTML for easier comprehension and impact analysis.*

[Coboldoc (unstring)](https://sourceforge.net/projects/unstring/) — A Java web application with a browser-based interface for analyzing COBOL code; it maintains a cross-reference database of static and dynamic calls to support impact analysis and is designed to run directly on z/OS. *COBOL relevance: Provides a modern browser-based navigator for large COBOL codebases, making dependency tracking and impact analysis accessible.*

[makeajackson](https://sourceforge.net/projects/makeajackson/) — A Java desktop tool for creating Jackson Structured Design (JSD) diagrams, a methodology used for designing the logical structure of procedural programs including COBOL. *COBOL relevance: Supports the JSD design methodology that many COBOL teams use to model program logic before coding.*

## TUI

[cobcurses](https://github.com/ve3wwg/cobcurses) — A package that enables COBOL programmers to create screen-based terminal applications using the Open-Cobol compiler by wrapping the curses/ncurses library, working around the lack of SCREENS SECTION support. *COBOL relevance: Allows GnuCOBOL developers to build full-screen terminal UIs in COBOL without depending on proprietary screen-handling extensions.*

## GUI

[GuiCOBOL](https://github.com/federico-priolo/GuiCOBOL) — A GUI framework for GnuCOBOL that leverages the Agar GUI toolkit to enable developers to build native graphical user interfaces for COBOL applications. *COBOL relevance: Lets COBOL developers modernize legacy batch programs with a desktop GUI layer without rewriting business logic in another language.*

[guicobol](https://sourceforge.net/projects/guicobol/) — A command-line preprocessor that allows OpenCOBOL developers to use GTK 2.x libraries with an object-oriented syntax, adding full graphical user interface support to COBOL programs. *COBOL relevance: Lets COBOL developers build native GTK desktop applications, providing an alternative GUI path for teams using older OpenCOBOL/GnuCOBOL toolchains.*

## Game Engine

[COBOL-Engine](https://github.com/ProGM/COBOL-Engine) — A game engine written in COBOL backed by the SDL2 library, providing wrapped SDL2 utilities and a working Pong example to demonstrate game development in the language. *COBOL relevance: A creative proof-of-concept showing how COBOL's capabilities can extend well beyond batch processing into multimedia and real-time event-driven programming.*

## Web Libraries

[COBOL on Wheelchair](https://github.com/azac/cobol-on-wheelchair) — A micro web framework for COBOL that allows COBOL programs to run as CGI scripts on Apache servers, enabling basic web application development in the language. *COBOL relevance: One of the most established approaches for exposing COBOL business logic over HTTP without a middleware rewrite.*

[webbol](https://github.com/jmsdnns/webbol) — A minimal static web server written in GnuCOBOL that serves files from a directory over HTTP on port 8080, with MIME type detection and path traversal protection. *COBOL relevance: Demonstrates that COBOL can handle network I/O and serve web content directly, useful as a learning reference for COBOL networking.*

[webbol (Nishanthjpatil)](https://github.com/Nishanthjpatil/webbol) — A fork of the webbol project providing a minimal static web server written in COBOL for hosting static websites. *COBOL relevance: An alternative reference implementation of COBOL-based HTTP serving for developers exploring web integration.*

[COBWEB](https://github.com/addinall/COBWEB) — A responsive HTML5/CSS3 framework for COBOL systems that generates mobile-friendly web pages from pure COBOL code, complete with an integrated content management system and no dependency on JavaScript frameworks. *COBOL relevance: Enables COBOL shops to build modern-looking web front ends entirely within a COBOL environment, avoiding the need to introduce Java or PHP.*

[cobolwebserver](https://github.com/KDreynolds/cobolwebserver) — A basic web server built with COBOL and C that serves static HTML files from a specified directory on port 8080. *COBOL relevance: Illustrates how COBOL can be combined with C interop to handle low-level socket programming and serve web content.*

[cobol-website](https://github.com/BalakeKarbon/cobol-website) — An entire website built in fixed-format COBOL using the CobDOMinate HTML DOM library, compiled to WebAssembly so it can run directly in modern browsers. *COBOL relevance: A cutting-edge demonstration of compiling COBOL to WebAssembly, opening a path for COBOL logic to run client-side in the browser.*

## Containerized Deployment

[docker-gnucobol](https://github.com/morecobol/docker-gnucobol) — A Docker image with GNU COBOL pre-installed, allowing developers to compile and run COBOL programs immediately without any local toolchain setup. *COBOL relevance: Provides a zero-friction environment for COBOL development and CI/CD pipelines using containers.*

[sample-docker-cobol (DigitalOcean)](https://github.com/digitalocean/sample-docker-cobol) — A sample application showing how to deploy COBOL programs to DigitalOcean's App Platform via Docker, using Flask to route HTTP requests to compiled COBOL binaries. *COBOL relevance: An official cloud-provider example demonstrating that COBOL workloads can be containerized and deployed on modern PaaS infrastructure.*

[containerizedCOBOL](https://github.com/idjohnson/containerizedCOBOL) — A project demonstrating how to run COBOL programs inside Docker containers alongside a Node.js server component, showcasing modern deployment patterns for legacy COBOL code. *COBOL relevance: Shows how COBOL logic can be wrapped in a microservice architecture, integrating with contemporary backend stacks.*

[example-cobol](https://github.com/koduki/example-cobol) — A Docker-based environment configured for COBOL CGI applications, with sample code and tooling to compile and execute COBOL scripts as web endpoints. *COBOL relevance: Useful as a starting template for developers wanting to deploy COBOL-based CGI services inside containers.*

[cobol-container](https://github.com/edudiasg/cobol-container) — A containerized development environment using Docker Compose and Make to streamline building and executing GNUCobol programs, eliminating the need for a local COBOL installation. *COBOL relevance: Lowers the barrier to entry for COBOL development by providing a reproducible, self-contained build environment.*

## Serverless Deployment

[lambda_cobol](https://github.com/BBCapMegane/lambda_cobol) — A project that demonstrates running GnuCOBOL programs on AWS Lambda using Docker-based custom runtimes, with sample COBOL programs to validate the setup. *COBOL relevance: Proves COBOL can be deployed as serverless functions on AWS, enabling event-driven execution of COBOL logic without managing servers.*

[serverless-cobol](https://github.com/atymic/serverless-cobol) — A serverless application that runs COBOL (via cobol-on-wheelchair) on Google Cloud Run, combining a classic mainframe language with modern cloud-native infrastructure. *COBOL relevance: Demonstrates deploying COBOL as a scalable, containerized serverless service on GCP with minimal operational overhead.*

[openfaas-cobol-template](https://github.com/devries/openfaas-cobol-template) — An OpenFaaS function template that enables deploying COBOL programs as serverless functions on Kubernetes, with a sample handler for processing input and returning output. *COBOL relevance: Enables COBOL developers to package and deploy business logic as functions in a Kubernetes-native FaaS platform.*

## Serialization / Encoding

[CobolJsonParser](https://github.com/askadian/CobolJsonParser) — A COBOL program for parsing JSON strings, bundled with sample JSON data to demonstrate reading structured modern data formats from within COBOL. *COBOL relevance: Addresses the common integration challenge of consuming REST API or microservice JSON responses in legacy COBOL systems.*

[cob2csv](https://github.com/HorseyofCoursey/cob2csv) — A pair of command-line tools written in pure GnuCOBOL that convert fixed-width COBOL flat files to CSV and back, requiring no mainframe system. *COBOL relevance: Solves a ubiquitous data migration problem for COBOL shops needing to exchange data with modern systems that expect delimited formats.*

[base64 (COBOL)](https://github.com/cschneid-the-elder/base64) — A COBOL implementation of base64 encoding and decoding. *COBOL relevance: Provides a reusable COBOL routine for base64 operations needed when integrating with web services or encoding binary data in COBOL programs.*

[coboltojson](https://sourceforge.net/projects/coboltojson/) — A tool that converts COBOL data files to and from JSON using a COBOL copybook as the structural schema, and can also auto-generate JSON schemas from copybook definitions. *COBOL relevance: Bridges legacy COBOL flat-file data with modern JSON-based APIs and data pipelines.*

[coboltocsv](https://sourceforge.net/projects/coboltocsv/) — A COBOL-and-Java tool that converts COBOL data files to and from CSV format using a copybook definition for accurate field mapping. *COBOL relevance: Simplifies data extraction from legacy COBOL files into spreadsheet-friendly CSV for reporting or migration.*

[coboltoxml](https://sourceforge.net/projects/coboltoxml/) — A COBOL-and-Java tool that converts COBOL data files to and from XML using copybook definitions as the schema, with both command-line and JVM library interfaces. *COBOL relevance: Facilitates integration of COBOL data stores with XML-based enterprise systems and web services.*

## SQL

[GNUCobolSQLServer](https://github.com/dwulkan/GNUCobolSQLServer) — A reference project demonstrating how to compile GnuCOBOL programs on Windows 11 that connect to and execute queries against Microsoft SQL Server databases. *COBOL relevance: Provides setup instructions and working sample code for developers integrating GnuCOBOL applications with SQL Server, a common enterprise database.*

[dsc-gnu-GixSQL](https://github.com/dscobol/dsc-gnu-GixSQL) — Example programs showing how to build GnuCOBOL applications that interact with PostgreSQL databases using the GixSQL embedded SQL precompiler. *COBOL relevance: Demonstrates the use of embedded SQL (EXEC SQL) syntax in GnuCOBOL for connecting to open-source relational databases, a standard pattern in mainframe COBOL ported to open systems.*

[dbpre](https://sourceforge.net/projects/dbpre/) — An SQL preprocessor for GnuCOBOL and MySQL that transforms embedded SQL statements in COBOL source into compilable GnuCOBOL code. *COBOL relevance: Enables GnuCOBOL programs to interact directly with MySQL databases using native embedded SQL syntax without manual CALL boilerplate.*

## FFI / Interop

[Copybook to XML (cb2xml)](https://sourceforge.net/projects/cb2xml/) — A Java-based utility that converts COBOL copybooks into XML documents and corresponding Java objects, bridging legacy data structure definitions to modern formats. *COBOL relevance: Enables integration of COBOL copybook layouts with Java or XML-based systems without rewriting the original data definitions.*

[record-editor](https://sourceforge.net/projects/record-editor/) — A data file editor for flat files (fixed-width, delimited, and binary) including mainframe COBOL files, with support for file comparison, reformatting, and format analysis. *COBOL relevance: Lets developers inspect and edit raw COBOL data files — including EBCDIC and packed-decimal binary formats — without a mainframe.*

[cobxref](https://sourceforge.net/projects/cobxref/) — A static analysis tool that parses COBOL source code and produces cross-reference reports showing where every variable, procedure, and section is defined and referenced, flagging dead code along the way. *COBOL relevance: Essential for understanding large legacy codebases where data names are reused or copy-pasted across hundreds of programs.*

[acas](https://sourceforge.net/projects/acas/) — An open-source accounting application (Sales, Purchase, and Nominal Ledgers plus inventory) written in GnuCOBOL and designed for small businesses across Linux, Mac, and Windows. *COBOL relevance: A real-world GnuCOBOL application that demonstrates how COBOL handles financial ledger logic on modern open-source toolchains.*

[stingrayreader](https://sourceforge.net/projects/stingrayreader/) — A Python library that provides unified, schema-driven reading of CSV, fixed-format flat files, and COBOL EBCDIC files by parsing COBOL Data Division Entry (DDE) definitions. *COBOL relevance: Allows Python programs to consume COBOL copybook-described files alongside modern formats through a single API.*

[cobol-dde](https://sourceforge.net/projects/cobol-dde/) — A Python library for parsing COBOL copybook Data Division Entry definitions and using them to extract data from COBOL-format files; superseded by the Stingray Reader project. *COBOL relevance: Enables Python-based data pipelines to natively understand COBOL record structures without a mainframe.*

[wsdl2cobol](https://sourceforge.net/projects/wsdl2cobol/) — An Apache Axis add-on that reads WSDL files and generates COBOL copybooks and source code for marshalling and unmarshalling SOAP/XML web service messages. *COBOL relevance: Enables COBOL programs to consume or expose SOAP web services by auto-generating the required XML-handling boilerplate.*

### Java

[jrecord](https://sourceforge.net/projects/jrecord/) — A Java library for reading and writing COBOL data files in fixed-width, mainframe binary, and delimited flat-file formats using record layouts defined in COBOL, CSV, or XML. *COBOL relevance: Provides a Java-side API for consuming COBOL-formatted data files, making it straightforward to build ETL pipelines that bridge mainframe output to JVM applications.*

[cb2java](https://sourceforge.net/projects/cb2java/) — A dynamic COBOL copybook parser for Java that reads copybook definitions and converts COBOL data types and record structures to and from Java objects with built-in validation. *COBOL relevance: Provides Java applications with a runtime bridge to parse and generate COBOL-format records using copybook schemas.*

[layoutparser](https://sourceforge.net/projects/layoutparser/) — A Java library that maps fixed-length and CSV files to Java objects using XML-based layout definitions, targeting integration with legacy positional-data systems such as those produced by COBOL. *COBOL relevance: Lets Java applications read and write the fixed-length record formats that COBOL batch programs typically produce.*

### Node.js

[node-cobol-promises](https://github.com/IonicaBizau/node-cobol-promises) — A Node.js library that lets developers embed and execute COBOL code from within JavaScript using a promise-based async API. *COBOL relevance: Enables gradual modernization by running existing COBOL logic from a Node.js service layer without rewriting the business rules.*

### With R

[rcoboldi](https://github.com/thospfuller/rcoboldi) — An R package that imports COBOL copybook-formatted data files directly into R as properly structured data frames for statistical analysis and transformation. *COBOL relevance: Allows data scientists to consume mainframe COBOL data exports without a manual conversion step, feeding legacy data directly into R workflows.*

### With Go

[Go calling COBOL](https://github.com/swichblade/Go-golang-calls-COBOL-program) — A demonstration project showing how Go code can compile a COBOL program into a static library and invoke it with input data, providing a working interop pattern between the two languages. *COBOL relevance: Provides a concrete, runnable template for shops migrating to Go that need to call existing COBOL modules rather than immediately rewriting them.*

[Sync COBOL Group Item with Go Struct](https://github.com/swichblade/Sync-Cobol-group-item-with-Golang-struct) — A project demonstrating bidirectional data exchange between COBOL group items and Go structs using JSON serialization and a Go shared library called from COBOL. *COBOL relevance: Shows a practical data-mapping strategy for teams that need COBOL programs to share structured records with Go microservices.*

## Modernization

[opensourcecobol4j](https://github.com/opensourcecobol/opensourcecobol4j) — A COBOL-to-Java compiler that translates COBOL source programs into equivalent Java source code so they can run on any JVM platform. *COBOL relevance: Offers a migration path for COBOL shops moving toward Java without a full rewrite, while preserving existing program logic.*

[COBREX-CLI](https://github.com/rishalab/COBREX-CLI) — A Python CLI tool that builds a Control Flow Graph (CFG) of a COBOL program and extracts its embedded business rules, outputting results in JSON and PDF formats. *COBOL relevance: Automates discovery and documentation of business logic hidden inside legacy COBOL programs, a critical first step in any modernization effort.*

[masquerade-cobol](https://github.com/billybillymc/masquerade-cobol) — An LLM-powered tool that parses legacy COBOL systems, extracts their business logic via static analysis combined with AI, and reimplements them in Python or Java with verified behavioral equivalence. *COBOL relevance: Targets the core challenge of COBOL modernization — understanding what the code actually does — and automates the translation to a target language.*

[opencobol2java](https://sourceforge.net/projects/opencobol2java/) — A pure-Java translator that parses VS COBOL II syntax and generates readable, refactorable Java source code, with support for embedded EXEC SQL statements. *COBOL relevance: Offers an automated migration path from COBOL to Java, producing Java source that developers can further refine in an IDE.*

## Games

### Tic Tac Toe

[TicTacTOBOL](https://github.com/ShaunLawrie/TicTacTOBOL) — A terminal Tic Tac Toe game written in COBOL with ASCII graphics and a simple random-move AI opponent. *COBOL relevance: A well-structured beginner project that illustrates COBOL screen I/O, conditional logic, and table handling in a familiar game context.*

[cobol_tictactoe](https://github.com/LivioConzett/cobol_tictactoe) — A straightforward Tic Tac Toe implementation written entirely in OpenCOBOL, covering the full game loop in a single program. *COBOL relevance: Useful as a compact reference for two-player input handling and board-state management in GnuCOBOL.*

### Minesweeper

[COBOL Minesweeper](https://github.com/Truttle1/COBOL-Minesweeper) — A fully playable Minesweeper game implemented in COBOL, demonstrating interactive terminal-based gameplay with the classic mine-revealing mechanics. *COBOL relevance: Showcases COBOL's ability to handle grid data structures, random number generation, and recursive reveal logic.*

[CoinBoller](https://github.com/yujisakata/CoinBoller) — A Minesweeper clone written in COBOL, recreating the classic game's mine-detection and flagging mechanics in a terminal environment. *COBOL relevance: Provides another example of COBOL being used for interactive grid-based programs, useful for studying table manipulation patterns.*

### 3D / Raycasters

[COBOL-CASTER](https://github.com/gyng/COBOL-CASTER) — An educational raycaster that renders a single sphere using ASCII characters, implementing 3D ray-casting fundamentals entirely in COBOL. *COBOL relevance: An unusual demonstration of COBOL's numeric computation capabilities applied to geometry and rendering math.*

[cobol-doom](https://github.com/deios0/cobol-doom) — A Doom 2 MAP01 renderer written in ~8,300 lines of GnuCOBOL with raycasting graphics, enemy AI, weapons, and SDL2 graphics via a minimal C interface. *COBOL relevance: One of the most ambitious COBOL hobby projects available, demonstrating that complex real-time programs with external library bindings are achievable in modern GnuCOBOL.*

### Other

Snake - [snek](https://github.com/lewisjb/snek) — A basic Snake game written in COBOL using the ncurses library for terminal graphics on a 10x10 grid. *COBOL relevance: Illustrates how GnuCOBOL can call C-based terminal libraries like ncurses for real-time keyboard input and screen rendering.*

Tetris - [OpenVMS COBOL Tetris](https://github.com/pikapokec/OpenVMSCobolTetris) — A Tetris implementation written in COBOL targeting the OpenVMS operating system, complete with falling pieces and line-clearing mechanics. *COBOL relevance: Valuable for developers working in OpenVMS COBOL environments, showing how game-loop logic maps to the platform's COBOL dialect.*

Minecraft Server - [CobolCraft](https://github.com/meyfa/CobolCraft) — A fully functional Minecraft server written in GnuCOBOL that supports the latest Minecraft protocol with terrain generation, multiplayer, block placement, crafting, and player persistence. *COBOL relevance: Arguably the most technically impressive proof-of-concept for modern GnuCOBOL, demonstrating network socket programming, binary protocol handling, and complex state management.*

[COBOL Roguelike](https://github.com/shamrice/COBOL-Roguelike) — A work-in-progress tile-based console game built in GnuCOBOL, using a level editor to define stages rather than procedural generation. *COBOL relevance: Explores game engine concepts such as tile maps, entity management, and turn-based input loops in a GnuCOBOL codebase.*

[GnuCOBOL Game of Life](https://github.com/marcel-100/gnucobol-game-of-life) — A GnuCOBOL implementation of Conway's Game of Life supporting various initial patterns via external map files. *COBOL relevance: A classic cellular-automaton exercise that effectively demonstrates COBOL table operations and iteration.*

[SDL COBOL Demo](https://github.com/oshaboy/SDL-COBOL-DEMO) — A minimal demo that draws random colored lines using the SDL2 graphics library called from GnuCOBOL, compilable on Unix-like systems and Cygwin. *COBOL relevance: Shows the mechanics of linking COBOL programs against a C graphics library, a pattern applicable to any FFI integration.*

[Sudoku Solver](https://github.com/COBOL-Erik/Sudoku-Solver-COBOL) — A callable COBOL module that accepts a sudoku string, solves it, and returns the solution along with the number of guesses required. *COBOL relevance: Demonstrates how to structure a reusable COBOL subprogram with a clean call interface — a core pattern in enterprise COBOL development.*

[Merry COBOL](https://github.com/oshaboy/Merry-Cobol) — A festive Christmas tree terminal animation written in GnuCOBOL using the Screen Section for display control. *COBOL relevance: Provides a concise demonstration of GnuCOBOL's Screen Section, an often-overlooked feature for building terminal UIs.*

[Space Incobers](https://github.com/PenguinCabinet/Space-Incobers) — A Space Invaders-style terminal game written entirely in COBOL with keyboard-controlled movement and firing against descending enemies. *COBOL relevance: Demonstrates real-time keyboard handling and moving-object logic in COBOL, pushing the language beyond its batch-processing roots.*

[CYGWIN Hangman Game](https://github.com/jfarrell423/CYGWIN-HANGMAN-GAME) — A two-program Hangman system written in GnuCOBOL for Windows/Cygwin, with a word manager utility and a main game featuring ASCII gallows and multi-round scoring. *COBOL relevance: Shows how to structure a multi-program COBOL application with shared data management on a Windows development environment.*

[pong-cobol](https://github.com/psywave-games/pong-cobol) — A Pong game implementation written in COBOL, recreating the classic two-paddle arcade game in a terminal context. *COBOL relevance: A compact example of real-time game loop design and collision detection logic expressed in COBOL.*

[battleship-cobol](https://github.com/gsteixeira/battleship-cobol) — A terminal-based Battleship game written in COBOL where a player competes against a computer opponent by guessing ship positions on a grid. *COBOL relevance: Illustrates two-dimensional array (table) handling and random AI decision-making in a COBOL program.*

[COBOL-CHESS](https://github.com/AntonBystedt/COBOL-CHESS) — A two-player chess game written in GnuCOBOL with command-line interface, move validation, check/checkmate detection, and game-save support. *COBOL relevance: One of the more feature-complete COBOL game projects, showcasing complex conditional logic and structured data representation.*

[cobol-fun](https://github.com/benjaminc-tech/cobol-fun) — A retro fortune teller application in COBOL that generates daily fortunes, lucky numbers, and astrological signs based on the current date and time. *COBOL relevance: A lighthearted demonstration of COBOL's date/time intrinsic functions and formatted output.*

[touche-cobol](https://github.com/HashDG/touche-cobol) — A simple 2v2 battleship-style game written in GnuCOBOL where two players enter fleet positions and take turns guessing. *COBOL relevance: Shows how to manage alternating player turns and shared game state within a single COBOL program.*

[mastermind (COBOL)](https://github.com/kalucky0/mastermind) — A terminal implementation of the classic Mastermind code-breaking game written in COBOL, fully playable from the command line. *COBOL relevance: Demonstrates input validation, iterative guess evaluation, and string comparison logic using standard COBOL constructs.*

[Pyramid of Ahraxis](https://github.com/playdeezgames/PyramidOfAhraxis) — An interactive fiction game featuring text-based dungeon navigation, inventory management, and room interaction commands. *COBOL relevance: Demonstrates how COBOL can power a parser-driven text adventure, highlighting string parsing and structured data for rooms and items.*

[cobol-adventure-engine](https://github.com/manyone/cobol-adventure-engine) — A text adventure game engine written in COBOL that runs on both modern PCs via GnuCOBOL and vintage IBM OS/360 mainframes, using two flat data files to define game worlds. *COBOL relevance: Uniquely spans six decades of hardware, proving COBOL's portability and showing how the same codebase can run on a 1960s mainframe and a modern workstation.*

## Applications

### Interpreters

BASIC - [cbi](https://github.com/shamrice/cbi) — A proof-of-concept BASIC interpreter written in GnuCOBOL that supports Microsoft QBasic syntax, allowing users to load and execute BASIC source programs. *COBOL relevance: Demonstrates that COBOL can serve as a meta-programming host language, implementing interpreters for other languages entirely in GnuCOBOL.*

LISP - [Cisp](https://github.com/lauryndbrown/Cisp) — A Common Lisp interpreter built in COBOL, featuring custom recursion handling and a logging system to work around COBOL's inherent language limitations. *COBOL relevance: Showcases advanced COBOL techniques for implementing recursive data structures and functional-language semantics inside a traditionally procedural environment.*

Brainfuck - [COBOL-brainfuck](https://github.com/mikebharris/COBOL-brainfuck) — A brainfuck esoteric-language interpreter implemented in GnuCOBOL, humorously combining one of programming's most verbose languages with its most minimalistic counterpart. *COBOL relevance: A fun exercise in parsing and state-machine logic in COBOL, illustrating how even unconventional interpreter tasks are achievable in the language.*

### AI

[perceptronCobol](https://github.com/victorqribeiro/perceptronCobol) — Implements a single-layer perceptron in COBOL to classify the classic Iris dataset, demonstrating machine learning concepts in a legacy language. *COBOL relevance: Shows COBOL developers how fundamental ML building blocks can be constructed natively, relevant to modernizing batch analytics pipelines.*

[cobol-neural-network](https://github.com/PierreRemacle/cobol-neural-network) — A fully-functional two-layer neural network in COBOL that classifies handwritten digits from the MNIST dataset, achieving accuracy comparable to a Python equivalent. *COBOL relevance: Proves that COBOL's numeric processing power is sufficient for real ML inference, offering a bridge path for running AI workloads close to existing mainframe data.*

[cobold-cli](https://github.com/xawt/cobold-cli) — A terminal chatbot written in COBOL 85 that connects to modern large language models, maintains conversation history, and executes tool calls through an agent loop. *COBOL relevance: An eye-opening proof-of-concept that COBOL can integrate with contemporary AI APIs, inspiring ideas for augmenting legacy systems with LLM capabilities.*

[neuralnetwork-cobol](https://github.com/gsteixeira/neuralnetwork-cobol) — Implements a configurable deep neural network in COBOL supporting multiple hidden layers and activation functions including sigmoid and leaky ReLU. *COBOL relevance: Extends the ML-in-COBOL concept to deeper architectures, providing a reference implementation for data scientists exploring mainframe-native AI.*

### Calculators

[cobol-emoji-rpn-calculator](https://github.com/ghuntley/cobol-emoji-rpn-calculator) — An emoji Reverse Polish Notation calculator in COBOL that uses Unicode emoji operators with classic stack-based RPN evaluation. *COBOL relevance: Demonstrates Unicode/UTF-8 handling and stack-oriented arithmetic logic in COBOL, useful for developers modernizing character-encoding support in legacy programs.*

[COBOLCalc](https://github.com/gaessaki/COBOLCalc) — A basic arithmetic calculator application built in MicroFocus COBOL for Visual Studio 2015, performing fundamental operations as a demonstration project. *COBOL relevance: A clean, minimal example of COBOL in a modern IDE environment, useful for developers learning Visual Studio tooling for COBOL.*

[cobcal74](https://github.com/manyone/cobcal74) — A COBOL-74 program that evaluates floating-point arithmetic expressions with proper operator precedence, designed to run on both vintage MVS mainframes (TK4-/Hercules) and modern GnuCOBOL. *COBOL relevance: Valuable for developers working in or migrating from COBOL-74 environments, showing how expression parsing was handled in classic mainframe-era code.*

[cobcalc](https://github.com/manyone/cobcalc) — An algebraic expression evaluator in COBOL that parses and computes infix mathematical expressions, supporting nested parentheses, exponentiation, and functions like SQRT. *COBOL relevance: A practical reference for COBOL developers implementing formula-parsing logic, such as in financial or scientific batch applications.*

### IRC / Discord Bots

[WOPO](https://github.com/qgevans/WOPO) — An IRC bot implemented in COBOL-74, demonstrating that the classic mainframe language can be adapted for real-time internet communication. *COBOL relevance: Highlights COBOL's ability to handle network socket I/O, relevant to developers integrating legacy COBOL services with modern messaging infrastructure.*

[comparse](https://github.com/nicklausw/comparse) — A Discord bot written in GnuCOBOL that parses and evaluates mathematical expressions with arbitrary-precision arithmetic via MPFR, integrated with Discord through the Concord C library. *COBOL relevance: Illustrates how COBOL can call into external C libraries and interact with cloud APIs, a pattern applicable to modernizing mainframe COBOL integrations.*

### Operating System

[cobol-pc86](https://github.com/wxwisiasdf/cobol-pc86) — A bare-metal x86 operating system written primarily in COBOL and C that boots via multiboot without requiring a pre-existing OS. *COBOL relevance: A remarkable systems-programming experiment showing COBOL operating at the lowest level of hardware abstraction, challenging assumptions about the language's domain.*

### Web3 / Crypto

[cobol-bitcoin-miner](https://github.com/Zaneham/cobol-bitcoin-miner) — An April Fools' joke Bitcoin miner implemented in COBOL for IBM mainframes, achieving roughly 100 hashes per second. *COBOL relevance: Humorously demonstrates SHA-256 hashing and low-level bit manipulation in COBOL, concepts that are genuinely useful in security and cryptographic work on mainframes.*

[ipcrypt-cobol](https://github.com/jedisct1/ipcrypt-cobol) — Implements the IPCrypt specification in COBOL, providing cryptographically secure and reversible IP address encryption to protect user privacy while preserving network processing capabilities. *COBOL relevance: Directly applicable to COBOL shops handling PII in network logs, offering a ready-to-use privacy-compliant IP anonymization routine.*

### Password Manager

[COVAULT](https://github.com/Geisshirt/COVAULT) — A proof-of-concept password manager in COBOL that stores encrypted identifier-password pairs in a CSV file, using a master password as the encryption key. *COBOL relevance: Demonstrates credential storage and basic encryption patterns in COBOL, serving as a starting point for developers exploring security-sensitive data handling on legacy platforms.*

### Other

[zECS (Walmart)](https://github.com/walmartlabs/zECS) — A production-grade distributed key/value caching service for z/OS from Walmart Labs, providing high-performance, highly available storage for text or binary content with RESTful access and ACID compliance. *COBOL relevance: A rare, real-world open-source enterprise COBOL codebase from a major retailer, offering valuable patterns for building scalable mainframe microservices.*

[cobol-apps](https://github.com/raphaelfrei/cobol-apps) — A collection of educational COBOL applications including calculators, CSV writers, and validation utilities, built to demonstrate practical language features. *COBOL relevance: A beginner-friendly portfolio of working programs covering common real-world tasks, useful as reference code for developers learning COBOL fundamentals.*

[EnterpriseCOBOLv6.3](https://github.com/cchipman21804/EnterpriseCOBOLv6.3) — A collection of utilities, financial tools, and interactive games written in Enterprise COBOL v6.3 for IBM Z mainframes running z/OS and UNIX System Services, with accompanying JCL. *COBOL relevance: Provides practical, mainframe-specific code samples targeting the latest IBM Enterprise COBOL dialect, valuable for developers on the IBM Z platform.*

[exercism/cobol](https://github.com/exercism/cobol) — The official COBOL track on the Exercism learning platform, providing a curated set of progressively challenging practice exercises with automated test suites for learners. *COBOL relevance: The go-to structured learning path for developers new to COBOL or sharpening their skills, with community mentorship and test-driven feedback.*

PHP / COBOL Web App - [openjensen](https://github.com/debinix/openjensen) — A web application combining a COBOL/PostgreSQL backend with a PHP/CGI frontend, demonstrating embedded SQL and browser-accessible COBOL business logic. *COBOL relevance: A practical reference architecture for exposing COBOL programs as web services, directly relevant to modernization projects that need a web front-end over legacy batch logic.*

[cobol-orbital](https://github.com/moshix/cobol-orbital) — A comprehensive COBOL program performing orbital mechanics calculations including Keplerian elements, Hohmann transfers, perturbation analysis, and orbit propagation. *COBOL relevance: Showcases COBOL's numerical computation capabilities in a scientific context, demonstrating that the language can handle complex floating-point physics far beyond its financial origins.*

[COMOL-1: The COBOL Wavetable Synthesizer](https://github.com/DZeman23/COMOL-1-The-COBOL-Wavetable-Synthesizer) — A highly flexible wavetable synthesizer written entirely in COBOL that emulates the time-variant control system of the Roland JD800 with customizable waveforms and envelopes. *COBOL relevance: An imaginative showcase of COBOL's numeric precision applied to digital signal processing, illustrating the language's versatility beyond business data processing.*

[pomodoro](https://github.com/louischristner/pomodoro) — A multi-language terminal Pomodoro timer project implementing the time-management technique in 16+ programming languages, with COBOL as the largest single-language component. *COBOL relevance: Offers a side-by-side comparison of COBOL syntax against modern languages for the same task, making it a useful reference for developers bridging old and new codebases.*

[cobol-hallmark-generator](https://github.com/manyone/cobol-hallmark-generator) — A COBOL application that generates seasonal romantic drama plots by combining configurable character, setting, and storyline templates for Christmas and Thanksgiving themes. *COBOL relevance: A lighthearted demonstration of COBOL's string templating and data-driven output generation, skills equally applicable to generating reports and form letters in enterprise settings.*

[cob-contacts](https://github.com/arctic-stoat/cob-contacts) — A simple CLI-based contacts list manager written entirely in COBOL, allowing users to store and retrieve contact information from the command line. *COBOL relevance: A clean, minimal CRUD application in COBOL that illustrates indexed file I/O and interactive terminal input — core skills for building real-world data-entry programs.*

[colorbot](https://github.com/PAndaContron/colorbot) — A simple Discord bot written in COBOL that lets users query their assigned color through chat commands. *COBOL relevance: Demonstrates COBOL making HTTP/REST calls to a modern chat platform, a pattern that can be applied to integrating mainframe COBOL services with collaboration tools.*

[InCollege](https://github.com/TramTonne/InCollege) — A COBOL-based simulation of a LinkedIn-style professional networking application featuring user authentication, profile management, job search, and messaging for college students. *COBOL relevance: A feature-rich example of building a multi-module, data-driven COBOL application with user management and relational data structures.*

CLI System info Fetcher for UNIX - [cobfetch](https://github.com/jrrom/cobfetch) — A Linux system information fetcher written in COBOL that displays OS details alongside dinosaur ASCII art, in the style of tools like neofetch. *COBOL relevance: Shows how COBOL can invoke system calls and format rich terminal output on UNIX/Linux, useful for developers running GnuCOBOL in modern cloud or container environments.*

[cobol-filesys](https://github.com/Lasokki/cobol-filesys) — A naive emulation of a terminal and filesystem implemented in COBOL, simulating directory traversal and file operations as a toy proof-of-concept. *COBOL relevance: Explores low-level file system concepts from within COBOL, offering insight into how COBOL's native file-handling capabilities map to broader OS abstractions.*

[protocol-depth](https://github.com/Teapot-protocol/protocol-depth) — A sophisticated 100%-COBOL project demonstrating advanced programming concepts including matrix operations, parallel processing, complex sorting algorithms, and Fast Fourier Transform calculations. *COBOL relevance: A strong counter-argument to the notion that COBOL is limited to simple business logic, providing reference implementations of advanced algorithms for performance-critical mainframe workloads.*

## Sample Code

Hotel Management System - [cobol-hotel](https://github.com/Ghostalex07/cobol-hotel) — A fully functional hotel management system written in free-format GnuCOBOL 3.x, comprising 3,067 lines of code with eight modules covering reservations, check-in/check-out, billing, loyalty programs, and executive reporting — all running in a terminal with no external dependencies. *COBOL relevance: A rare end-to-end, real-world application in pure GnuCOBOL that demonstrates complex business logic, data structures, and modular program design patterns directly applicable to enterprise COBOL development.*

Banking Software - [CICS Banking Sample Application (CBSA)](https://github.com/cicsdev/cics-banking-sample-application-cbsa) — An IBM-maintained, comprehensive banking simulation (52.9% COBOL) that integrates CICS, COBOL, BMS, Db2, Java/Liberty, and Spring Boot, offering four distinct UIs including a traditional BMS terminal interface and a modern Carbon React web front-end. *COBOL relevance: Provides a production-quality reference for integrating mainframe COBOL with modern technologies and is an ideal testbed for practicing CICS application development and modernization strategies.*

Insurance Software - [CICS GenApp](https://github.com/cicsdev/cics-genapp) — IBM's General Insurance Application (originally SupportPac CB12), a working COBOL/JCL application on CICS TS for z/OS that manages insurance policy data in Db2 and demonstrates how traditional 3270 green-screen applications can be modernized. *COBOL relevance: A well-documented, intermediate-level reference application that illustrates CICS API usage, Db2 integration, and application modernization patterns directly relevant to mainframe COBOL developers.*

[COBOL Legacy Benchmark Suite](https://github.com/sentientsergio/COBOL-Legacy-Benchmark-Suite) — A production-grade Investment Portfolio Management System in COBOL (96.1%), designed as a benchmark for evaluating how well LLMs can translate complex legacy COBOL into modern languages; it includes batch programs, CICS online transactions, copybooks, VSAM/DB2 schemas, JCL, and full documentation. *COBOL relevance: Offers an unusually rich and realistic codebase covering mainframe patterns — VSAM, CICS, JCL, financial batch processing — making it valuable both as a study reference and as a modernization testing platform.*

[EstesE/COBOL](https://github.com/EstesE/COBOL) — A historical archive of student COBOL programs from Westfield State College coursework (2003–2004), covering a range of introductory and intermediate programming concepts. *COBOL relevance: Provides clean, straightforward academic examples useful for beginners learning COBOL syntax and fundamental programming constructs.*

BarnCamp Attendee Management System - [BAMS](https://github.com/mikebharris/BAMS) — A deliberately retro-styled GNU COBOL console application for managing welcome-desk operations at community events, supporting attendee registration, search, payment tracking, and CSV import/export. *COBOL relevance: A practical, modern application written entirely in COBOL that demonstrates real-world file I/O, function-key navigation, and integration patterns.*

[Power of COBOL](https://github.com/Technology-Hatchery/Power-of-COBOL) — A companion code repository for the book "The Power of COBOL" by Rui Bivar de Oliveira, containing chapter-by-chapter GnuCOBOL examples along with the OpenCOBOL Programmer's Guide. *COBOL relevance: Provides structured, book-driven learning examples compiled and tested with GnuCOBOL, making it a convenient hands-on supplement for anyone working through a COBOL textbook.*

[COBOL and VB on .NET - Apress Source Code](https://github.com/Apress/cobol-VB-on-.net) — The official Apress source code for Chris L. Richardson's 2003 book *COBOL and Visual Basic on .NET*, demonstrating how COBOL integrates into the .NET framework alongside Visual Basic. *COBOL relevance: One of the few available code resources showing COBOL operating within the .NET ecosystem, valuable for developers exploring legacy language interoperability and migration paths.*

[ITP Advanced COBOL Final Project](https://github.com/jnicholson/ITP-Advanced-COBOL-FINAL) — A 100%-COBOL repository representing the final project submission of an advanced COBOL intensive training program, containing a substantial workspace of programs accumulated over 155 commits. *COBOL relevance: Offers a concrete example of advanced coursework-level COBOL programming, useful as a reference for the scope and complexity expected at an intermediate-to-advanced training level.*

[cygwin-cbl](https://github.com/jfarrell423/cygwin-cbl) — A curated collection of 30+ GNU COBOL programs designed to help developers learn COBOL using GnuCOBOL under the Cygwin environment on Windows, ranging from a classic ELIZA chatbot to games, a phone directory, and a retirement calculator, with companion YouTube tutorials. *COBOL relevance: A practical on-ramp for Windows-based developers to start writing and running COBOL programs immediately, with varied examples illustrating screen I/O, file handling, and logic patterns.*

[Visual COBOL for Java Developers - Book Source](https://github.com/RocketSoftware/visual-cobol-for-java-developers-book) — The official Rocket Software sample code for *Visual COBOL: New Application Modernization Tools for the Java Developer*, split 68% COBOL / 29% Java to demonstrate COBOL-Java integration and modernization techniques. *COBOL relevance: Directly targets Java developers transitioning to or integrating with COBOL, providing chapter-aligned code that bridges OOP and legacy COBOL paradigms.*

[entcobol-examples](https://github.com/OlegKunitsyn/entcobol-examples) — An educational repository demonstrating modern Enterprise COBOL development practices on z/OS, including package/library creation, automated unit testing, mocking, CI/CD pipelines via GitHub Actions, and DevOps workflows. *COBOL relevance: Fills a rare niche by showing how professional software engineering practices — modularity, dependency management, CI/CD — apply to z/OS COBOL development.*

[Memory Map GnuCOBOL](https://github.com/JamesBWhite/Memory-Map-GnuCOBOL) — A performance benchmarking project in GnuCOBOL that implements and compares three file-matching strategies — sequential, indexed, and memory-mapped — against datasets of up to 350 million records and 7+ GB files. *COBOL relevance: Provides concrete, runnable performance comparisons for large-scale file processing techniques central to batch COBOL development.*

[COBOL 68 Mainframe Projects](https://github.com/PaulVH53/cobol68-mainframe-projects) — An educational repository providing a guided learning path for COBOL 68 programming on a simulated IBM mainframe using the MVS-TK5 distribution and the Hercules emulator, with six example programs. *COBOL relevance: Offers a rare, hands-on environment for learning or revisiting classic COBOL 68 on authentic mainframe tooling without requiring access to physical z/OS infrastructure.*

[dsc-gnu-Indexed](https://github.com/dscobol/dsc-gnu-Indexed) — A focused GnuCOBOL repository demonstrating CRUD operations on indexed files under GNU/Linux, drawing explicit parallels to mainframe COBOL/VSAM programming patterns. *COBOL relevance: Serves as a concise, practical bridge for developers learning how GnuCOBOL indexed file handling maps to mainframe VSAM concepts.*

## Learning Resources

[Rocket Software - Learn COBOL in 1 Day Course](https://www.rocketsoftware.com/en-us/learn-cobol) — Rocket Software's free introductory COBOL course, intended to get developers up and running with COBOL basics in a single day. *(HTTP 403; description inferred from context.)* *COBOL relevance: Rocket Software is a major enterprise COBOL vendor, making their introductory course a practical starting point for developers entering the mainframe ecosystem.*

[Open Mainframe Project - COBOL Programming Course](https://openmainframeproject.org/projects/cobol-programming-course/) — An open-source initiative under the Linux Foundation's Open Mainframe Project that offers free COBOL educational materials and hands-on labs using Visual Studio Code, with real-world enterprise examples drawn from financial and government systems. *COBOL relevance: The course covers modern tooling alongside the language itself, bridging classic COBOL with contemporary developer workflows.*

[COBOL on Exercism](https://exercism.org/tracks/cobol) — Exercism's COBOL track provides 46 coding exercises with automated feedback and access to volunteer mentors, offering a structured, practice-driven path to COBOL fluency. *COBOL relevance: Hands-on coding exercises with mentor review are one of the most effective ways to build real COBOL programming skill.*

[COBOL Tutorial on GeeksForGeeks](https://www.geeksforgeeks.org/cobol/what-is-cobolcommon-business-oriented-language/) — A comprehensive introductory article covering COBOL's history since 1959, its English-like syntax, the four mandatory program divisions, and its continued dominance in business transaction processing. *COBOL relevance: A solid reference for understanding the foundational concepts and structure of the language before diving into code.*

[Jay Moseley COBOL Site](https://www.jaymoseley.com/programming/cobol.htm) — A curated personal resource page featuring book recommendations alongside links to online tutorials, reference materials, and programming tools, with an emphasis on COBOL's continued relevance in modern software. *COBOL relevance: A long-standing community reference that aggregates books and tools useful throughout a COBOL developer's career.*

[Michael Coughlan's COBOL Course](https://bushidocodes.github.io/limerick-cobol/) (resurrected) — A mirrored version of Michael Coughlan's comprehensive COBOL learning platform from the University of Limerick, offering tutorials, lectures, exercises, examples, and reference documentation in one place. *COBOL relevance: Coughlan is also the author of the Apress book "Beginning COBOL for Programmers," making this site a well-regarded academic introduction to the language.*

[William M. Klein's COBOL FAQ](https://bushidocodes.github.io/klein-cobol-faq/) (resurrected) — A mirrored, comprehensive FAQ originally authored by William M. Klein (last updated 2005) covering compiler sources, commercial vendors, books, development tools, language standards, and practical questions from beginners and experienced practitioners. *COBOL relevance: Despite its age, this FAQ remains a valuable historical and practical reference for understanding the COBOL ecosystem.*

[Kasten COBOL Page](https://web.archive.org/web/20101216080513/http://home.swbell.net/mck9/cobol/cobol.html) (archived) — A Wayback Machine archive of a personal COBOL reference site. *(Archived page; description inferred from context.)* *COBOL relevance: Archived community reference pages like this often preserve tips, code snippets, and links from the pre-GitHub era of COBOL development.*

[Beginning COBOL for Programmers - Apress Source Code](https://github.com/Apress/beg-cobol-for-programmers) — The official companion GitHub repository for Michael Coughlan's *Beginning COBOL for Programmers* (Apress, 2014), organized chapter-by-chapter with all source code examples from the book. *COBOL relevance: Provides runnable code to accompany one of the most widely recommended modern COBOL textbooks.*

[COBOL Examples](https://github.com/shamrice/COBOL-Examples) — A collection of standalone COBOL example programs written using GnuCOBOL on Linux, covering a broad range of topics including JSON/XML generation, sorting algorithms, and database operations. *COBOL relevance: A practical, copy-and-study reference for common programming patterns in modern open-source COBOL.*

[cobol-course](https://github.com/tanto259/cobol-course) — Workshop programs developed during IBM instructor Jonathan Sayles's "Enterprise COBOL for Business Application Programming" course, written in Enterprise COBOL 6 on IBM z/OS 2.4. *COBOL relevance: Offers real course materials targeting IBM's Enterprise COBOL, the most widely deployed COBOL compiler in production mainframe environments.*

[COBOL Fundamentals Training (Rocket Software)](https://github.com/RocketSoftware/cobol-fundamentals-training) — Free, instructor-led video course materials from Rocket Software teaching COBOL fundamentals and Rocket COBOL tooling, with sample programs designed for use with the Learn COBOL VS Code extension. *COBOL relevance: Directly ties language fundamentals to vendor tooling, making it immediately applicable for developers working in Rocket Software environments.*

[lucapiccinelli/array](https://github.com/lucapiccinelli/array) — A COBOL implementation of dynamic arrays for the Acu COBOL dialect, created to fill the gap where most COBOL implementations lack built-in support for dynamically sized data structures. *COBOL relevance: Demonstrates how to extend COBOL with modern data structure patterns, useful for developers who need flexible collections in business logic.*

[COBOL Programming with VSCode - IBM (Coursera)](https://www.coursera.org/learn/cobol-programming-vscode) — An IBM-authored Coursera course teaching Enterprise COBOL using Visual Studio Code, covering program structure, data manipulation, file handling, debugging, compilation, and CI/CD integration through hands-on labs. *COBOL relevance: Bridges traditional mainframe COBOL development with modern IDE workflows, making the language more accessible to contemporary developers.*

[IBM z/OS Mainframe Practitioner (Coursera)](https://www.coursera.org/professional-certificates/ibm-z-mainframe) — A three-course IBM professional certificate on Coursera covering enterprise computing fundamentals, z/OS system administration, and basic system programming, with hands-on labs on actual IBM Z servers. *COBOL relevance: COBOL runs almost exclusively on z/OS mainframes in enterprise settings, so understanding the platform is essential for any serious COBOL practitioner.*

[Mainframe: The Complete COBOL Course From Beginner To Expert (Udemy)](https://www.udemy.com/course/mainframe-the-complete-cobol-course-from-beginner-to-expert/) — A comprehensive Udemy course taking learners from COBOL basics through advanced mainframe programming topics. *(HTTP 403; description inferred from title.)* *COBOL relevance: A frequently purchased Udemy course aimed at building end-to-end COBOL and mainframe skills suitable for enterprise employment.*

[Introduction to COBOL (Udemy)](https://www.udemy.com/course/cobol-course/) — An introductory Udemy course covering the fundamentals of COBOL programming. *(HTTP 403; description inferred from title.)* *COBOL relevance: Entry-level COBOL courses on Udemy are widely used by self-taught developers breaking into legacy system maintenance roles.*

[Learn COBOL Super Fast - Fundamentals In Under 2 Hours (Udemy)](https://www.udemy.com/course/learn-cobol-super-fast/) — A fast-track Udemy course aimed at covering core COBOL fundamentals in under two hours. *(HTTP 403; description inferred from title.)* *COBOL relevance: A concise crash course for developers who need a quick working understanding of COBOL syntax before diving into a legacy codebase.*

[Mainframe - COBOL DB2 - Basic to Advance Level (Udemy)](https://www.udemy.com/course/mainframe-cobol-db2-basic-to-advance-level/) — A Udemy course covering COBOL alongside DB2 (IBM's relational database), from basic to advanced topics. *(HTTP 403; description inferred from title.)* *COBOL relevance: DB2 is the primary database technology used alongside COBOL in mainframe applications, making combined COBOL/DB2 training essential for enterprise developers.*

[Learn Introductory Programming With COBOL (Udemy)](https://www.udemy.com/course/learn-introductory-programming-with-cobol/) — A beginner-oriented Udemy course using COBOL as a vehicle for teaching introductory programming concepts. *(HTTP 403; description inferred from title.)* *COBOL relevance: Suitable for complete beginners who want to learn programming fundamentals while simultaneously gaining a marketable legacy-language skill.*

[COBOL Training Courses (NobleProg)](https://www.nobleprog.com/cc/cobolprogram) — NobleProg's catalog of instructor-led and online corporate COBOL training courses. *(Page returned 404.)* *COBOL relevance: Corporate training providers serve organizations that need to upskill teams on COBOL for enterprise modernization projects.*

[COBOL Online Training Courses (LinkedIn Learning)](https://www.linkedin.com/learning/topics/cobol) — The LinkedIn Learning COBOL topic page aggregating over 100 results including courses on COBOL Essential Training and Migrating COBOL Apps, targeting mainframe and finance-sector developers. *COBOL relevance: LinkedIn Learning's catalog is widely used for professional development, and the COBOL content covers both learning and modernization.*

[Learning COBOL - Introduction to COBOL (LinkedIn Learning)](https://www.linkedin.com/learning/cobol-essential-training) — A LinkedIn Learning course teaching COBOL programming fundamentals, emphasizing that organizations pay a premium for developers who can maintain and update existing COBOL code in banking, government, and critical operations. *COBOL relevance: Provides a structured, self-paced curriculum suited for professionals looking to add COBOL to their skill set for career advancement.*

[Code Quality and Code Security for COBOL (SonarSource)](https://www.sonarsource.com/knowledge/languages/cobol/) — A SonarQube resource page describing deep static code analysis for mainframe development that identifies bugs, code smells, and security vulnerabilities in COBOL and JCL, with CI/CD pipeline integration support. *COBOL relevance: Static analysis is critical for maintaining quality and security in large, long-lived COBOL codebases that often lack modern testing infrastructure.*

[Beginner's Guide to SDL2 in COBOL](https://github.com/ProgrammingRainbow/Beginners-Guide-to-SDL2-in-COBOL) — A GitHub repository containing a nine-part video tutorial series with accompanying source code for using the SDL2 graphics library in COBOL, demonstrating graphical application development in the language. *COBOL relevance: Proves that COBOL can be used beyond batch processing and business logic, appealing to developers curious about its broader capabilities.*

## Learning Exercises

[COBOL katas](https://github.com/mikebharris/COBOL-katas) — A GitHub repository containing twelve classic programming katas (FizzBuzz, Roman numerals, Mars Rover, Conway's Game of Life, and more) implemented as complete solutions in GnuCOBOL. *COBOL relevance: Kata-style practice with well-known problems is an effective way to build COBOL fluency and reinforce algorithmic thinking in the language.*

## Reference & Background

[What is a mainframe?](https://www.ibm.com/think/topics/mainframe) — IBM's explainer article covering what mainframe computers are, their architecture, capabilities, and why they remain central to enterprise computing. *(HTTP 403; description inferred from context.)* *COBOL relevance: Mainframes are the primary runtime environment for the vast majority of production COBOL code, making this essential background for any COBOL developer.*

[What is COBOL?](https://www.ibm.com/think/topics/cobol) — IBM's introductory overview of the COBOL language — its history, design goals, and continued role in banking, government, and insurance systems. *(HTTP 403; description inferred from context.)* *COBOL relevance: A concise, authoritative starting point for anyone new to the language or needing to explain it to colleagues.*

[COBOL 65th Anniversary Guest Book](https://elnion.com/wp-content/uploads/2024/09/COBOL65_guest_book-by-Derek-Britton.pdf) — A commemorative PDF guest book compiled by Derek Britton celebrating 65 years of COBOL, collecting tributes and reflections from practitioners across the industry. *COBOL relevance: Provides historical perspective and community voices that illustrate COBOL's enduring impact and the people behind it.*

[CBT Tape](https://www.cbttape.org/) — A long-running freeware repository of MVS/z/OS systems programming materials, offering hundreds of utility programs, tools, documentation, and archived content for mainframe operating systems. *COBOL relevance: Many tape files contain COBOL utilities, sample programs, and productivity tools directly usable on z/OS systems.*

[GnuCOBOL Community Site](https://gnucobol.altervista.org/) — A community meeting point for GnuCOBOL users and enthusiasts, offering documentation, resources, debuggers, and web framework integrations for the open-source COBOL compiler. *COBOL relevance: Serves as a hub for developers using the most popular free COBOL compiler, with practical tools and community discussion.*

[GnuCOBOL FAQ](https://gnucobol.sourceforge.io/faq/index.html) — A comprehensive FAQ and how-to guide for GnuCOBOL, covering standards from COBOL-85 through COBOL-2014. *COBOL relevance: The definitive first stop for questions about installing, configuring, and using GnuCOBOL on modern platforms.*

[GNU COBOL 2.0 Programmer's Guide (PDF)](https://gnucobol.sourceforge.io/guides/GNU%20COBOL%202.0%20Programmers%20Guide.pdf) — A roughly 400-page programmer's reference manual for GnuCOBOL 2.0, covering language syntax, compiler options, and runtime behavior. *COBOL relevance: The primary technical reference for writing and compiling COBOL programs with GnuCOBOL.*

[COBOL on Archive.org](https://archive.org/search?query=cobol&tab=all) — A search results page on the Internet Archive surfacing freely accessible COBOL-related books, manuals, software, and digitized historical materials across all media types. *COBOL relevance: A treasure trove of out-of-print COBOL textbooks, vintage IBM manuals, and historical language specifications no longer available elsewhere.*

[COBOL Portal](https://web.archive.org/web/20100928183310/http://www.cobolportal.com/) (archived) — A 2010 Wayback Machine snapshot of an early COBOL community portal that aggregated news, articles, job listings, and resources for COBOL professionals. *COBOL relevance: A historical snapshot of how the COBOL community organized itself online in the early web era.*

## Community & Forums

[r/COBOL Subreddit](https://www.reddit.com/r/cobol/) — Reddit's COBOL community where developers share questions, news, job postings, humor, and technical discussions about the language. *COBOL relevance: An active, informal space for COBOL developers of all experience levels to seek help and stay current with industry news.*

[comp.lang.cobol via Planet Usenet](https://www.planetusenet.com/groups/comp.lang.cobol) — A web gateway to the classic Usenet newsgroup comp.lang.cobol, one of the oldest forums for COBOL technical discussion. *COBOL relevance: Decades of archived technical Q&A threads offer solutions to obscure COBOL problems that predate modern forums.*

[Open Mainframe Project - COBOL Technical Questions](https://community.openmainframeproject.org/c/cobol-technical-questions/16) — The Open Mainframe Project's dedicated forum category for COBOL technical questions, covering topics from compiler selection and JSON integration to file handling and learning resources. *COBOL relevance: A well-moderated, vendor-neutral space backed by the Linux Foundation where COBOL developers can get authoritative answers.*

[Open Mainframe Project Slack](https://slack.openmainframeproject.org/) — An invite link to the Open Mainframe Project's Slack workspace, which hosts real-time channels for COBOL, z/OS, and related mainframe topics. *COBOL relevance: Enables direct, synchronous communication with other COBOL and mainframe practitioners worldwide.*

[Rocket COBOL Product Forums](https://community.rocketsoftware.com/rocket-cobol-27) — Rocket Software's community forum covering Visual COBOL, ACUCOBOL, Net Express/Server Express, COBOL Analyzer, and RM/COBOL, with over 10,000 technical discussions. *COBOL relevance: The best place to find product-specific answers and workarounds for Rocket/Micro Focus COBOL compiler and toolchain issues.*

[Tek-Tips COBOL Forum](https://www.tek-tips.com/forums/cobol-general-discussion.209/) — A peer-reviewed general discussion forum for COBOL on Tek-Tips, covering mainframe COBOL, iSeries, migration, and compiler tooling. *COBOL relevance: Hosts years of archived COBOL problem-solving threads that are still highly relevant for day-to-day development challenges.*

## Organizations & Vendors

[SHARE User Group](https://www.share.org/) — SHARE is an independent, volunteer-run IT association founded in 1955 that provides education, networking, and industry influence for enterprise and mainframe IT professionals. *COBOL relevance: SHARE conferences and working groups have historically shaped IBM mainframe and COBOL direction, making it a key organization for enterprise COBOL practitioners.*

[COBOLworx](https://www.cobolworx.com/) — A company that develops, maintains, and provides commercial support for free and open-source COBOL compilers, including GCC COBOL and GnuCOBOL. *COBOL relevance: The primary commercial backing behind open-source COBOL tooling, offering enterprise support contracts for organizations that need it.*

## Standards

[Old JTC1/SC22/WG4 - COBOL Site (open-std.org)](https://www.open-std.org/jtc1/sc22/wg4/) — The official website of ISO/IEC JTC1/SC22/WG4, the international standards working group responsible for developing and maintaining COBOL language standards, including approved documents and ongoing projects. *COBOL relevance: The authoritative source for COBOL language specifications, conformance requirements, and the formal standards that implementations must follow.*

[Old JTC1/SC22/WG4 - COBOL Site (cobolstandard.info)](https://web.archive.org/web/20170104085359/http://www.cobolstandard.info/wg4/wg4.html) (archived) — A 2017 Wayback Machine snapshot of an earlier mirror of the WG4 COBOL standards committee website. *COBOL relevance: Preserves older WG4 documentation and standards materials that may no longer be accessible on the live open-std.org site.*

[incits PL22.4 Site](https://web.archive.org/web/20161208153643/http://www.cobolstandard.info/j4/index.htm) (archived) — A 2016 Wayback Machine snapshot of the INCITS PL22.4 committee site, the US national body responsible for COBOL standardization. *COBOL relevance: Documents the US domestic standards process that feeds into the international ISO/IEC COBOL standard.*

[COBOL Standards Website](https://web.archive.org/web/20120915080821/http://www.cobolstandards.com/) (archived) — A 2012 archived snapshot of a website dedicated to COBOL language standards, aggregating information on COBOL-85, COBOL-2002, and related specifications. *COBOL relevance: A historical reference point for understanding how COBOL standardization was communicated to the broader developer community.*

[COBOL Standards Website Brazil](https://web.archive.org/web/20071012131857/http://www.clubecobol.com.br/cobolstandards/) (archived) — A 2007 archived Brazilian COBOL community page covering COBOL standards, hosted by Clube COBOL. *COBOL relevance: Demonstrates the global reach of COBOL standardization efforts and serves as a Portuguese-language reference for Brazilian practitioners.*

## Academic Research

[Remodularization of COBOL programs through Scope and DataFlow Analysis](https://web.archive.org/web/20081219203053/http://www.csis.ul.ie/RsrchPubs/Remodcob.htm) (archived) — A research publication from the University of Limerick presenting techniques for restructuring monolithic COBOL programs using scope analysis and data-flow analysis. *COBOL relevance: Offers academically grounded methods for modernizing and refactoring legacy COBOL codebases.*

[Gerbrand Strap - Cobol Data Flow Restructuring](https://homepages.cwi.nl/~paulk/thesesMasterSoftwareEngineering/GerbrandStap.pdf) (archived) — A master's thesis from CWI examining automated techniques for restructuring COBOL programs through data flow analysis. *COBOL relevance: Provides rigorous software engineering approaches to understanding and transforming complex COBOL data flows, useful for modernization projects.*

[COBOL Research at the Free University in Amsterdam](https://www.cs.vu.nl/Cobol/) (archived) — The VU Amsterdam IT-Management and Software Engineering group's research portal focusing on COBOL modernization, standardization, and grammar engineering through academic and industrial collaboration. *COBOL relevance: One of the most prolific academic research groups on COBOL, producing tools and findings directly applicable to legacy system modernization.*

[What does aspect-oriented programming mean to Cobol?](https://web.archive.org/web/20121221093115/http://homepages.cwi.nl/~ralf/AspectCobol) (archived) — A research page from CWI exploring the application of aspect-oriented programming (AOP) concepts — separation of cross-cutting concerns — to COBOL language design and tooling. *COBOL relevance: Examines whether modern software engineering paradigms like AOP can be applied to COBOL, relevant to teams modernizing large codebases.*

[COBOL grammar Version 0.1.1](https://www.cs.vu.nl/grammarware/cobol/) (archived) — A formal grammar specification for IBM COBOL automatically recovered from IBM's official language reference, defining 252 rules across 226 syntactic categories covering program structure, data definitions, and procedural statements. *COBOL relevance: An invaluable resource for tooling developers building parsers, linters, or static analysis tools that need a machine-readable COBOL grammar.*

## Compilers & Development Tools

[IBM Enterprise COBOL for z/OS Documentation Library](https://www.ibm.com/support/pages/enterprise-cobol-zos-documentation-library) — IBM's official documentation hub for Enterprise COBOL for z/OS, providing links to language reference manuals, migration guides, programming guides, and release notes for all supported versions. *(HTTP 403; description inferred from context.)* *COBOL relevance: The definitive reference for IBM's flagship COBOL compiler, essential for any developer targeting z/OS production systems.*

[cobol-rekt](https://github.com/avishek-sen-gupta/cobol-rekt) — An evolving reverse-engineering toolkit for legacy COBOL code that provides flowchart generation, control flow analysis, and transpilation support, with both deterministic and LLM-augmented analysis capabilities. *COBOL relevance: Directly addresses one of the hardest problems in the COBOL world — understanding and transforming large, undocumented legacy codebases.*

[Net Express / Server Express (Broadcom/Micro Focus)](https://www.microfocus.com/en-us/products/net-express/) (dead) — A legacy Micro Focus product page for Net Express and Server Express, Windows- and Unix-based COBOL development environments. *(Now redirects following Micro Focus acquisition by Broadcom/OpenText.)* *COBOL relevance: These IDEs were widely deployed for off-mainframe COBOL development and many enterprise teams still maintain codebases built with them.*

[COBOL-Sheet](https://github.com/Archive-projects/COBOL-Sheet) — A GitHub repository containing an Excel-formatted COBOL coding sheet designed as a quick-reference cheat sheet for COBOL syntax and structure. *COBOL relevance: A handy desk reference for developers who need a fast reminder of COBOL column layout, reserved words, and common constructs.*

[zCONNEE Wildfire Workshop](https://github.com/ibm-wsc/zCONNEE-Wildfire-Workshop) — Educational workshop materials from IBM's Washington Systems Center for z/OS Connect Enterprise Edition (ZCEE), including presentations, exercises, API specifications, and COBOL source code for building REST APIs on z/OS. *COBOL relevance: Shows hands-on techniques for exposing COBOL programs as modern REST services, a key modernization pattern for mainframe applications.*

## Humor

[Re-Boot Hill](https://web.archive.org/web/20110908081646/http://www.actscorp.com/reboothill.htm) (archived) — A humor page from ACTS Corporation featuring tongue-in-cheek tombstones and epitaphs for retired mainframe technologies and programming languages. *COBOL relevance: Light-hearted industry humor that celebrates — and gently mocks — the longevity of COBOL and its mainframe companions.*

## Other Resources

[COBOL Guide (mikeroyal)](https://github.com/mikeroyal/COBOL-Guide) — A broad community-curated GitHub guide covering COBOL frameworks, libraries, tools, and learning resources aimed at developers of all experience levels. *COBOL relevance: A wide-ranging reference that maps the COBOL ecosystem, useful for discovering tools and resources beyond the standard IBM documentation.*
