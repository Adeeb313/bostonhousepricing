### Boston House Pricing Prediction 

### Software and Tools Requiredments

1. [Github Account](http://github.com)
2. [Heroku Acoount](http://heroku.com)
3. [VS code IDE](http://code.visualstudio.com)
4. [Git CLI](https://git-scm.cogitm/book/en/v2/Getting-Started-The-Command-Line)

### Create a New Environment

```
python -m venv .venv
```
```
.venv\Scripts\activate
```
### Install all dependency libraries
```
git config --global user.name and git config --global user.email
```
### add all modified files and commit then push
```
git add . 
```
```
git commit -m "comment"
```
```
git push origin main
```
### GitHub Actions Workflow
### Project : Boston House Price Prediction (Flask + Docker)
### Purpose : Build, Test and Deploy to Heroku using Docker

### Official Documentation:
1. [GitHub Actions](https://docs.github.com/actions)
2. [Docker](https://docs.docker.com/)
3. [Python Setup Action](https://github.com/actions/setup-python)
4. [Checkout Action](https://github.com/actions/checkout)
5. [Heroku Container Registry](https://devcenter.heroku.com/articles/container-registry-and-runtime)

### Required GitHub Repository Secrets
```
Go to:

GitHub → Repository → Settings → Secrets and variables → Actions

Create these secrets:

Secret Name	Value
HEROKU_EMAIL	Your Heroku account email
HEROKU_API_KEY	Heroku API Key
HEROKU_APP_NAME	Your Heroku App Name
```
