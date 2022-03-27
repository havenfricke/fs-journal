# Deploying Applications

**1.** What is the package.json file used for?
<!-- enter you answer in the space below -->
```
The .json file collects metadata in a node project so that dependancies can be installed when uploaded to NPM as a public registry. 

``` 
**2.** At what level of your project do you need package.json when deploying your application? Why?
<!-- enter you answer in the space below -->
```
When uploading to npm as a publisc registry, a .json file's metadata is used to install dependencies

```
**3.** What command will ensure that your Vue code is compiled properly for deployment?
<!-- enter you answer in the space below -->
```
npm-run

```
**4.** _______ are used to provide your application with specific data based on it's environment. For example: connections strings, private keys or port. Fill in the blank.
<!-- enter you answer in the space below -->
```
.env files

```
**5.** What are the two ways to view the logs from your Heroku app.
<!-- enter you answer in the space below -->
```
--source app and --source heroku

```
**6.** How do you update an app already deployed on Heroku?
<!-- enter you answer in the space below -->
```
- Clone the repository from GitHub to your local device:
use command git clone <YOUR HTTPS URL FROM GITHUB>

- Make your changes, and commit them to GitHub:
use command git add .
use command git commit -m "<YOUR COMMIT MESSAGE>"
use command git push origin <YOUR BRANCH NAME>

- Login to your Heroku account:
use command heroku login
Follow the directions on the screen to login to your account through the browser, then return to the terminal in vscode

- Set remote for your project:
use command heroku git:remote -a <YOUR PROJECT NAME>

- Push to Heroku master to deploy updates:
use command git push heroku master

```
**7.** Why is branching important to version control?
<!-- enter you answer in the space below -->
```
Branching is important to version control because different versions of an app can be deployed from a baseline project. 

```
**8.** When should code review happen?
<!-- enter you answer in the space below -->
```
before the testing phase and after the development phase. It should be around the time the app has first come together to talk out bugs and unwanted features or where aditional features would be preferred.

```
**9.** What is the term used to define combining two branches?
<!-- enter you answer in the space below -->
```
A merge.

```