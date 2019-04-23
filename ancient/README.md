# Odd behavior #1 (ancient)

When no version is provided and `github.com/lightningnetwork/lnd/lnrpc` is used as a dependency, `go mod init` chooses an ancient version: `v0.0.2`.
