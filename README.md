# kubeconeu2023-release-tools-example

Sample project that uses [bom](https://github.com/kubernetes-sigs/bom) to generate the SBoms and [tejolote](https://github.com/kubernetes-sigs/tejolote) to generate the intoto attestation for you Go project

Also uses [GoReleaser](https://github.com/goreleaser/goreleaser) to build and push the artifacts to GitHub release and [Cosign](https://github.com/sigstore/cosign) to sign the artifacts.
