# Eidolon
Eidolon biomedical visualization and analysis framework.

## Installation

See INSTALLATION.md for details on how to run Eidolon. The code includes precompiled libraries and executables so compilation shouldn't be necessary unless your platform is not supported. Eidolon itself does not need to be installed in any particular location nor require permissions.

To clone the included **EidolonLibs** submodule which contains shared libraries needed to run, use this command within the cloned Eidolon directory:

    git submodule update EidolonLibs
    
Eidolon releases will include pre-built application packages, see the release notes for details.

## Building

For building the Python bindings and Cython libraries, see BUILDING.md.
For building the EidolonLibs objects, see the README.md file in that submodule.

## Documentation

Doxygen Documentation:[![Documentation](https://codedocs.xyz/ericspod/Eidolon.svg)](https://codedocs.xyz/ericspod/Eidolon/)

The wiki https://github.com/ericspod/Eidolon/wiki is the main source of usage documentation. 
Online documentation at runtime for Python code can be seen through the console using the **help** command.

## Authors/Acknowledgements

Eidolon is developed and maintained by Eric Kerfoot, King's College London <eric.kerfoot@kcl.ac.uk>.

If any publications are made with the help of Eidolon it would be appreciated if an acknowledgement is included recognizing the author and KCL.

The main citation for Eidolon:

    @InProceedings{kerfoot2016miar,
      author =    {Kerfoot, E. and Fovargue, L. and Rivolo, S. and Shi, W. and Rueckert, D. and Nordsletten, D. and Lee, J. and Chabiniok, R. and Razavi, R.},
      title =     {Eidolon: Visualization and Computational Framework for Multi-Modal Biomedical Data Analysis},
      booktitle = {LNCS 9805, Medical Imaging and Augmented Reality 2016 (MIAR 2016)},
      year =      {2016},
      journal =   {Lecture Notes in Computer Science},
      volume =    {9805},
      doi =       {10.1007/978-3-319-43775-0},
      url =       {http://www.springer.com/gb/book/9783319437743},
      publisher = {Springer}
    }

## License

Copyright (C) 2016 Eric Kerfoot, King's College London, all rights reserved

This file is part of Eidolon.

Eidolon is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Eidolon is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along
with this program (LICENSE.txt).  If not, see <http://www.gnu.org/licenses/>

## Used/Included Library Copyrights

#### Python

Python is licensed under the Python Software Foundation License.
Copyright (c) 2001, 2002, 2003, 2004, 2005, 2006, 2007, 2008, 2009, 2010, 2011,
2012, 2013, 2014, 2015, 2016 Python Software Foundation.  All rights reserved.

#### PyQt
PyQt is licensed under the GPL version 3.
PyQt is Copyright (C) 2011 Riverbank Computing Limited <info@riverbankcomputing.com>
                                            
#### Ogre

OGRE (www.ogre3d.org) is made available under the MIT License.
Copyright (c) 2000-2015 Torus Knot Software Ltd

#### Cython 

Cython is available under the open source Apache License v2.

#### IRTK

The Image Registration Toolkit was used under Licence from Ixico Ltd. 

The image registration software itself has been written by

Daniel Rueckert

Visual Information Processing Group Department of Computing Imperial College London London SW7 2BZ, United Kingdom

The image processing library used by the registration software has been written by

Daniel Rueckert Julia Schnabel

See the COPYRIGHT file in the IRTK repository at https://github.com/BioMedIA/IRTK for more information on the copyright and license agreement for the software.

#### GPU_Nreg

GPU_Nreg is provided by Dr Wenjia Bai, Imperial College London (http://wp.doc.ic.ac.uk/wbai/).


