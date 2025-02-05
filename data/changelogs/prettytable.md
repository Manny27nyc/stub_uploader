## 3.4.2.4 (2023-01-18)

Replace `Any` with `Incomplete` in many places (#9558)

## 3.4.2.3 (2022-12-28)

Check for unused `pyright: ignore` and differentiate from mypy ignores (#9397)

## 3.4.2.2 (2022-11-23)

Mark first argument of `__[get|set|del]attr__` as `str` (#9245)

## 3.4.2.1 (2022-10-29)

[stubsabot] Mark prettytable as obsolete since 3.5.0 (#9023)

Release: https://pypi.org/pypi/prettytable/3.5.0
Homepage: https://github.com/jazzband/prettytable
Diff: https://github.com/jazzband/prettytable/compare/3.4.1...3.5.0

Co-authored-by: stubsabot <>

## 3.4.2 (2022-09-25)

prettytable: get_X_string return str (#8791)

## 3.4.1 (2022-09-03)

`prettytable`: Fix stubtest errors (#8676)

Fixes #8674. A partial revert of 9e696275018ef3798bb596821ad0d8b4b8e80ab6.

## 3.4.0 (2022-08-29)

Bump prettytable to 3.4.* (#8621)

## 3.3.1 (2022-07-12)

Use error codes for type ignores (#8280)

Disable reportSelfClsParameterName for pytype as this is out of typeshed's
control

Closes: #7497

## 3.3.0 (2022-06-30)

Bump prettytable to 3.3.* (#8207)

Co-authored-by: hauntsaninja <>
Co-authored-by: Alex Waygood <Alex.Waygood@Gmail.com>

## 2.1.3 (2022-06-26)

Check missing definitions for several packages (#8167)

Co-authored-by: hauntsaninja <>

## 2.1.1 (2021-10-12)

Add star to all non-0.1 versions (#6146)

