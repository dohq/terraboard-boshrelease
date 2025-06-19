# terraboard-boshrelease
[terraboard](https://github.com/camptocamp/terraboard)

> 🌍 📋 A web dashboard to inspect Terraform States


## Usage
```
# deploy bosh
bosh deploy -d terraboard terraboard-boshrelease/manifests/terraboard.yml \
  -l terraboard-boshrelease/manifests/version.yml \
  -v access_key_id=<<AWS accesskey>> \
  -v secret_access_key=<<AWS secret accesskey>> \
  -v region=<<S3 region>> \
  -v s3_bucket=<<S3 bucket with terraform.tfstate>>
```
