# GCP Function Demo
Thumbnail Image processing function

## How to deploy
[x] Create gcp source storage bucket named 'demo-thumbnail'
[x] Create gcp target storage bucket named 'demo-target-thumbnail'
[x] Execute below gcloud command
gcloud functions deploy processThumbImage \
--runtime nodejs10 \
--trigger-resource demo-thumbnail \
--trigger-event google.storage.object.finalize