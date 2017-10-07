# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]
### Added
- Describe the translation as a fan work, not affiliated to ASCII Corporation
- Part with mini table of contents
- Figure 7.18
- Section 3.1
  - 3.1.1 Memory configuration
  - 3.1.2 I/O Configuration
  - 3.1.3 Built-in and external identifier data
  - 3.1.4 Warning about OPLL direct access
- MSX-MUSIC BASIC Extension
  - Summary
  - Chapter Notation
  - BASIC Extension command list
- BASIC Extension Explained
  - Call AUDREG
  - Call BGM
  - Call MUSIC
  - Call PITCH
  - Call PLAY (1)
    - MML Notation
    - Rhythm MML Specification
    - MML Correspondence
  - Call PLAY (2)
  - Call STOPM
  - Call TEMPER
  - Call TRANSPOSE
  - Call VOICE
    - Tone Library
    - Instrument Parameters Data Format
  - Call VOICE COPY
- Illegal MSX-AUDIO Statements
- FM BIOS
  - Summary
  - FM BIOS Allocation Size
  - FM BIOS Functions
    - WRTOPL (4110H)
    - INIOPL (4113H)
    - MSTART (4116H)
    - MSTOP (4119H)
    - RDDATA (411CH)
    - OPLDRV (411FH)
    - TSTBGM (4122H)
  - FM BIOS Data Structures

### Changed
- Typefont (from computer modern to alegreya)
- Mono Typefont (from computer modern to inconsolata)
- Alegreya to kpfonts
- kpfonts to URW-Garamond (better quality for printing)

### Fixed
- SubSection was not shown on table of contents.
- Index section and subsection typefont formatting.
- Header chapter formatting.

## first commit - 2016-6-23
### Added
- This CHANGELOG file (based completely on [keep-a-changelog])
- CONTRIBUTING file, sugesting a way to help this work
- LICENSE file, as releasing must have its use conditions
- README with some initial basic questions
- Book cover
- Initial book sectioning (index, first chapter) and subsections

[keep-a-changelog]: https://github.com/olivierlacan/keep-a-changelog/blob/master/CHANGELOG.md
