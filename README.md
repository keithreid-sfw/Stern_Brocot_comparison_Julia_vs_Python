# Stern Brocot comparison Julia vs Python

"""
The MIT License (MIT)

Copyright © 2023 Dr Keith S Reid Cailleach Computing Ltd

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

=#

#=

Python version
Python 3.7.6 (default, Jan  8 2020, 19:59:22) 

[GCC 7.3.0] :: Anaconda, Inc. on linux

Julia Version 1.8.1 (2022-09-06)

Date 18 Feb 2023

Box Spec
OS:         Ubuntu 22.04.1 LTS x86_64
Kernel:     5.15.0-60-generic 
Shell:      bash 5.1.16 
CPU:        AMD Ryzen 9 3900X (24) @ 3.800G 
Memory:     64Gb RAM
                     
Intent:
Implement Stern Brocot in Python and Julia using TDD and nothing too clever
For speed comparison
Roughly simlar logic in the two versions
