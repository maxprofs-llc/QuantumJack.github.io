---
layout: post-light-feature
title: MedReader
categories: articles
date: 2020-04-03
image: 
        feature: soft-trees.jpg
---

### Gallery

<figure>
	<img src="https://raw.githubusercontent.com/Joyliu290/MedReader/master/ExampleImg.jpg">
	<figcaption>Example of how to use MedReader</figcaption>
</figure>

## Introduction
- This is a prize-winning hackathon project with our team: me, Anita, Sahana and Joy. We are very proud that InfoSys believed in our idea and chose MedReader to be one of the winners of Most Efficient and Sustainable Energy Hack of Stanford's Treehack2020!

## Inspiration
- To help patients, the elderly population and those with vision impairments and/or reading difficulties better understand and remember their medical and prescription information from both electronic and handwritten documentation.

## What it does
- Our project is a user-friendly, assistive digital tool based on image-to-text and text-to-speech technology to read aloud prescription and medical record information. Users can take a photo or upload a picture of their report/prescription instructions, and the text is converted to an audio recording and played back.

## How I built it
- We integrated machine learning models from Google Cloud Vision API and Cloud Text-to-Speech API to convert images to text data and text data to speech data, respectively. Django was used to build out the back-end logic and integrating the back-end with the front-end.

## Challenges I ran into
- Two main challenges we faced in this project were working with Django to build out the front-end and building a web-based platform that works on the mobile interface.

## Accomplishments that I'm proud of
- We are proud that we learned how to combine multiple Google Cloud machine learning APIs to do image-to-text and text-to-speech extraction. Also, as a group, we didn't have much prior experience in front-end development, so it was a fun learning experience to integrate our final model into a web-based platform.

## What I learned
- We refined our skills in front-end development.

## What's next for MedReader
- Future work would focus on refining detection of specific medical and prescription data related to dosage and usage and exclude all other information on reports or prescriptions. To preserve patient privacy, we will also incorporate functionality to detect and anonymize all personal patient information in a given image at the time of upload. Moreover, we plan to sync the extracted audio recording with the phone calendar to set both audio and text medication reminders for users and add support for multiple languages.

## Built With
- css3
- django
- google-cloud-image-api
- google-cloud-speech-api
- google-cloud-vision-api
- html5
- python

## Try it out
- [Devpost Repo](https://devpost.com/software/medreader)

## Honor
- Stanford TreeHack Most Energy Efficient/Sustainable Energy Hack