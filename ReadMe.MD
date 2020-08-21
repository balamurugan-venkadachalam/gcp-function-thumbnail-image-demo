gcloud functions deploy processThumbImage \
--runtime nodejs10 \
--trigger-resource demo-thumbnail \
--trigger-event google.storage.object.finalize