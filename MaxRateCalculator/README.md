Max Rate Calculator mod for Factorio
==============================


Provides a selection tool (default hotkey is ctrl-n), which when used to select a set of machines, calculates the maximum
possible rate of items consumed and produced by those machines.   These rates are displayed in a GUI window on the left
side of the Factorio window, in items per second, and items per minute.

# Changelog
### 0.0.1
* Initial release - only handles assemblers, chemical plants, refineries, centrifuges.

### 0.0.2
* Fixed default hotkey (CONTROL-N not CTRL-N).  Fixed en locale strings

### 0.0.3
* Fixed calculation bug when mixed set of modules in an assembler

### 0.1.4
* Calculates production/consumption for furnaces (but not fuel)
* Beacon effectivity no longer hardcoded