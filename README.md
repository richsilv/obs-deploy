# obs-deploy
Deployment config for jimmytidey/obs via Meteor up

## How to deploy

```
npm install -g mup
git clone https://github.com/richsilv/obs-deploy
cd obs-deploy
```

Update mup.json with the appropriate local paths to your AWS pem and the obs app directory. Then:

```
mup setup
mup deploy
```
