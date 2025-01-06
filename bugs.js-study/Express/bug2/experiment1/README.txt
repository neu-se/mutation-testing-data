The files in this directory contain the test results produced by running the following
command:
   node_modules/.bin/_mocha --require test/support/env --reporter json-cov test/ test/acceptance/ 
using Node v20.18.1


  - Bug2-out-fix.json: contains the output produced using the Bug-2-fix version
  - Bug2-out-test.json: contains the output produced using the Bug-2-fix version in which the
    original bug is reintroduced
  - Bug2-out-mutantX.json: contans the output produced using the Bug-2-fix version in which mutant X 
    is applied

Notes:
  - there are multiple test failures that happen in all versions
  - using the Bug-2-test version containing the original bug produces results that are different from those when reintroducing the bug in the Bug-2-fix version, presumably due to unrelated changes elsewhere in the code
