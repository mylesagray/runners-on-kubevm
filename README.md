# runners-on-kubevm

Running GitHub actions on-prem using self-hosted GitHub runners with the VCF KubeVM Service

## Update the manifests in `/kubevm` with:

### All manifests:
 - `namespace`

### `cloud-init.yaml`:
 - SSH public key
 - GitHub Repo
 - GitHub Runner token (swap for your repo location): https://github.com/mylesagray/runners-on-kubevm/settings/actions/runners/new