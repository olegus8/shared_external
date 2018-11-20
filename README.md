# shared_external

This repository stores additional third party dependencies that may be used selectively in the nvpro-samples.
Compared to code in shared_sources, the libraries here may also come with binaries for windows.

## Third Party

#### AntTweakBar
- http://anttweakbar.sourceforge.net/doc/tools:anttweakbar:download
- if located somewhere else, specify its base directory with ANTTWEAKBAR_LOCATION
- rebuilding it will generate lib and dll in shared_external\AntTweakBar\lib. cmake will look for them here.
  - a compiled version is already provided

````
Copyright (C) 2005-2013 Philippe Decaudin

This software is provided 'as-is', without any express or implied warranty. 
In no event will the authors be held liable for any damages arising from the
use of this software.

Permission is granted to anyone to use this software for any purpose, including
commercial applications, and to alter it and redistribute it freely, subject to
the following restrictions:

1. The origin of this software must not be misrepresented; you must not claim 
that you wrote the original software. If you use this software in a product, 
an acknowledgment in the product documentation would be appreciated but is not 
required.

2. Altered source versions must be plainly marked as such, and must not be 
misrepresented as being the original software.

3. This notice may not be removed or altered from any source distribution.
````

#### d3d12 headers for dxc
- https://github.com/Microsoft/DirectXShaderCompiler/tree/master/include/dxc

#### NSight Tools Extensions
- https://docs.nvidia.com/nsight-visual-studio-edition/Content/NVIDIA_Tools_Extension_Library_NVTX.htm
- if located somewhere else, specify its base directory with NSIGHT_LOCATION


#### OpenCL
- https://www.khronos.org/opencl/resources
- OpenCL 1.2 headers and libraries

#### zlib
- https://github.com/madler/zlib
- This folder contains only the compiled version of zlib.
- It is the result of INSTALL build of this project:
  - bin : the dll/so
  - include : zlib includes
  - lib : library to link with (static or dynamic)
  
````
  Copyright (C) 1995-2012 Jean-loup Gailly and Mark Adler

  This software is provided 'as-is', without any express or implied
  warranty.  In no event will the authors be held liable for any damages
  arising from the use of this software.

  Permission is granted to anyone to use this software for any purpose,
  including commercial applications, and to alter it and redistribute it
  freely, subject to the following restrictions:

  1. The origin of this software must not be misrepresented; you must not
     claim that you wrote the original software. If you use this software
     in a product, an acknowledgment in the product documentation would be
     appreciated but is not required.
  2. Altered source versions must be plainly marked as such, and must not be
     misrepresented as being the original software.
  3. This notice may not be removed or altered from any source distribution.
````

