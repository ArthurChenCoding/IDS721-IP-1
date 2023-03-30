[![CI](https://github.com/nogibjj/aws-template/actions/workflows/cicd.yml/badge.svg?branch=main)](https://github.com/nogibjj/aws-template/actions/workflows/cicd.yml)
[![Codespaces Prebuilds](https://github.com/nogibjj/aws-template/actions/workflows/codespaces/create_codespaces_prebuilds/badge.svg?branch=main)](https://github.com/nogibjj/aws-template/actions/workflows/codespaces/create_codespaces_prebuilds)

# Intro
This project implements a microservice that calculate the final savings given the initial investment amount and number of years assuming all investments goes to S&P 500

By making a web request to the microservice, the microservice return the final amount of investment.

# Set up
1. Open a terminal

2. cd into  individual_project_1

3. install virtualenv:  python3 -m pip install virtualenv

4. create a virtualenv: /home/coder/.local/bin/virtualenv VENV

5. source the virtualenv:  source VENV/bin/activate

6. cd into flask-change-microservice:

7. install software:  make install

8. run flask:  python app.py

visit 127.0.0.1:5000/change/<initial_investment_in_dollar>/<number_of_years> This will make a web request to Microservice.