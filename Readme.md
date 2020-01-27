# Beam Code with Cloud build

This repo contains beam code from beam example. 
I have added a cloud build file to trigger build.

Replace the service account with your service account and invoke the cloud build.
`export GOOGLE_APPLICATION_CREDENTIALS=<<service_account.json>>`

`$gcloud builds submit --config=build-deploy-dataflowapp.yaml`
