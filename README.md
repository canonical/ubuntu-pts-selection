## Install test suite and profiles

```bash
$cp -r *.xml ~/.phoronix-test-suite/test-suites/local/
$cp -r test-profiles/* ~/.phoronix-test-suite/test-profiles/
```

## Run the tests

```bash
$phoronix-test-suite strict-benchmark alltests
```

