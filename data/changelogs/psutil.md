## 5.8.3 (2021-09-06)

Improves `psutil/_common.pyi` (#6010)

* Improves `psutil/_common.pyi`

In this iteration I've fixed the most obvious types and corrected several mistakes.
We can go deeper in the next iteration(s).

* We don't need to import `Union`

* Update _common.pyi

* Update _common.pyi

* Update _common.pyi

## 5.8.2 (2021-09-06)

Adds more missing `ContextManager` types (#6007)

1. https://github.com/giampaolo/psutil/blob/c3e63b4dd59f1724a7fa29371e53dfa7f46cbcd3/psutil/_psbsd.py#L571
2. https://github.com/giampaolo/psutil/blob/c3e63b4dd59f1724a7fa29371e53dfa7f46cbcd3/psutil/_psosx.py#L365

## 5.8.1 (2021-09-05)

Fix return type of Process.oneshot() (#6006)
