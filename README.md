# Chuanian Converter Backend

This is a basic backend that allows you to convert videos to different formats via ffmpeg.
Hosted on Google Cloud Functions.

## Technologies

- Python
- Google Cloud Functions
- HTML / JavaScript / CSS
- ffmpeg

# Deployment

```
gcloud functions deploy convert-video \
    --runtime python312 \
    --trigger-http \
    --allow-unauthenticated \
    --memory 2048MB \
    --timeout 300s
```