# on-client
True if running in browserified script, False if running in node

__Deprecated__ Just use `process.browser` ! It's `true` in the [browserify implementation of process](https://github.com/defunctzombie/node-process) and `undefined` in node.