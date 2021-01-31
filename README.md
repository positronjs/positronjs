# PositronJS

In the [issue of Electron about Deno](https://github.com/electron/electron/issues/23613):

> Deno is Rust, which our build system doesn't have support for.

> [...] integrating deno as the JS runtime in Electron instead of node is not possible or wanted at this time. Although that may change in the future my personal opinion is that it won't.

It's possible compile Rust as static or dynamic libraries that could be used from C or C++, and use C libraries from Rust.

Because that, ProtonJS was started.
