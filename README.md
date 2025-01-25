# Running the project locally 
* Clone the repo in your system.
* Make a Virtual Environment in your Vscode using the following command.
  *  python -m venv myenv
*  To run the Virtual Environment use:
   *  myenv\Scripts\activate
* Install the Libraries once in the Virtual Environment:
* Command for installing all the required libraries.
  * pip install flask numpy==1.26.4 pandas==2.2.2 scikit-learn==1.2.2 gunicorn
* Run the python file using:
  * python app.py
  * To stop the flask server from running press Ctrl+C in your Vscode.
* To deactivate the Virtual Environment after use write deactivate in the terminal.
  







# Steps to host this on Render
* Clone this repository on your system.
* Make a new repo on GitHub. 
* Push the code to that Repo.
  * Use the following Commands in your Vscode Terminal to push:
    * git init
    * git add .
    * git commit -m "your_message"
    * git remote add origin your_git_repo_url
    * git push -u origin master
* Go to [Render.com](https://render.com/).
* Sign in, You will be directed to the Dashboard.
* Choose Web Service out of all the options.
* Choose the git service and then it will prompt you to authorize your git account.
* Select the repo you want to Host.
* After selecting the repo, you can put the name of your website theres no need to chnage the rest.
* Select the free plan, and finally click on the Deploy button. 
      
