# GCP Login link 
console.cloud.google.com

# TF GCP Site Link
https://registry.terraform.io/providers/hashicorp/google/latest/docs

# Get Started with GCP 
terraform {
  required_providers {
    google = {
      source = "hashicorp/google"
      version = "4.42.1"
    }
  }
}

provider "google" {
  
}
