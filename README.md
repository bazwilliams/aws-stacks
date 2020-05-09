# Deploy

```bash
aws cloudformation deploy --template-file=bjw.me.uk.yaml --stack-name=bjw-me-uk
aws cloudformation deploy --template-file=jwilliams.uk.yaml --stack-name=jwilliams-uk
aws cloudformation deploy --template-file=ldvcamper.com.yaml --stack-name=ldvcampervan-website
aws cloudformation deploy --template-file=media.yaml --stack-name=home-media
aws cloudformation deploy --template-file=archive.yaml --stack-name=home-archive
aws cloudformation deploy --template-file=octocam.yaml --stack-name=octocam-footage
```