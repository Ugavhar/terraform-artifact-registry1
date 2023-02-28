# terraform-artifact-registry1
module "my-repository" {
    source = "./module"
    artifact-config ={
        repository_id = "nodejs-repo"
        location      = "us-central1"

    }
}
This is my module of artifact_registry
