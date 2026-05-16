# Change Log

All notable changes to the "elegant-crimson" extension will be documented in this file.

Check [Keep a Changelog](http://keepachangelog.com/) for recommendations on how to structure this file.

## [Unreleased]

- Initial release

## [1.0.7]

- Changed Vue/HTML custom component tag color from golden amber to rose pink (`#FF6382`) for better palette coherence
- Changed string color to soft rose (`#FF8BBC`)
- Added `italic` style to: readwrite variables, CSS selectors, docstrings, and CSS pseudo-classes/elements
- Added `bold italic` style to: inherited class names (`extends`), type/interface declarations, and PHP use aliases

## [1.0.6]

- Added golden amber coloring for unrecognized Vue component tags using dot notation (e.g. `<Disclosure.Button>`, `<Transition.Child>`)
- Added golden amber coloring for PascalCase Vue component tags that share names with native HTML elements (`Button`, `Dialog`, `Form`, `Input`, `Link`, `Menu`, `Progress`, `Table`, `Tbody`, `Td`, `Th`, `Thead`, `Tr`)
