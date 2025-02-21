# ts-deepscan
TS-DeepScan

# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.3] - 2022-07-06

### Changed Features
    * Fix creation of worker processes on Windows (use "spawn")


## [1.0.2] - 2022-06-14

### Changed Features
    * Fix components key generation

## [1.0.1] - 2022-06-14

### Changed Features
    * Minor fixes


## [1.0.0] - 2022-06-13

### Changed Features
    * Create and upload a module based on the files scan to the TrustSource service
    * Use the root folder license as the license for the module's component
    * Provide separate commands for scanning and uploading results 
    * Add multiprocessing support ("-j N" option to specify number of parallel jobs) 
    * Add license compatibility checks

## [0.6.0] - 2022-06-08

### Changed Features
    * Add files filtering based on unix file name patterns
    * Upload module scans together with files scans to the TrustSource service  
