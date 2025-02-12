# Changelog
All notable changes to the `pulp` branch of this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## pulp-v0.3.1 - 2023-05-10
### Changed
- Upgrade FPU to pulp-v0.1.1

### Fixed
- Bender.yml: Fix file list for target cv64a6_imafdcsclic_sv39
- cva6_icache_axi_wrapper: Fix negative repetition multiplier for paddr width > AxiAddrWidth
- cva6_clic_controller: Resolve inferred latch by adding default case
- Bender.lock: Update

## pulp-v0.3.0 - 2023-05-03
### Added
- Initial Hypervisor extension (incl. regression tests)

### Changed
- Upgrade AXI to v0.39.0-beta.2

## pulp-v0.2.2 - 2023-04-27
### Fixed
- `Bender.yml`: Specify version for tech_cells_generic
- `Makefile`: Fix vopt for recent questasim versions

## pulp-v0.2.1 - 2023-04-17
### Fixed
- `Bender.yml`: Add cv64a6_imafdcsclic_sv39 target

## pulp-v0.2.0 - 2023-04-08

### Added
- CLIC support

### Fixed
- Verilator 5 compatibility
- `Bender.yml`: Update paths
- Minor tool compatibility issues

## pulp-v0.1.1 - 2023-03-25
### Fixed
- Typo in `Bender.yml`

## pulp-v0.1.0 - 2023-03-24
### Added
- `fence.t` instruction to support timing channel prevention

### Changed
- Bumped `master`
- Updated `Bender.yml`

### Fixed
- Questasim flow
- `icache_axi_wrapper`: Signal widths
