# ms-collect
A series of modules that provide easy storage/accesss to Mass Spec related Raw Data / Groupings of Data.
- Documentation: https://jakuzo.github.io/ms-collect/
- Bug Reports/Feature Requests: https://github.com/jakuzo/ms-collect/issues
- Source Code: https://github.com/jakuzo/ms-collect
- The Why: https://jakuzo.github.io/ms-collect/html/background.html
- Contributing: https://jakuzo.github.io/ms-collect/html/contribute.html

> This package is currently in its BETA phase. Your understanding is greatly appreciated.

## Installation
```sh
pip install ms-collect
```
## Background
In regions of m/z and Retention Time, there exists various signals, features, and collections of data.
This package provides:
- Interfaces to entities that can represent these signals and collections.
- Seamless visual utilities for these entities.
- Input/Output utilities for parsing and organizing MS data.
- Various conversion utilities for MS data.

MS-1 3D Plot             |  MS-1 3D Spectrum
:-------------------------:|:-------------------------:
![3D collection](threeD_collection.png "3D plot of MS-1 Data")  |  ![3D Spectrum](threeD_spectrum.png "3D spectrum plot of MS-1 Data")

![3D collection as spectrum](spectrum.png "Standard Spectrum representation of an MS-1 Collection")
## Usage
For usage examples and Api documentation refer to: https://jakuzo.github.io/ms-collect/

### Upcoming features
- Visual utilities for the various types of collections.
- Optimizations on resource intensive class methods.
- Better import/export and IO related functionality.
- Converting a collection to a dataframe.
- Better Api doc experience.
- If you would like to see something here we are accepting feature requests! Please submit an issue or ping us!
