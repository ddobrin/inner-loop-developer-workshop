# Create a Repository in Artifact Registry for the lab

A repository can be created easily from the gcloud CLI:
```shell
# generic
# gcloud artifacts repositories create <repo-name> --repository-format=docker --location=<region> --description="Docker repository for multi-layer lab images"

# ex
gcloud artifacts repositories create demo-app \ 
    --repository-format=docker \ 
    --location=us-central1 \ 
    --description="Docker repository for multi-layer images"
```