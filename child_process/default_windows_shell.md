
Although Microsoft specifies `%COMSPEC%` must contain the path to
`'cmd.exe'` in the root environment, child processes are not always subject to
the same requirement. Thus, in `child_process` functions where a shell can be
spawned, `'cmd.exe'` is used as a fallback if `process.env.ComSpec` is
unavailable.

[`'error'`]: #child_process_event_error
[`'exit'`]: #child_process_event_exit
[`'message'`]: #child_process_event_message
[`ChildProcess`]: #child_process_child_process
[`Error`]: errors.html#errors_class_error
[`EventEmitter`]: events.html#events_class_eventemitter
[`JSON.stringify` spec]: https://tc39.github.io/ecma262/#sec-json.stringify
[`subprocess.connected`]: #child_process_subprocess_connected
[`subprocess.disconnect()`]: #child_process_subprocess_disconnect
[`subprocess.kill()`]: #child_process_subprocess_kill_signal
[`subprocess.send()`]: #child_process_subprocess_send_message_sendhandle_options_callback
[`subprocess.stderr`]: #child_process_subprocess_stderr
[`subprocess.stdin`]: #child_process_subprocess_stdin
[`subprocess.stdout`]: #child_process_subprocess_stdout
[`child_process.exec()`]: #child_process_child_process_exec_command_options_callback
[`child_process.execFile()`]: #child_process_child_process_execfile_file_args_options_callback
[`child_process.execFileSync()`]: #child_process_child_process_execfilesync_file_args_options
[`child_process.execSync()`]: #child_process_child_process_execsync_command_options
[`child_process.fork()`]: #child_process_child_process_fork_modulepath_args_options
[`child_process.spawn()`]: #child_process_child_process_spawn_command_args_options
[`child_process.spawnSync()`]: #child_process_child_process_spawnsync_command_args_options
[`maxBuffer` and Unicode]: #child_process_maxbuffer_and_unicode
[`net.Server`]: net.html#net_class_net_server
[`net.Socket`]: net.html#net_class_net_socket
[`options.detached`]: #child_process_options_detached
[`process.disconnect()`]: process.html#process_process_disconnect
[`process.env`]: process.html#process_process_env
[`process.execPath`]: process.html#process_process_execpath
[`process.on('disconnect')`]: process.html#process_event_disconnect
[`process.on('message')`]: process.html#process_event_message
[`process.send()`]: process.html#process_process_send_message_sendhandle_options_callback
[`stdio`]: #child_process_options_stdio
[`util.promisify()`]: util.html#util_util_promisify_original
[Default Windows Shell]: #child_process_default_windows_shell
[Shell Requirements]: #child_process_shell_requirements
[synchronous counterparts]: #child_process_synchronous_process_creation
