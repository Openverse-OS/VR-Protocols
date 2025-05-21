# Data Repositories

This checklist is designed to facilitate the sharing of data and code from studies that use VR, ensuring they are accessible to other researchers. The goal is to support replication efforts by providing identical protocols and to enable pooled analyses across multiple datasets. Note that it is important to follow the steps outlined in the interoperability section to share data openly and effectively. This ensures that the shared materials are accessible and usable by other researchers.

---

## Ensuring Rights to Share

- Acquire the rights to share the VR simulation and its assets free of charge to other scholars.
- If the work is collaborative, receive a written agreement from those involved to share the VR simulation and assets publicly.
- Ethics approval for the study establishes which variables from the data collection can be shared publicly without violating participants' privacy.

---

## Uploading Files to Data Repositories

- Upload a readme file that describes the contents of the repository
- Upload the complete VR simulation for other researchers to replicate the study in an identical manner
- Upload VR assets (e.g., individual objects, environments, confederates) for other researchers to recreate and/or repurpose elements of the VR simulation, also if the VR simulation becomes defunct due to new updates.
- Upload VR participant data (e.g., measures of presence) for other researchers to use as a benchmark for their own VR research.

---

## Uploading VR Simulations

- Identify a repository where study materials can be shared openly, free of charge, to someone accessing the materials (e.g., GitHub).
- Upload the VR simulation materials in an accessible format (see section on interoperability).
- If your simulation uses a virtual environment, upload the code to run the program.
- If your simulation uses 360-video, ensure to inject 360-degree metadata (e.g., using Spatial Media Metadata Injector) before uploading the video, and use an MP4 (or equivalent) file format.
- Upload the minimum number of files necessary to directly replicate the study materials, this may include combining multiple files into one before uploading.
- Simplify the operational requirements of the VR simulation such that researchers only need to download the simulation and upload it to the hardware they are using.
- Include a “step-by-step” guide in the repository to walk researchers through the process if otherwise necessary.
- Share the link to the repository in the original communication of the research (e.g., in the methods section and/or data availability statements of the research paper).

---

## Uploading VR Assets

- Share VR assets on platforms that allow researchers to upload licenses and store assets in different file formats, or provide exporters (e.g. Sketchfab), allowing other researchers to access VR assets and use them in their respective engines with the suitable license.

---

## Uploading VR Participant Data

- Confirm that all the data can be shared openly without violating IRB protocols.
- If certain variables from data collection cannot be shared safely, remove them from the dataset before sharing.
- Identify a repository where data be shared openly free of charge to researchers (e.g., Open Science Framework).
- Label each variable in the dataset clearly and/or upload a codebook for researchers to identify variables.
- Upload the primary data in a widely accessible format (e.g., .csv), avoiding software-specific data formats (e.g., .dta or .rds).
- Upload the analysis code in the original data format it was used in (e.g., .rmd); if possible, upload the same analysis code in a plain text format (e.g., using the wiki section in OSF) to make it more accessible. This latter step is essential if the analysis software is behind a paywall (e.g., STATA or SPSS).
- Upload the minimum amount of data files needed to reproduce the results of the study.
- If the data set includes automatic output from the VR hardware that is not immediately relevant to the research question (e.g., head orientation or eye fixation data) include this in a separate file.
- Ensure that a researcher only needs to follow two steps to reproduce the analysis: 1) upload the data into the analysis software, and 2) run the analysis code.
- Share a link to the repository in the methods section of the paper and/or data availability statements.
