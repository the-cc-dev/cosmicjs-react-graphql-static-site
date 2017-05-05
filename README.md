# React GraphQL Static Site
This is an example of a simple blog app built using [create-react-app](https://github.com/facebookincubator/create-react-app). It's powered by [GraphQL](http://graphql.org/) connected to the [Cosmic JS API](https://cosmicjs.com/) for easy content management.

## Getting Started
1. Go to [Cosmic JS](https://cosmicjs.com/) and create a new Bucket.
2. Import the `bucket.json` in this repo to your Bucket located in Your Bucket > Import / Export
3. Download the app:
```
git clone https://github.com/tonyspiro/react-graphql-static-site
cd react-graphql-static-site
yarn
```
## Starting the app
### Run in development
Connect to your Cosmic JS Bucket using the environment variable `COSMIC_BUCKET` or edit the `config.js` file.
```
COSMIC_BUCKET=your-bucket-slug yarn start
```
### Build for production
```
COSMIC_BUCKET=your-bucket-slug yarn build
```
