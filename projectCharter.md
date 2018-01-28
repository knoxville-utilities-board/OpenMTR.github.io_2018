---
title: Project Charter
layout: default
permalink: /charter/
---

## Idea Concept
KUB is in the process of converting all meters in their service area to SmartMeters. The deployment is ~500k meters. To ensure accuracy of the meter readings, and therefore customer billing, photos are being taken during each install. Post install, each photo is manually reviewed to verify that the reading manually recorded is the same as the reading in the photo. This project will remove the requirement to manually review each photo, but rather only those photos that fail the automatic review. The project will use OpenCV to do an OCR process of existing meter photos. The OCR’d reading will be compared to the meta data of a meter.


## Minimum Viable Product Guidelines
- Iterate photos and meta data for a given path
- OCR the reading on Gas and Water meters
- Report the level of confidence of processing
- Read meta data of photo
- Report the meters where the manual readings from the meta data is different from the OCR value and where the confidence is greater than threshold variable
- Source Control – Continuous Integration – Static Code Analysis
- Documentation – Github Pages

## Stretch Goals
- OCR Electric dial meters
- Process Azure Storage Path
- API that processes photo URL or photo upload
- A Demo application that demonstrates the application of filters
