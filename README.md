# SiteGenie Bot Inerface using Streamlit

This is a sample chat application built with Streamlit, utilizing Vertex AI Text Bison for generating responses. The application is containerized using Docker, allowing for easy setup and deployment.

## Prerequisites

Before you begin, make sure you have Docker and Docker Compose installed on your system. If you don't have them installed, follow the installation guides for [Docker](https://docs.docker.com/get-docker/) and [Docker Compose](https://docs.docker.com/compose/install/).

## Setup

1. **Clone the Repository**

   Clone or download the repository.


2. **Configure Environment Variables**

   Before running the application, you need to set up your OpenAI API key. Copy the `.env-example` file to a new file named `.env` in the same directory. Then, open the .env file and replace `OPENAI_API_KEY` with your actual OpenAI API key:
   
   OPENAI_API_KEY=<your_openai_api_key>
 

3. **Building & Running Docker**

   docker-compose up --build 

If successfully built, you should be provided with network url to access the interface through browser.