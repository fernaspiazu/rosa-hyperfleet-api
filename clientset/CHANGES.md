# Changes

## 0.1.1 Oct 09 2026

- ROSAENG-74297: chore: seed CHANGES.md
- chore(clientset): bump version to clientset/v0.1.17
- chore(clientset): bump version to clientset/v0.1.16
- ROSAENG-65114: feat: add IngressConfiguration Signed-off-by: marcolan018 <llan@redhat.com>
- ROSAENG-65293 | chore: Enable custom AWS tags in v2
- test(api): cover labels and replica validation
- feat(nodepool): expose mutable labels and taints
- feat(api): support additional trust bundles
- chore(clientset): bump version to clientset/v0.1.15
- ROSAENG-68168 | feat: add schedulerconfiguration into cluster
- chore(clientset): bump version to clientset/v0.1.14
- chore: pathbind allow list(object) attribute definition in override
- chore: coderabbit review + increase unit coverage
- chore: allow pathbind to bundle fields under keys
- chore(clientset): bump version to clientset/v0.1.13
- ROSAENG-67988: chore: enable proxyconfiguration passthrough fields
- update clientset go mod
- add unit tests
- Add automated versioning and release workflows for api and clientset modules
- ROSAENG-67739 | Expose NodePool fields to SDK/clientset for describe
- ROSAENG-66461 | fix: harden pathbind generation
- ROSAENG-66461 | chore: include passthrough depndency in makefile and update docs
- chore: adjust namespace of children
- poc: intermediate native before terraform types
- feat: Phase 3 - Implement TF mode code generation
- ROSAENG-66461 | chore: modularize pathbind-gen for multi-mode code generation
- ROSAENG-67515 | fix: update channel write-mode from service-set to mutable
- ROSAENG-67262 | feat: scope node pools by cluster
- Rename NumericPtrFields to UnsetPtrFields in pathbind-gen
- Normalize unset *bool pathbind flags before API expand
- ROSAENG-66463 | feat: pathbind engine, code generator and draft-as-source pipeline
- ROSAENG-65615 | feat: allow setting pre-created OIDC config on cluster create
- chore: batch go-openapi v1 dependency updates
- chore: batch Renovate minor/patch dependency updates
- ROSAENG-64871 | fix: review fixes for public types migration
- ROSAENG-64871 | feat: migrate platform-api to v1alpha1/public types
- review: add clientset markers to generate sdk
- [docs-agent] Fix prettier formatting and stale wording across docs
- fix lint: replace deprecated parser.ParseDir, drop always-nil error return, fix ratelimit test timeout
- ROSAENG-62084 | chore: fix gofmt issues in clientset and bridge-gen
- ROSAENG-62084 | fix: address security and doc findings from review
- ROSAENG-62084 | refactor: rename WIRE_ Makefile vars to BRIDGE_, update architecture.md
- ROSAENG-62084 | refactor: rename wire→bridge throughout clientset and api
- ROSAENG-62084 | feat: map cluster_id wire field to NodePool metadata.namespace
- docs: update architecture.md for error translation and nonNamespaced Clusters
- ROSAENG-62084 | fix: translate platform-api error envelopes to metav1.Status
- ROSAENG-62596 | fix: set cluster as non namespaced for client generator
- ROSAENG-64737: switch clientset to use kube-like public types
- ROSAENG-61801: restructure passthrough types into api/v1alpha1
- ROSAENG-64580: move api types from hyperfleet-operator/api to top-level api/
- fix(ROSAENG-62084): harden clientset transport, add unit tests, drop examples
- docs(ROSAENG-62084): update SDK architecture doc to reflect current codebase
- chore(ROSAENG-62084): add test-clientset and verify-clientset targets, fix import ordering in generated wrappers
- refactor(ROSAENG-62084): collapse triple-nested clientset/clientset/clientset into clientset/generated
- test(ROSAENG-62595): add unit tests for SigV4 transport and clientset initialization
- fix(ROSAENG-62084): route Update by UID, add instance profile to nodepool create, fix cluster_id injection
- feat(ROSAENG-62084): add nodepool CRUD examples and platform-specific option types
- chore(ROSAENG-62084): expand fmt/vet/lint targets to clientset and wire-gen; fix misspellings
- feat(ROSAENG-62084): add Watch guard, WaitUntil polling, and cluster lifecycle examples
- chore(ROSAENG-62084): add hyperfleet clientset module with typed client generation


## 0.1.17 Oct 08 2026

- Add create and update path bindings for node pool node labels.
