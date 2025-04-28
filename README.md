# go systemd wrapper
Wrapper for executing Go apps with relative paths using systemd.

I had issues creating a simple systemd entry with a recent app I was testing. The app used relative paths so executing outside of the binary's directory resulted in errors. Eventually found a solution by using a .sh wrapper script and also including missing directories from system PATH in the systemd entry.

Modify for your specific use.
