## Ruby on Rails Acornfile

Here we have the Simple `Articles App` using Ruby on Rails framework and we have the Acornfile which can be used to deploy it on Acorn SaaS Platform.

##### Deploying the App on SaaS Platform.
- First you need to login to saas platform using your github username.Once the Account is setup you need to click on create and select `from acorn image` where you need to select `name`, `region` and `Acron Image`. For Ruby on rails below is the latest image
```
ghcr.io/infracloudio/ruby-on-rails-acorn:v0.0.2
```
Once you click on `Create` , Provisioning starts and in some time your app is in Running state and you can access it using the given URL.

##### Checking App logs
- You can click on 4 dots on the right side of your app on the UI and click on View Logs through which you can see your app Logs.

##### Removing the App
- If you simply want to remove the App . Click on the 4 dots and click `Remove` which will remove your app.

---

As this Application just include simple `Articles App` which can be easily customized based on your requirement . You can follow all the Ruby on Rails docs.

- [Getting Started](https://guides.rubyonrails.org/getting_started.html)

Join the Acorn Community Slack

- [Slack](http://slack.acorn.io/)