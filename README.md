# Usage

### Please copy paste below code 
```
module "release" {
  source  = "ysakova90/release/helm"
  name = "testapplication"
  namespace = "testapp"
  values_yaml = <<EOF
EOF
}
```