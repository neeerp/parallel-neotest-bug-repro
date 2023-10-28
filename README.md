# README

This is a minimal reproduction of https://github.com/nvim-neotest/neotest/issues/199

## Steps

1. Create and activate venv
```
python -m venv .venv && . .venv/bin/activate
```

2. Install dependencies
```
pip install -r requirements.txt
```

3. Open neovim, navigate to `tests/test_tests.py`, and use `neotest` to run the
   test. The test should pass but neotest will report it as failing, as in the
   screenshot

![fails](https://github.com/neeerp/parallel-neotest-bug-repro/assets/22756295/b1d02c06-a34a-4ff0-85a3-1a70dcb887a3)
