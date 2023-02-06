# AI text Generator on Steroids
Just your basic text generator using OpenAI
Heroku Deployment

![Alt text](https://raw.githubusercontent.com/unnamedmistress/AutoCompleteSteroids/main/public/homepage.png)

## Play with me
https://upgradem.herokuapp.com/

# Steps:
1. Clone this repository: Open your terminal and navigate to the directory where you want to clone the repository. Run the following command:

git clone https://github.com/unnamedmistress/AutoCompleteSteroids.git

2. Install dependencies: Change your terminal's current directory to the cloned repository and run the following command to install the necessary dependencies:

npm install

3. Add API key: Go to the .env.example file and replace YOUR_API_KEY with your OpenAI API key. Then, rename the file to .env.

4. Start the development server: In your terminal, run the following command to start the development server:

npm run dev

5. Deploy to Heroku (or your preferred site): If you want to deploy your application to Heroku, you will need to create a Heroku account and follow the steps provided by Heroku to deploy your application.

6. Edit the prompt: Navigate to the Pages/API/generate.js file and look for line 34. This is where you can edit, update, or create your own prompts.

Now when someone enters in text and presses submit, your prompt will customize the output of the OpenAPI.

That's it! You now have a fully functional AI text generator that can be run on your local machine or deployed to the web. You can make changes to the code and customize the application to fit your needs.