## catatonit ##

A container init that is so simple it's effectively brain-dead. This is a
rewrite of [initrs][initrs] in C, because we found that it is not possible to
statically compile Rust binaries without using musl. That was, in turn, a
reimplementation of other container inits like `tini` and `dumb-init` which
have some concerning implementation details that are non-trivial to just patch
out.

[initrs]: https://github.com/cyphar/initrs

### License ###

catatonit is licensed under the GNU General Public License version 3 or later.

```
catatonit: a container init so simple it's effectively brain-dead
Copyright (C) 2018 SUSE LLC

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
```
