````
gcloud deploy releases create release-1 \
  --project=<PROJECT_ID> \
  --region=europe-north1 \
  --delivery-pipeline=kcc-demo-pipeline

gcloud deploy targets rollback qsprod \
   --delivery-pipeline=kcc-demo-pipeline \
   --release=release-1 \
   --rollout-id=release-1-to-qsprod-0001 \
   --region=europe-north1 \
   --project=<PROJECT_ID>


kubectl delete -f k8s/

kubectl get 
iampolicymember,iamserviceaccount,pubsubtopic,pubsubsubscription,storagebucket,storagebucketaccesscontrol,storagenotification -n 
kcc-deploy

gcloud deploy apply --file clouddeploy.yaml --region=europe-north1 --project=<PROJECT_ID>

gcloud deploy delivery-pipelines delete kcc-demo-pipeline --region europe-north1 --force
````
