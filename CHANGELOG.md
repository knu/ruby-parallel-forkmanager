# Parallel::ForkManager Changelog

## 2.0.5 (2015-05-23)

- Adds reap_finished_children, is_child and is_parent to match Perl PFM 1.14.

## 2.0.3 (2015-05-10)

- Start adding tests
- Switch to Rubygems packaging
- Allow use of Rubocop

## 2.0.2 (2015-05-08)

- Fixes bug in garbage collection.

## 2.0.1 (2015-05-07)

- Minor doc fixes.
- Fixes garbage collection.

## 2.0.0 (2015-05-04)

- Refresh to match changes to Perl PFM 1.12.
- May the 4th be with you.

## 1.5.1 (2011-03-04)

- Resolves bug #29043 wait_one_child failed to retrieve object.
- Adds conversion of Object to Hash before serialization to avoid 'singleton can't be dumped' error.
- Minor documentation changes for initialize().

## 1.5.0 (2011-02-25)

- Implements data structure retrieval as had appeared in Perl Parallel::ForkManager 0.7.6.
- Removes support for passing Proc to run_on_* methods; now supports blocks instead.
- Documentation updates and code cleanup.

## 1.2.0 (2010-02-01)

- Resolves bug #27748 finish throws an error when used with start(ident).
- Adds block support to run_on_start(), run_on_wait(), run_on_finish().

## 1.1.1 (2010-01-05)

- Resolves bug with Errno::ECHILD.

## 1.1.0 (2010-01-01)

- Resolves bug [#27661] forkmanager doesn't fork!.
- Adds block support to start() w/doc changes for same.

## 1.0.1 (2009-10-24)

- Resolves bug #27328 dies with max procs 1.

## 1.0.0 (2008-11-03)

- Initial release
