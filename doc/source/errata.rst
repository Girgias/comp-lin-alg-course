.. default-role:: math

======
Errata
======

Here we'll list all the updates to the exercises and coursework Classroom
repositories for Autumn 2020. An up to date version is in the
`public repository <https://github.com/comp-lin-alg/comp-lin-alg-course>`_.

#. Exercise 1.16. In the description of the exercise, it was intended
   that `C` should be stored in the upper triangular part of `\hat{A}`,
   but the lower triangular part was specified instead. This has been
   fixed now in the notes.
#. Exercise 2.3. There was an error in the parameterisation of the
   test, which is fixed in the public repository.
#. Exercise 2.4. Updated the text to indicate that a copy should be made.
   Replaced ``GS_modified`` `\to`
   ``cla_utils.GS_modified`` in ``test_exercises2.py``.
#. Exercise 2.7. Don't use ``out==`` in ``GS_modified_R`` as this relies
   on structure in the numpy array that may not be the
   same. ``test_GS_modified_R`` has been updated in
   ``test/test_exercises2.py`` (there were previously ``_L`` where
   there shouldn't have been, due to failing to merge a PR fixing
   various things). Finally, we have updated the parameterised `m` and
   `n` values to smaller ones, as this construction for `R` is
   numerically unstable.
#. Exercise 2.10. Added a .conj() to the orthonormality test.
