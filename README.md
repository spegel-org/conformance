# Conformance

This is a modified version of the OCI Distribution Specification [conformance tests](https://github.com/opencontainers/distribution-spec/tree/main/conformance) to be used for conformance tests of [Spegel](https://github.com/spegel-org/spegel).

The tests are modified to implement the proposed [repository namespace query parameter](https://github.com/opencontainers/distribution-spec/pull/66) when pulling images. Spegel depends on this feature to work. The modification is required for the conformance tests to pass. This repository will become archived when the proposal is accepted. 

## License

This project is licensed under the Apache 2.0 License - see the [LICENSE](LICENSE) file for details.