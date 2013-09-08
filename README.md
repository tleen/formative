formative
=========

Form validation utilities for node.js

May not actually need to build this based on what I find, thus far looking like I may.

I like the [express-form](https://github.com/freewil/express-form) library. But for my needs I would need at least two more things:

- Allow custom validators to access other form elements
- Allow custom (all validators really) to proceed async style with callbacks (validating via db query for example)
