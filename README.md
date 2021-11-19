# devfest2021 - Private Catalog Demo

This repository contains the source code for the demo session, presented on the devfest2021 event.

## Prerequisites
- Check requirements here: https://cloud.google.com/private-catalog/docs/dm-based-solution

## Configuration
- Select the project on the GCP Cloud Console, where Private Catalog should be located
- Go to the "Private Catalog Admin" page
- Create a new Catalog and share it with project(s), folder(s) or with the whole organization
- Create a new DM-based Solution
- Upload the "devfest-pc-gce-debian-9-dm.jinja" and "devfest-pc-gce-debian-9-dm.jinja.schema" files in a zipped form to the Solution
- Assign the Solution to the Catalog

## Verification
- Select the Project where the Catalog was shared
- Go to the "Private Catalog" page
- Select the Solution and click on "Deploy"
