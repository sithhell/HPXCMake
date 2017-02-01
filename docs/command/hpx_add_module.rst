hpx_add_module
--------------

Add a module

.. code-block:: cmake

    hpx_add_module(<module> <commit>)

Adds the module as a dependency. If the module could not be found in :cmake:variable:`HPX_MODULE_DIR`
it will be fetched form :cmake:variable:`HPX_MODULE_<module>_REPOSITORY` and ``<commit>`` is checked
out. The location of the checkout will be :cmake:variable:`HPX_MODULE_DIR`.
