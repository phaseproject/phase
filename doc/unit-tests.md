Compiling/running unit tests
------------------------------------

Unit tests will be automatically compiled if dependencies were met in `./configure`
and tests weren't explicitly disabled.

After configuring, they can be run with `make check`.

To run the phased tests manually, launch `src/test/test_phase`.

To add more phased tests, add `BOOST_AUTO_TEST_CASE` functions to the existing
.cpp files in the `test/` directory or add new .cpp files that
implement new BOOST_AUTO_TEST_SUITE sections.

To run the phase-qt tests manually, launch `src/qt/test/test_phase-qt`

To add more phase-qt tests, add them to the `src/qt/test/` directory and
the `src/qt/test/test_main.cpp` file.
