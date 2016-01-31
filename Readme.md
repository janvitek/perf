# Perf 

A simple tool for repeatedly running Java MapReduce jobs and Java applications for the purpose of coarse-grained performance measurements. 

The tool support three kinds of execution modes: plain (Java on the local machine), local (pseudo distributed MR jobs) and could (EMR jobs).

Arguments are passed to it via the command line and a configuration file. None of this is very general, the tool is tailored to a particular set of assignments.

## Building

Typing 

```mvn clean package```

will create a self-contained JAR file with App.

## Running


