```shell
root@bc8eb2a37444:/workspaces/hoge# rubocop --disable-pending-cops 
Inspecting 5 files
...C.

Offenses:

sig/bar.rbs:1:1: C: [Correctable] Style/FrozenStringLiteralComment: Missing frozen string literal comment.
class Bar
^

5 files inspected, 1 offense detected, 1 offense autocorrectable
```