# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.1.0.3] - 2018-04-05
### Changed
- More accurate `fromNode` on data fields with `Maybe a` type. If there is no such field in Node, data field will be set to Nothing.

## [0.1.0.0] - 2018-02-22
### Added
- Template Haskell code to generate `Node`s and `URelationship`s.
- Simple queries to upload `Node` and `URelationship`.
- Simple query to download `Node`s.
