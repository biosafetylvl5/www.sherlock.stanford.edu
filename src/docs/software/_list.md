* [`biology`](#biology): cryo-em, neurology
* [`chemistry`](#chemistry): computational chemistry, molecular dynamics
* [`devel`](#devel): build, compiler, data, language, libs, mpi
* [`math`](#math): computational geometry, deep learning, language, numerical analysis, numerical library, statistics
* [`system`](#system): compression, containers, file transfer, language, libs, scm, tools
* [`viz`](#viz): remote display

<small>As of Tuesday, August 22 2017, we provide 118 software packages, in 6 categories, covering 24 fields of science.</small>


### Biology
Field  | Module\ name | Version(s) | URL  | Description
:----- | :----------- | ------: | :--- | :----------
**cryo-em** | `relion` | `2.0.3` | [Website](http://www2.mrc-lmb.cam.ac.uk/relion/index.php/Main_Page) | RELION (for REgularised LIkelihood OptimisatioN, pronounce rely-on) is a stand-alone computer program that employs an empirical Bayesian approach to refinement of (multiple) 3D reconstructions or 2D class averages in electron cryo-microscopy (cryo-EM). 
**neurology** | `afni` | `17.2.07` | [Website](https://afni.nimh.nih.gov) | AFNI (Analysis of Functional NeuroImages) is a set of C programs for processing, analyzing, and displaying functional MRI (FMRI) data - a technique for mapping human brain activity. 
**neurology** | `ants` | `2.1.0` | [Website](https://stnava.github.io/ANTs) | ANTs computes high-dimensional mappings to capture the statistics of brain structure and function. 
**neurology** | `freesurfer` | `6.0.0` | [Website](https://surfer.nmr.mgh.harvard.edu/) | An open source software suite for processing and analyzing (human) brain MRI images. 
**neurology** | `fsl` | `5.0.10` | [Website](https://fsl.fmrib.ox.ac.uk/fsl) | FSL is a comprehensive library of analysis tools for FMRI, MRI and DTI brain imaging data. 
**neurology** | `mrtrix` | `0.3.16` | [Website](http://www.mrtrix.org) | MRtrix3 provides a set of tools to perform various types of diffusion MRI analyses, from various forms of tractography through to next-generation group-level analyses. 
**neurology** | `spm` | `12` | [Website](http://www.fil.ion.ucl.ac.uk/spm/) | The SPM software package has been designed for the analysis of brain imaging data sequences. The sequences can be a series of images from different cohorts, or time-series from the same subject. 

### Chemistry
Field  | Module\ name | Version(s) | URL  | Description
:----- | :----------- | ------: | :--- | :----------
**computational chemistry** | `gaussian` | `g16` | [Website](https://www.gaussian.com) | Gaussian is a general purpose computational chemistry software package. 
**computational chemistry** | `vasp` | `5.4.1` | [Website](https://www.vasp.at) | The Vienna Ab initio Simulation Package (VASP) is a computer program for atomic scale materials modelling, e.g. electronic structure calculations and quantum-mechanical molecular dynamics, from first principles. 
**molecular dynamics** | `gromacs` | `2016.3` | [Website](http://www.gromacs.org) | GROMACS is a versatile package to perform molecular dynamics, i.e. simulate the Newtonian equations of motion for systems with hundreds to millions of particles. 

### Devel
Field  | Module\ name | Version(s) | URL  | Description
:----- | :----------- | ------: | :--- | :----------
**build** | `cmake` | `3.8.1` | [Website](https://www.cmake.org) | CMake is an extensible, open-source system that manages the build process in an operating system and in a compiler-independent manner. 
**build** | `scons` | `2.5.1_py36`<br/>`2.5.1_py27` | [Website](http://www.scons.org) | SCons is an Open Source software construction tool. 
**compiler** | `gcc` | `7.1.0`<br/>`6.3.0` | [Website](http://gcc.gnu.org) | The GNU Compiler Collection includes front ends for C, C++, Fortran, Java, and Go, as well as libraries for these languages (libstdc++, libgcj,...). 
**compiler** | `icc` | `2017.u2` | [Website](https://software.intel.com/en-us/c-compilers) | Intel C++ Compiler, also known as icc or icl, is a group of C and C++ compilers from Intel 
**compiler** | `ifort` | `2017.u2` | [Website](https://software.intel.com/en-us/fortran-compilers) | Intel Fortran Compiler, also known as ifort, is a group of Fortran compilers from Intel 
**compiler** | `llvm` | `4.0.0` | [Website](http://llvm.org) | The LLVM Project is a collection of modular and reusable compiler and toolchain technologies. Clang is an LLVM native C/C++/Objective-C compiler, 
**data** | `h5utils` | `1.12.1` | [Website](http://ab-initio.mit.edu/wiki/index.php/H5utils) | h5utils is a set of utilities for visualization and conversion of scientific data in the free, portable HDF5 format. 
**data** | `hdf5` | `1.10.0p1` | [Website](https://www.hdfgroup.org/hdf5) | HDF5 is a data model, library, and file format for storing and managing data. It supports an unlimited variety of datatypes, and is designed for flexible and efficient I/O and for high volume and complex data. 
**data** | `sqlite` | `3.18.0` | [Website](https://www.sqlite.org) | SQLite is a self-contained, high-reliability, embedded, full-featured, public-domain, SQL database engine. 
**language** | `ant` | `1.10.1` | [Website](http://www.oracle.com/technetwork/java/index.html) | Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented,[14] and specifically designed to have as few implementation dependencies as possible. 
**language** | `cuda` | `8.0.61` | [Website](https://developer.nvidia.com/cuda-toolkit) | CUDA is a parallel computing platform and application programming interface (API) model created by Nvidia. It allows software developers and software engineers to use a CUDA-enabled graphics processing unit (GPU) for general purpose processing. 
**language** | `java` | `1.8.0_131` | [Website](http://www.oracle.com/technetwork/java/index.html) | Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented,[14] and specifically designed to have as few implementation dependencies as possible. 
**language** | `julia` | `0.5.1`<br/>`0.6` | [Website](https://julialang.org) | Julia is a high-level, high-performance dynamic programming language for numerical computing. 
**language** | `perl` | `5.26.0` | [Website](https://www.perl.org) | Perl 5 is a highly capable, feature-rich programming language with over 29 years of development. <br/>[Usage on Sherlock](http://www.sherlock.stanford.edu/docs/software/using/perl)
**language** | `py-ipython` | `6.1.0_py36`<br/>`5.4.1_py27` | [Website](https://ipython.org) | IPython is a command shell for interactive computing in multiple programming languages, originally developed for the Python programming language. 
**language** | `py-jupyter` | `1.0.0_py36`<br/>`1.0.0_py27` | [Website](https://jupyter.org) | Jupyter is a browser-based interactive notebook for programming, mathematics, and data science. It supports a number of languages via plugins. 
**language** | `python` | `3.6.1`<br/>`2.7.13` | [Website](https://www.python.org) | Python is an interpreted, interactive, object-oriented programming language. 
**language** | `ruby` | `2.4.1` | [Website](https://www.ruby-lang.org) | A dynamic, open source programming language with a focus on simplicity and productivity. It has an elegant syntax that is natural to read and easy to write. 
**libs** | `boost` | `1.64.0` | [Website](http://www.boost.org) | Boost is a set of libraries for the C++ programming language that provide support for tasks and structures such as linear algebra, pseudorandom number generation, multithreading, image processing, regular expressions, and unit testing. 
**libs** | `eigen` | `3.3.3` | [Website](http://eigen.tuxfamily.org) | Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms. 
**libs** | `nccl` | `1.3.4`<br/>`2.0.4` | [Website](https://github.com/NVIDIA/nccl) | NCCL (pronounced 'Nickel') is a stand-alone library of standard collective communication routines, such as all-gather, reduce, broadcast, etc., that have been optimized to achieve high bandwidth over PCIe. 
**libs** | `tbb` | `2017.u2` | [Website](https://software.intel.com/en-us/intel-tbb) | Intel® Threading Building Blocks (Intel® TBB) is a widely used C++ library for shared-memory parallel programming and heterogeneous computing (intra-node distributed memory programming). 
**mpi** | `impi` | `2017.u2` | [Website](https://software.intel.com/en-us/intel-mpi-library) | Intel® MPI Library is a multi-fabric message passing library that implements the Message Passing Interface, version 3.1 (MPI-3.1) specification. 
**mpi** | `openmpi` | `2.0.2`<br/>`2.1.1` | [Website](https://www.openmpi.org) | The Open MPI Project is an open source Message Passing Interface implementation that is developed and maintained by a consortium of academic, research, and industry partners. 

### Math
Field  | Module\ name | Version(s) | URL  | Description
:----- | :----------- | ------: | :--- | :----------
**computational geometry** | `cgal` | `4.10` | [Website](http://www.cgal.org) | The Computational Geometry Algorithms Library (CGAL) is a C++ library that aims to provide easy access to efficient and reliable algorithms in computational geometry. 
**deep learning** | `cudnn` | `5.1`<br/>`6.0`<br/>`7.0` | [Website](https://developer.nvidia.com/cudnn) | NVIDIA cuDNN is a GPU-accelerated library of primitives for deep neural networks. 
**deep learning** | `py-tensorflow` | `1.2.1`<br/>`1.3.0` | [Website](https://www.tensorflow.org) | TensorFlow™ is an open source software library for numerical computation using data flow graphs. 
**language** | `py-scipystack` | `1.0_py36`<br/>`1.0_py27` | [Website](https://www.scipy.org) | The SciPy Stack is a collection of open source software for scientific computing in Python. It provides the following packages: numpy, scipy, matplotlib, ipython, jupyter, pandas, sympy and nose. 
**numerical analysis** | `matlab` | `R2017a` | [Website](https://www.mathworks.com/products/matlab.html) | MATLAB (matrix laboratory) is a multi-paradigm numerical computing environment and fourth-generation programming language. 
**numerical library** | `fftw` | `3.3.6` | [Website](http://www.fftw.org/) | The Fastest Fourier Transform in the West (FFTW) is a software library for computing discrete Fourier transforms (DFTs). 
**numerical library** | `gmp` | `6.1.2` | [Website](https://gmplib.org) | GMP is a free library for arbitrary precision arithmetic, operating on signed integers, rational numbers, and floating-point numbers. 
**numerical library** | `gsl` | `1.16`<br/>`2.3` | [Website](https://www.gnu.org/software/gsl) | The GNU Scientific Library (GSL) is a numerical library for C and C++ programmers. The library provides a wide range of mathematical routines such as random number generators, special functions and least-squares fitting. 
**numerical library** | `imkl` | `2017.u2` | [Website](https://software.intel.com/en-us/intel-mkl) | Intel Math Kernel Library (Intel MKL) is a library of optimized math routines for science, engineering, and financial applications. Core math functions include BLAS, LAPACK, ScaLAPACK, sparse solvers, fast Fourier transforms, and vector math.[3] The routines in MKL are hand-optimized specifically for Intel processors 
**numerical library** | `mpfr` | `3.1.5` | [Website](https://www.mpfr.org) | The MPFR library is a C library for multiple-precision floating-point computations with correct rounding. 
**numerical library** | `openblas` | `0.2.19` | [Website](http://www.openblas.net/) | OpenBLAS is an optimized BLAS library 
**statistics** | `R` | `3.4.0` | [Website](http://r-project.org) | R is a free software environment for statistical computing and graphics. 
**statistics** | `stata` | `14`<br/>`15` | [Website](https://www.stata.com) | Stata is a complete, integrated statistical software package that provides everything you need for data analysis, data management, and graphics. 

### System
Field  | Module\ name | Version(s) | URL  | Description
:----- | :----------- | ------: | :--- | :----------
**compression** | `szip` | `2.1.1` | [Website](https://support.hdfgroup.org/doc_resource/SZIP) | Szip compression software, providing lossless compression of scientific data, is an implementation of the extended-Rice lossless compression algorithm. 
**compression** | `xz` | `5.2.3` | [Website](http://tukaani.org/xz/) | XZ Utils is free general-purpose data compression software with a high compression ratio. 
**compression** | `zlib` | `1.2.11` | [Website](http://zlib.net) | zlib is designed to be a free, general-purpose, legally unencumbered -- that is, not covered by any patents -- lossless data-compression library for use on virtually any computer hardware and operating system. 
**containers** | `singularity` | `2.3`<br/>`2.3.1` | [Website](http://singularity.lbl.gov) | Singularity is a container framework that enables users to package entire scientific workflows, software and libraries. 
**file transfer** | `gdrive` | `2.1.0` | [Website](https://github.com/prasmussen/gdrive) | gdrive is a command line utility for interacting with Google Drive. 
**file transfer** | `mpifileutils` | `20170210` | [Website](https://github.com/hpc/mpifileutils) | mpiFileUtils is a suite of MPI-based tools to manage large datasets, which may vary from large directory trees to large files. 
**file transfer** | `rclone` | `1.36` | [Website](https://rclone.org) | Rclone is a command line program to sync files and directories to and from: Google Drive, Amazon S3, Dropbox, Google Cloud Storage, Amazon Drive, Microsoft One Drive, Hubic, Backblaze B2, Yandex Disk, or the local filesystem. 
**language** | `tcltk` | `8.6.6` | [Website](https://www.tcl.tk) | Tcl (Tool Command Language) is a dynamic programming language, suitable for web and desktop applications, networking, administration, testing. Tk is a graphical user interface toolkit. 
**libs** | `atk` | `2.24.0` | [Website](https://developer.gnome.org/atk) | ATK is the Accessibility Toolkit. It provides a set of generic interfaces allowing accessibility technologies such as screen readers to interact with a graphical user interface. 
**libs** | `cairo` | `1.14.10` | [Website](https://www.cairographics.org/) | Cairo is a 2D graphics library with support for multiple output devices. 
**libs** | `cups` | `2.2.4` | [Website](https://www.cups.org/) | CUPS is the standards-based, open source printing system. 
**libs** | `fltk` | `1.3.4` | [Website](http://www.fltk.org) | FLTK (pronounced 'fulltick') is a cross-platform C++ GUI toolkit. 
**libs** | `fontconfig` | `2.12.4` | [Website](https://www.freedesktop.org/wiki/Software/fontconfig) | Fontconfig is a library for configuring and customizing font access. 
**libs** | `freeglut` | `3.0.0` | [Website](http://freeglut.sourceforge.net/) | FreeGLUT is a free-software/open-source alternative to the OpenGL Utility Toolkit (GLUT) library. 
**libs** | `freetype` | `2.8` | [Website](http://freetype.org) | FreeType is a software font engine that is designed to be small, efficient, highly customizable, and portable while capable of producing high-quality output (glyph images). 
**libs** | `gconf` | `2.9.91` | [Website](https://projects.gnome.org/gconf) | GConf is a system for storing application preferences. 
**libs** | `gdk-pixbuf` | `2.36.8` | [Website](https://git.gnome.org/browse/gdk-pixbuf) | The GdkPixbuf library provides facilities for loading images in a variety of file formats. 
**libs** | `glib` | `2.52.3` | [Website](https://wiki.gnome.org/Projects/GLib) | The GLib library provides core non-graphical functionality such as high level data types, Unicode manipulation, and an object and type system to C programs. 
**libs** | `gobject-introspection` | `1.52.1` | [Website](https://wiki.gnome.org/Projects/GObjectIntrospection) | GObject introspection is a middleware layer between C libraries (using GObject) and language bindings. 
**libs** | `gtk+` | `2.24.30`<br/>`3.22.18` | [Website](https://www.gtk.org) | GTK+, or the GIMP Toolkit, is a multi-platform toolkit for creating graphical user interfaces. 
**libs** | `harfbuzz` | `1.4.8` | [Website](https://www.freedesktop.org/wiki/Software/HarfBuzz) | HarfBuzz is an OpenType text shaping engine. 
**libs** | `icu` | `59.1` | [Website](http://site.icu-project.org) | ICU is a set of C/C++ and Java libraries providing Unicode and Globalization support for software applications. 
**libs** | `libepoxy` | `1.4.1` | [Website](https://github.com/anholt/libepoxy) | Epoxy is a library for handling OpenGL function pointer management for you. 
**libs** | `libffi` | `3.2.1` | [Website](http://sourceware.org/libffi) | libffi is a portable Foreign Function Interface library. 
**libs** | `libidl` | `0.8.14` | [Website](https://github.com/GNOME/libIDL) | The libIDL package contains libraries for Interface Definition Language files. This is a specification for defining portable interfaces. 
**libs** | `libjpeg-turbo` | `1.5.1` | [Website](http://www.libjpeg-turbo.org) | libjpeg-turbo is a JPEG image codec that uses SIMD instructions (MMX, SSE2, AVX2, NEON, AltiVec) to accelerate baseline JPEG compression and decompression on x86, x86-64, ARM, and PowerPC systems 
**libs** | `libmng` | `2.0.3` | [Website](http://libmng.sourceforge.net) | THE reference library for reading, displaying, writing and examining Multiple-Image Network Graphics. MNG is the animation extension to the popular PNG image-format. 
**libs** | `libpng` | `1.2.57`<br/>`1.6.29` | [Website](http://libpng.sourceforge.net) | libpng is the official PNG reference library. It supports almost all PNG features, is extensible, and has been extensively tested for over 20 years. 
**libs** | `libressl` | `2.5.3` | [Website](https://www.libressl.org) | LibreSSL is a version of the TLS/crypto stack forked from OpenSSL in 2014, with goals of modernizing the codebase, improving security, and applying best practice development processes. 
**libs** | `libtiff` | `4.0.8` | [Website](http://simplesystems.org/libtiff/) | libtiff provides support for the Tag Image File Format (TIFF), a widely used format for storing image data. 
**libs** | `libxml2` | `2.9.4` | [Website](http://xmlsoft.org/) | Libxml2 is a XML C parser and toolkit. 
**libs** | `mesa` | `17.1.6` | [Website](https://www.mesa3d.org) | Mesa is an open-source implementation of the OpenGL, Vulkan and other specifications. 
**libs** | `ncurses` | `6.0` | [Website](https://www.gnu.org/software/ncurses) | The ncurses (new curses) library is a free software emulation of curses in System V Release 4.0 (SVr4), and more. 
**libs** | `orbit` | `2.14.19` | [Website](https://projects.gnome.org/ORBit2) | ORBit2 is a CORBA 2.4-compliant Object Request Broker (ORB) featuring mature C, C++ and Python bindings. 
**libs** | `pango` | `1.40.10` | [Website](http://www.pango.org) | Pango is a library for laying out and rendering of text, with an emphasis on internationalization. 
**libs** | `pcre` | `8.40` | [Website](http://www.pcre.org/) | The PCRE library is a set of functions that implement regular expression pattern matching using the same syntax and semantics as Perl 5. 
**libs** | `popt` | `1.16` | [Website](http://rpm5.org/files/popt) | Library for parsing command line options. 
**libs** | `py-mako` | `1.0.7` | [Website](http://www.makotemplates.org/) | Mako is a template library written in Python. It provides a familiar, non-XML syntax which compiles into Python modules for maximum performance. 
**scm** | `git` | `2.12.2` | [Website](http://git-scm.com) | Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency. 
**tools** | `curl` | `7.54.0` | [Website](https://curl.haxx.se/) | curl is an open source command line tool and library for transferring data with URL syntax. 
**tools** | `expat` | `2.2.3` | [Website](http://libexpat.github.io) | Expat is a stream-oriented XML parser library written in C. 
**tools** | `motif` | `2.3.7` | [Website](https://motif.ics.com) | Motif is the toolkit for the Common Desktop Environment. 
**tools** | `qt` | `5.9.1` | [Website](https://www.qt.io) | QT is a cross-platform application framework that is used for developing application software that can be run on various software and hardware platforms. 
**tools** | `x11` | `7.7` | [Website](https://www.x.org) | The X.Org project provides an open source implementation of the X Window System. 
**tools** | `xkeyboard-config` | `2.21` | [Website](https://www.freedesktop.org/wiki/Software/XKeyboardConfig/) | The non-arch keyboard configuration database for X Window. 

### Viz
Field  | Module\ name | Version(s) | URL  | Description
:----- | :----------- | ------: | :--- | :----------
**remote display** | `virtualgl` | `2.5.2` | [Website](http://www.virtualgl.org) | VirtualGL is an open source toolkit that gives any Unix or Linux remote display software the ability to run OpenGL applications with full 3D hardware acceleration. 