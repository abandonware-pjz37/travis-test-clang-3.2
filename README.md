Test `clang++-3.2` existance:
* `clang.default` (**failed**: by default no such compiler):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2.png?branch=clang.default)](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2)
* `specify.compiler` (**failed**: try to specify compiler key of `.travis.yml`):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2.png?branch=specify.compiler)](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2)
* `try.install` (**failed**: force update and try to install from default repo):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2.png?branch=try.install)](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2)
* `external.repo` (**passed**):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2.png?branch=external.repo)](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2)
* `cmake.clang-3.2` (**???**: cmake detect clang-3.2):
[![Build Status](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2.png?branch=cmake.clang-3.2)](https://travis-ci.org/travis-ci-tester/travis-test-clang-3.2)
