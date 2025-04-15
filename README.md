### Klepsydra UT coverage

```bash
mkdir build && cd build/
cmake .. -DEIGEN_COVERAGE_TESTING=ON
make -j$(($(nproc)/2)) coverage-html
```

Expect about 40 minutes for UT build and 3 additional hours for running. Then go to the
gcovr [report](build/coverage-html/index.html).

---

**Eigen is a C++ template library for linear algebra: matrices, vectors, numerical solvers, and related algorithms.**

For more information go to http://eigen.tuxfamily.org/.

For ***pull request***, ***bug reports***, and ***feature requests***, go to https://gitlab.com/libeigen/eigen.
