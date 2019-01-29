# SVPlatform

## What is that?

SVPlatform is a Java 8 application that can be used for secure remote voting for companies. You can think of simple cooperative companies where members want to vote remotely about different topics, with a tool that provide security, integrity and authenticity of the vote. In this same article I also include a Scala version of the same application with a document that summerizes the analysis of the migration from Java to Scala.

## Why?

It was a project for a University exam at first but later I use the SVPlatform case study for the analysis of migrations of Java applications to Scala platform.

## Any technical detail?

The original application is written in Java 8 using Java libraries for security. The security properties of the vote system are granted by combined use of symmetric encryption (with a secret token), asymmetric encryption and hash functions.

The Scala application is identical to the first and comes with a document that analyzes the design choices made to best approach a migration, trying to re-use most of the code and increase code readibility and scalability of the system.

## Links

[At this link](https://drive.google.com/file/d/1atbYJRUKcOI_odxHg5SMueJzpVNfGSBo/view?usp=sharing) you can find source code of the two applications. You have first to configure the application. You can either use Scala version or Java version.
