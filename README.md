# WRFEval
NCL Toolkit to evaluate WRF performance

The main folder has the following subfolders:

WRFEval/                           # Main directory
- src/                               # Source code
- - WRFEval.ncl                        # Main NCL Script including all necessary references to code.
- - lib/                               # General functions
- - - io/                                # IO Functions
- - - - grid/                              # IO Functions for gridded data (satellite, models, analysis, GIS, etc)
- - - - point/                             # IO Functions for point data (surface stations, buoys, etc)
- - - - profile/                           # IO Functions for profile data (soundings, profilers, etc)
- - - date/                              # Date management functions
- - plot/                              # Plot tools
- - - grid/                              # Plot functions to plot gridded data statistics
- - - point/                             # Plot functions to plot point data statistics
- - - profile/                           # Plot functions to plot profile data statistics
- - stats/                             # Statistics Tools
- - - grid/                              # For Gridded data
- - - point/                             # For point data
- - - profile/                           # For profile data
- data/                              # sample data
- test/                              # just for testing
- specs/                             # technical details on code
- - StatisticSpecs.doc                 # Technical description of statistical functions implemented in codes
- - OtherSpecs.doc                     # Technical description of other tools used in functions
- - DataStandards.doc                  # Technical description of standards for data formats
- - bib/                               # Papers or books for references
- doc/                               # user's guide
- - WRFEval_UsersGuide.doc             # User's Guide

