# valveprotos

a subset of protos for steam and valve games. primarily for use in
[haste](https://github.com/blukai/haste), and in other unrelated projects of
mine that happen to share a need to have access to the same set of protos. 

## feature flags

- `deadlock`: enables deadlock protos.
- `dota2`: enables dota2 protos.
- `gcsdk`: enables game coordinator protos (enabled by `deadlock` and `dota2`).
- `protobuf-src`: enables
[protobuf_src](https://docs.rs/protobuf-src/latest/protobuf_src/) crate which
builds `protoc`.

## scripts

- `graph-imports`: builds a dot graph of imports between protos.
- `fetch-protos`: fetches latest protos from steamdb's
[Protobufs](https://github.com/SteamDatabase/Protobufs) repo.
