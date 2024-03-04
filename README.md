# FloodGPT: An Advanced AI Assistant for Flood Risk Management
FloodGPT-4: An Advanced AI Assistant Enabled by GPT-4 for Enhanced Interpretability and Public Engagement

## Introduction
Welcome to the **FloodGPT-4** project repository! This initiative explores the integration of **GPT-4's** advanced capabilities with flood risk management strategies to offer an innovative AI Assistant. Our prototype, featured in the paper "Towards Democratized Flood Risk Management: An Advanced AI Assistant Enabled by GPT-4 for Enhanced Interpretability and Public Engagement," aims to make flood risk information more accessible and actionable for the public.

## Repository Contents
This repository primarily contains the Jupyter Notebook (`FloodGPT.ipynb`) that serves as the core of our prototype, showcasing the AI Assistant designed to enhance flood risk management.

### Setup Instructions
To get the prototype up and running, follow these steps:

1. **Clone this repository** to your local machine to get the `FloodGPT.ipynb` notebook. You can do this by running the following command in your terminal or command prompt:
   ```bash
   git clone https://github.com/RafaelaMartelo/FloodGPT-4_Prototype.git
   cd FloodGPT-4_Prototype
   
2. **Download the 2020 US SVI data** from [CDC/ATSDR's official site](https://www.atsdr.cdc.gov/placeandhealth/svi/data_documentation_download.html). This data is essential for the prototype's operation.

3. **Place the downloaded SVI_2020_US folder** in the same directory as the FloodGPT.ipynb notebook.

4. **Create a .env file** in the root directory of the cloned repository. Inside this file, include your API keys for the National Flood Map Data API and the ChatGPT-4 API like so:
      ```bash
   OPENAI_API_KEY=your_openai_api_key_here
   FEMA_API_KEY=your_fema_api_key_here

5. **Ensure you have access to the following APIs** used in the prototype:

   - **National Flood Map Data API:** [Documentation](https://docs.nationalflooddata.com/dataservice/v3/index.html) - Used to retrieve flood data and flood map.
   - **ChatGPT-4 API:** [Documentation](https://platform.openai.com/docs/introduction) - Powers the intelligent responses and function calls within the prototype.

6. **Open and run the notebook** in a Jupyter environment. This will activate the FloodGPT-4 AI Assistant, ready to assist with flood risk management tasks.


## Authors

Rafaela Martelo & Ruo-Qian Wang

## Acknowledgments
This project's initial structure and function calling implementation were inspired by the following resources:

- "Function Calling: Integrate Your GPT Chatbot With Anything" by Tomas Fernandez
  [Link to Article](https://dzone.com/articles/function-calling-integrate-your-gpt-chatbot-with-a)

- "gpt-function-calling-tutorial" by JayZeeDesign
  [Link to GitHub Repository](https://github.com/JayZeeDesign/gpt-function-calling-tutorial)
