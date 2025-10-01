There are many ways to install/deploy Flowise (Chatflow), this tutorial will be using Hugging Face to host Flowise.  
Login to Hugging Face 🤗.  

## Step 1: Create a new space  
Give the space a name and a short description.  Then select Docker as the SDK.
<img width="500" height="545" alt="Image" src="https://github.com/user-attachments/assets/5a638cee-8dae-4229-8854-3b3cb88d05cf" />  

> * Choose Blank for Docker Template  
> * Select CPU Basic for Space hardware
> * Create Space  

<img width="500" height="700" alt="Image" src="https://github.com/user-attachments/assets/8007b092-40fd-4e0f-9fba-c18659e08e45" />  

## Step 2: Set the Environment Variables  
Click on Settings and scroll down to find New Variable.  
<img width="1000" height="126" alt="Image" src="https://github.com/user-attachments/assets/d14d430d-0a0b-426b-b030-265675287859" />

Enter "PORT" in the name field, and "7860" in the Value field.  
<img width="500" height="380" alt="Image" src="https://github.com/user-attachments/assets/6123ad1f-598b-42ed-bdcf-8d77991399fa" />  

## Step 3: Create a Docker file  
File tab > Contribute > Create a new file  
<img width="500" height="223" alt="Image" src="https://github.com/user-attachments/assets/9d0e0d37-2812-439f-aacc-418eea2cf3de" />  

Go to https://docs.flowiseai.com/configuration/deployment
/hugging-face to copy the Dockerfile text.  
<img width="600" height="400" alt="Image" src="https://github.com/user-attachments/assets/ea5d7509-304d-49b1-a317-984d2d370878" />  

> * Return to Hugging Face.
> * Name the file "Dockerfile"
> * Paste the Dockerfile text into the canvas and make two amendments shown below
> * Commit new file
<img width="700" height="570" alt="Image" src="https://github.com/user-attachments/assets/27f468c1-6104-40a5-bc2c-a76948d4a5c5" />

<img width="700" height="170" alt="Image" src="https://github.com/user-attachments/assets/4e8fb71b-5c46-492c-96ee-f9913dcbf9f6" />  

Hugging Face will start building the new space, this step will take about 5 - 10mins.
<img width="1200" height="130" alt="Image" src="https://github.com/user-attachments/assets/6a8bdb83-b3bb-4ba4-92f2-53d7d99572a9" />   

Once building is completed, the Flowise space will be created and running.  
<img width="400" height="200" alt="Image" src="https://github.com/user-attachments/assets/5eb7b8b9-155f-4090-8557-16b50eb26ef0" />

End of Flowise setup. Back to [Projects Portfoilio](https://cheeweeng.github.io/)
