# How to deploy?

`Workflow Method.`

Fork or import heroku branch only.

- Upload Config.env (Either Zmirror or Weebzone) in This Repo.
- Upload token.pickle in root folder. 
- If you want to add service account json then create a folder name accounts and upload your account json file .

### Add These in Secrets

- `HEROKU_EMAIL`
- `HEROKU_API_KEY`
- `HEROKU_APP_NAME`

This docker is unable to extract accounts.zip . So create a folder name accounts and upload all service accounts json in accounts folder.
If you add anything in heroku branch you need to run workflow to load changes .

## Modded Versions

* [Zmirror](https://github.com/kctelegram5/ZMirror-Heromku)
* [WeebZone](https://github.com/kctelegram5/Weebzone-heromku)

  >**NB** : Add [Cron-job](https://cron-job.org/en/) for 5min to avoid Sleep 



Will Try to add Other Repo's Also in Future
