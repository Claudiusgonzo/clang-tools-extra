.. title:: clang-tidy - google-runtime-int

google-runtime-int
==================

Finds uses of ``short``, ``long`` and ``long long`` and suggest replacing them
with ``u?intXX(_t)?``.

The corresponding style guide rule:
https://google.github.io/styleguide/cppguide.html#Integer_Types.

Correspondig cpplint.py check: `runtime/int`.
