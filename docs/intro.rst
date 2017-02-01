.. Copyright (c) 2017 Thomas Heller

   Distributed under the Boost Software License, Version 1.0. (See accompanying
   file LICENSE_1_0.txt or copy at http://www.boost.org/LICENSE_1_0.txt)

HPX -- CMake Scripts
============================

HPXCMake is a collection of CMake_ scripts to be used for modular HPX_ development.
The goal is to provide a basic set of CMake_ scripts that allow a convenient way
of supporting modular developement of HPX_ based libraries and applications. Its
main goal is to provide a basis for developing HPX_ itself.

The key features are:

 - Specification of dependant modules

:cmake:command:`add_module`
:cmake:variable:`HPX_MODULE_DIR`
:cmake:variable:`variable:CMAKE_BINARY_DIR`
:variable:`CMAKE_BINARY_DIR`

.. _CMake: https://cmake.org/
.. _HPX: http://stellar-group.org/libraries/hpx
