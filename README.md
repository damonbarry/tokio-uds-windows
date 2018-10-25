# tokio-uds-windows

An implementation of Unix Domain Sockets for Tokio on Windows, adapted from the
Unix-only implementation, [tokio-uds].

## Windows support for Unix domain sockets
Support for Unix domain sockets was introduced in Windows 10
[Insider Build 17063][af-unix-preview]. It became generally available in version
1809 (aka the October 2018 Update), and in Windows Server 1809/2019.

[tokio-uds]: https://docs.rs/tokio-uds
[af-unix-preview]: https://blogs.msdn.microsoft.com/commandline/2017/12/19/af_unix-comes-to-windows

## License

This project is licensed under the [MIT license](./LICENSE).
