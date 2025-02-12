CHANGELOG
=========

## HEAD (Unreleased)

## 0.0.8 (2020-12-03)

- Use ephemeral storage for disk mutations.
  [#109](https://github.com/pulumi/pulumi-kubernetes-operator/pull/109)

- Fix handling of `state` message, and add new `lastAttemptedCommit` and `lastSuccessfulCommit` status fields.
  [#107](https://github.com/pulumi/pulumi-kubernetes-operator/pull/107).

- Support configuring alternative `backend`s.
  [#106](https://github.com/pulumi/pulumi-kubernetes-operator/pull/106)

- Support streaming logs from `pulumi up/destroy/refresh`.
  [#101](https://github.com/pulumi/pulumi-kubernetes-operator/pull/101)

## 0.0.7 (2020-09-29)

- Add SSH keyagent, add keys to known_hosts for SSH git.
  [#92](https://github.com/pulumi/pulumi-kubernetes-operator/pull/92)

## 0.0.6 (2020-09-15)

- Refactor controller to use Automation API.
  [#86](https://github.com/pulumi/pulumi-kubernetes-operator/pull/86)

## 0.0.5 (2020-08-11)

- Initial Release!