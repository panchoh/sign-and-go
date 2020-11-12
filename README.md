# Sign-and-Go

**WIP**: Sign-and-Go aims to be a GitHub Action(s) that will enable the secure
generation of signed releases.

# Usage

### Inputs

| Name             | Description                                                              | Default           |
|------------------|--------------------------------------------------------------------------|-------------------|
| revokers-dirpath | Path to the directory that holds the public key of the designed revokers | .github/revokers/ |

### Outputs

| Name           | Description                           |
|----------------|---------------------------------------|
| signing-key-id | Key ID of the just-produced GnuPG key |

## Interface

See [action.yml](action.yml) for the gory details.

# License

The scripts and documentation in this project are released under the [Apache
License 2.0](LICENSE).
