````
gcloud deploy releases create release-1 \
  --project=gcp-asm-crfa-djq8kx \
  --region=europe-north1 \
  --delivery-pipeline=kcc-demo-pipeline \



gcloud deploy apply --file clouddeploy.yaml --region=europe-north1 --project=gcp-asm-crfa-djq8kx
````
