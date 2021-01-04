# vault-on-gke
Repo for Installing HashiCorp Vault on GKE

GCP GKE Prep Work Needed before Installing HashiCorp Vault on GKE

# Enable GCP API's for GCP Project

gcloud services enable \
    cloudapis.googleapis.com \
    cloudkms.googleapis.com \
    cloudresourcemanager.googleapis.com \
    cloudshell.googleapis.com \
    container.googleapis.com \
    containerregistry.googleapis.com \
    iam.googleapis.com
