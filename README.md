# loan-payments

- need the Heroku CLI installed: 
    - `npm i -g heroku`
- login to Heroku:
    - `heroku login`
- need to attach the remote if not already linked: 
    - `heroku git:remote -a <app-name>`
- update any submodules that may have changed: 
    - Pull each changed module first
        - `git push heroku master`
    - Update project and push
        - `git submodule update`
        - `git commit -a -m "Latest Version"`
        - `git push origin main`
- verify on Git the submodules are the correct version
- when ready, push to Heroku:
    - `git push heroku main`

