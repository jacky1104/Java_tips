# Java_tips
#### These tips about mainly about the tips in daily developments.

**List**
- Not return null as a list, if the return list is an empty list try to use Collections.emptyList instead.

**Thread pool**
- If thread throws exception in thread pool, the exception maybe not recorded in the log correctly, so try...catch clause necessary.
