# Intro to Context Caching with the Gemini API (GSP1265)

This repository contains materials for the Google Cloud Skills Boost lab: **Intro to Context Caching with the Gemini API (GSP1265)**. This lab introduces you to the context caching feature of the Gemini API within Vertex AI, enabling you to optimize requests by storing and reusing frequently used input tokens.

## Overview

The Gemini API's context caching allows developers to store and reference frequently used input tokens, reducing token redundancy and lowering request costs. This lab provides hands-on experience in utilizing this feature to enhance efficiency and cost-effectiveness when working with Gemini models.

## Lab Objectives

In this lab, you will learn how to:

* Create a context cache.
* Retrieve and use a context cache.
* Use context caching in chat applications.
* Update the expiration time of a context cache.
* Delete a context cache.

## Prerequisites

Before you start this lab, you should have:

* Basic Python programming knowledge.
* General understanding of API concepts.
* Experience running Python code in Jupyter notebooks on Vertex AI Workbench.

## Lab Content

This repository includes:

* `intro_context_caching.ipynb`: The Jupyter Notebook containing the lab exercises.

## Lab Tasks

1.  **Open the notebook in Vertex AI Workbench:**
    * Navigate to Vertex AI > Workbench in the Google Cloud console.
    * Open the JupyterLab instance.
2.  **Set up the notebook:**
    * Open the `intro_context_caching.ipynb` file.
    * Select the Python 3 kernel.
    * Run the "Getting Started" and "Import libraries" sections.
    * Set the Project ID and Location.
3.  **Create a context cache:**
    * Run the code to create a new context cache.
4.  **Retrieve and use a context cache:**
    * Learn how to retrieve and utilize an existing context cache in your requests.
5.  **Use context caching in Chat:**
    * Explore how to implement context caching within a chat application context.
6.  **Update the expire time of a context cache:**
    * Learn to modify the expiration time of a created context cache.
7.  **Delete a context cache:**
    * Learn to delete a context cache.

## Setup and Requirements

* Access to a standard internet browser (Chrome recommended).
* Use an Incognito or private browser window to prevent account conflicts.
* Time to complete the lab (approximately 1 hour).
* Temporary Google Cloud credentials provided by the lab.

## How to Start the Lab

1.  Click the "Start Lab" button in Google Cloud Skills Boost.
2.  Open the Google Cloud console using the provided credentials.
3.  Navigate to Vertex AI > Workbench.
4.  Open the JupyterLab instance.
5.  Follow the instructions within the `intro_context_caching.ipynb` notebook.

## Additional Resources

* [Gemini API Documentation](https://cloud.google.com/vertex-ai/docs/generative-ai/learn/model-gemini)
* [Vertex AI Documentation](https://cloud.google.com/vertex-ai/docs)
* [Google Cloud Documentation](https://cloud.google.com/docs)

## Credits

This lab is provided by Google Cloud Skills Boost.
