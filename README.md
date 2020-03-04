# PDF Toolkit

PDF Toolkit is a tool that I had developed to aid my department in the searching and processing of common PDF files encountered in the day-to-day work life.

This toolkit contains 3 tools:

1. Tenderiser
  - Allows a user to upload multiple PDF files and input the desired search keywords
  - All occurrences of the specified keywords in the uploaded files are then displayed on one screen
2. Factsheet Searcher
  - Extracts the relevant information from a common document type, e.g. RFQ document
  - Extracted information includes project title, closing date, customer name, date published, contact person
3. PDF-to-text
  - An easy way to convert multiple PDF files to .txt files

Tech stack:

- Frontend: React.js + Ant Design UI
- Backend: Python (RESTful Flask API)
- Deployment: Google Kubernetes Engine
- DevOps: Gitlab CI/CD
- Other tools: Elasticsearch, Apache Tika

A dummy instance of this app is running at the address **http://34.87.187.144**.

The repositories are hosted on Gitlab as Gitlab CI/CD is used as the DevOps tool:

- Frontend: https://gitlab.com/ruibinch/pdftk-fe
- Backend: https://gitlab.com/ruibinch/pdftk-be
- Deployment: https://gitlab.com/ruibinch/pdftk-deployment
