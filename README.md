Steps to reproduce:
1. npm i
2. npm t

Output:


        $ npm t

        > jest-describe@1.0.0 test C:\Test\jest-describe
        > jest

        FAIL test/test.test.ts
          ● Test suite failed to run

            ReferenceError: describe is not defined

            > 1 | describe('Jest', function() {
                | ^
              2 |     it('should work', function() {
              3 |         expect(true).toBe(true);
              4 |     });

              at Object.<anonymous> (test/test.test.ts:1:1)

        Test Suites: 1 failed, 1 total
        Tests:       0 total
        Snapshots:   0 total
        Time:        1.557s
        Ran all test suites.
        npm ERR! Test failed.  See above for more details.
