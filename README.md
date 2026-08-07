will add more searching algorithms other than Boyre Moore.

# Tests
- File size: 100MB
- Number of matches: `4'369'066 / 4'369'066`
- System specs: Windows 11, Processor: 12th Gen Intel(R) Core(TM) i5-12500H 2.50 GHz, Installed RAM: 16 GB Speed: 3200 MT/s, Graphics card: 128 MB Intel(R) Iris(R) Xe Graphics
```
hrsh $(LAPTOP-HK58DTQE):~/dev/ssearch/build$🌙 ctest
Test project /home/hrsh/dev/ssearch/build
    Start 1: ssearch_test.searchText
1/4 Test #1: ssearch_test.searchText ...........   Passed    0.00 sec
    Start 2: ssearch_test.threadedSearchText
2/4 Test #2: ssearch_test.threadedSearchText ...   Passed    0.00 sec
    Start 3: ssearch_test.threadedSearchFile
3/4 Test #3: ssearch_test.threadedSearchFile ...   Passed    0.17 sec
    Start 4: ssearch_test.searchFile
4/4 Test #4: ssearch_test.searchFile ...........   Passed    0.40 sec

100% tests passed, 0 tests failed out of 4

Total Test time (real) =   0.58 sec
```
