## 8.0.0.0 (2022-11-25)

[stubsabot] Bump pyvmomi to 8.0.* (#9271)

Release: https://pypi.org/pypi/pyvmomi/8.0.0.1
Homepage: https://github.com/vmware/pyvmomi
Diff: https://github.com/vmware/pyvmomi/compare/v7.0.3...v8.0.0.1

Stubsabot analysis of the diff between the two releases:
 - 3 public Python files have been added: `pyVmomi/Feature.py`, `pyVmomi/Security.py`, `pyVmomi/VmomiJSONEncoder.py`.
 - 0 files included in typeshed's stubs have been deleted.
 - 1 file included in typeshed's stubs has been modified or renamed: `pyVmomi/__init__.py`.
 - Total lines of Python code added: 6229.
 - Total lines of Python code deleted: 5341.

If stubtest fails for this PR:
- Leave this PR open (as a reminder, and to prevent stubsabot from opening another PR)
- Fix stubtest failures in another PR, then close this PR

Note that you will need to close and re-open the PR in order to trigger CI

Co-authored-by: stubsabot <>

## 7.0.8.2 (2022-10-20)

Remove `pyvmomi` from `pyright`'s exclude (#8943)

## 7.0.8.1 (2022-10-15)

Use `Incomplete` instead of `Any` in `__getattr__` (#8903)

## 7.0.8 (2022-08-04)

Various pyvmomi improvements (#8469)

Co-authored-by: pre-commit-ci[bot] <66853113+pre-commit-ci[bot]@users.noreply.github.com>
Co-authored-by: Alex Waygood <Alex.Waygood@Gmail.com>

## 7.0.7 (2022-04-06)

Update pyVmomi stubs (#7599)

* Add generic base class `DynamicData`
* Add missing `key` prop to `OptionValue`
* Fix `MethodFault` not inheriting from `Exception`
* Fix `RetrieveOptions` default `maxObjects` type and default

## 7.0.6 (2022-03-29)

Add a few classes to vmodl and vmodl.fault (#7565)

## 7.0.5 (2022-03-09)

Remove Python 2 support from some third-party distributions (#7466)

Co-authored-by: Alex Waygood <Alex.Waygood@Gmail.com>

## 7.0.4 (2022-01-31)

Upgrade black version (#7089)

## 7.0.3 (2022-01-08)

Use lowercase `type` everywhere (#6853)

## 7.0.1 (2021-10-12)

Add star to all non-0.1 versions (#6146)

## 7.0.0 (2021-09-19)

Update third-party package versions (#5996)

