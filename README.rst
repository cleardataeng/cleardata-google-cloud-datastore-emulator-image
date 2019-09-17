cleardata-google-cloud-datastore-emulator-image
===============================================

This image runs the Google Cloud Datastore Emulator on port 8081, and
exposes that port.  This allows the emulator to be used as a Gitlab CI
service.  See info at https://docs.gitlab.com/ce/ci/yaml/#services

Environment variables:

- GOOGLE_PROJECT: used to set gcloud's project for the emulator

- DATASTORE_CONSISTENCY: passed to the --consistency parameter of the
  emulator; defaults to 0.9.

