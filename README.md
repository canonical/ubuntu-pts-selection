## Installation

To install the test suite please install phoronix-test-suite and run `phoronix-test-suite list-available-tests` to populate the local directory.
Copy the test suite definition and test profiles to the local directory:
```
cp suite-definition.xml ~/.phoronix-test-suite/test-suites/local/
cp -r test-profiles/* ~/.phoronix-test-suite/test-profiles/
```

## Running

```
phoronix-test-suite strict-benchmark alltests
```
