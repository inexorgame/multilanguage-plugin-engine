engine
------

`engine` is the driving force behind Inexor :bullettrain_side:

All theoretical work for the [engine](https://github.com/orgs/inexorgame/projects/2) is contained within [linked pad](https://hackmd.io/37sIZedlTTmTbn-maDb4vg?view).

## Next steps

This is a concept repo to implement our architecture as discussed with the pad.
The following tasks shall be completed and added to the [CHANGELOG.md](./CHANGELOG.md)

- [x] create repo
- [ ] create a prototype of a [Trac](https://trac.edgewall.org/wiki/TracDev/ComponentArchitecture)-like system for C++
- [ ] build a plugin loader (plugin) using the above system

## How to compile

- you should have a reasonably recent version of `GCC>=6` or `Clang>=4`
- you should have a reasonably recent version of `CMake`
- `mkdir build && cd build && cmake .. && make`

For the sake of simplicity you can also just do this if you feel like it:

- `c++ Exception.hpp Interface.hpp ExtensionPoint.hpp Component.hpp ComponentManager.hpp`
