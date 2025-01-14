## 3.2.0.3 (2023-01-18)

Improve pre-commit config (#9563)

- Add a few more hooks. These are all very fast, and I've found them useful in other projects:
  - Autofixes:
    - `trailing-whitespace`: fixes trailing whitespace
    - `requirements-txt-fixer`: alphabetises items in `requirements.txt` files
    - `end-of-file-fixer`: makes sure every file ends with a single newline character
    - `mixed-line-ending`: Makes sure Windows users don't accidentally introduce CRLF line endings into a file that uses LF line endings
  - None-autofixes:
    - `check-yaml`: loads YAML files to validate syntax
    - `check-toml`: loads TOML files to validate syntax
    - `check-merge-conflict`: detects merge-conflict strings in files and blocks them from accidentally being committed
    - `check-case-conflict`: checks for files with names that would conflict on a case-insensitive filesystem like MacOS HFS+ or Windows FAT; blocks them from being committed.
  - Change the bot schedule to quarterly, to reduce noisy PRs
  - Change the `black` language target-version to Python 3.10, synching the setting here with the changes that were made to our `pyproject.toml` file in #7538

## 3.2.0.2 (2023-01-18)

Replace `Any` with `Incomplete` in many places (#9558)

## 3.2.0.1 (2022-11-23)

Mark first argument of `__[get|set|del]attr__` as `str` (#9245)

## 3.2.0 (2022-06-18)

Bump oauthlib to 3.2.* (#8081)

## 3.1.5 (2021-12-28)

Use PEP 585 syntax wherever possible (#6717)

## 3.1.4 (2021-11-18)

Revert "do not use mypy-specific syntax in '# type: ignore' comments" (#6338)

## 3.1.3 (2021-10-12)

Add star to all non-0.1 versions (#6146)

## 3.1.2 (2021-08-29)

do not use mypy-specific syntax in '# type: ignore' comments (#5953)

