# Changelog

This file contains all the notable changes done to the Ballerina `cdc.schema.aws.s3.driver` package through the releases.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed
- Update the minimum required Ballerina distribution to 2201.14.0 (Swan Lake Update 14) with Java 25 support

## [1.1.1]

### Changed
- Fix the S3 schema history in GraalVM native images by including the AWS SDK `SdkHttpService` service file, which the SDK uses to find its HTTP client.

## [1.1.0]

### Changed
- Upgrade the bundled Debezium S3 schema-history storage to 3.5.1.Final.
