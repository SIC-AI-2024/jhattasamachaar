# JhattaSamachaar: Personalized News Summarization Application

Welcome to the repository for JhattaSamachaar, our personalized news summarization application. This project uses advanced AI techniques to deliver concise and user-specific news summaries. Below is an overview of the repository structure and key details about the project.

## Repository Structure

- **[Backend](./backend/)**
  - Django-based backend using DRF (Django Rest Framework) with Google Firebase login implemented via Knox tokens.
- **[Frontend](./frontend/)**
  - Flutter-based cross-platform mobile application (details to be completed).
- **[Dataend](./dataend/)**
  - Data handling and processing, using a cookie-cutter data template for maintaining project organization.
- **[Docs](./docs/)**
  - Contains project documents, including the proposal report, mid-term status report, and final report.

## Project Overview

JhattaSamachaar is designed to provide a culturally relevant and efficient news experience tailored to user interests. The project integrates a **fine-tuned T5 transformer model** with a robust backend and frontend, creating a seamless and personalized user experience.

### Key Objectives

1. **Model Development**: Fine-tune a T5 transformer model for effective news summarization.
2. **Dataset Preparation**: Collect, preprocess, and utilize in-house datasets for model training and validation.
3. **Frontend Development**: Build a cross-platform mobile application using Flutter to deliver news summaries and customization options.
4. **System Integration**: Combine backend, summarization model, and frontend for real-time summarization and deployment at scale.

## Repository Links

- [Backend Repository](./backend/)
- [Frontend Repository](./frontend/)
- [Dataend Repository](./dataend/)

## Personal Repo Links
*if above links aren't updated*
- [Backend Repository](https://github.com/darpankattel/jhatta-samachar)
- [Frontend Repository](https://github.com/amritsharma01/jhattasamachaar)
- [Dataend Repository](https://github.com/darpankattel/jhatta-samachaar-dataend)

## Project Reports

The following reports can be found in the **[Docs Folder](./docs/)**:

- Proposal Report
- Mid-Term Status Report
- Final Report

---

### Backend

The backend is built using Django and Django Rest Framework. It includes:

- Google Firebase login based on Knox-generated tokens.
- Instructions for setting up the backend:
  1. Clone this repository.
  2. Navigate to the `backend` folder: `cd backend/`.
  3. Create a virtual environment: `python -m venv venv`.
  4. Install requirements: `pip install -r requirements.txt`.
  5. Apply database migrations: `python manage.py migrate`.
  6. Run the server: `python manage.py runserver`.

While you may run the server, but for fully setting it up, you may require a `.env` file with `GOOGLE_CLIENT_ID` of your firebase app. Also, the models are directly used inside the backend, hence, model files are also required.

### Frontend

*Amrit, your work remains.*

### Dataend

The dataend folder is structured using a cookie-cutter data template. It includes:

- Notebooks for all stages of the project.
- The dataset and model files are not included in the repository but can be accessed via this [Google Drive link](https://drive.google.com/drive/folders/1Iau3EdYNw5o2pF_1uKp2aqtW9AVByHJS?usp=sharing) upon request, or with campus id, there is complete access.

---

We welcome contributions and feedback to improve the project further. Thank you for checking out JhattaSamachaar!
