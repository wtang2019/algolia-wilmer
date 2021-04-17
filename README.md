# wilmer-ecommerce-demo-app

_This project was generated with [create-instantsearch-app](https://github.com/algolia/create-instantsearch-app) by [Algolia](https://algolia.com)._

## Get started

To run this project locally, install the dependencies and run the local server:

```sh
npm install
npm start
```

Alternatively, you may use [Yarn](https://http://yarnpkg.com/):

```sh
yarn
yarn start
```

Open http://localhost:3000 to see your app.

## Overview
This project was created with algolia's create-instantsearch-app and using the demo_ecommerce test datatest provided by algolia as well.
The concept of how algolia works has been understood but however due to time constraints I haven't changed the UI much.

## Feedback
I initially thought that I could easily integrate algolia's search by simply using algolia's API into my existing website. However, it took me some time to understand the concept of the different components. I quickly built a web application based on Python hosted in Azure and wanted to integrate Algolia's search into that using the airport dataset. But the Python API was actually just used to push data into Algolia.

Some of the challenges I faced during the Integration:
* The understanding of the different components and finding the right documentation to guide me through an example
* When I deployed the instantsearch app I faced an error which took me a bit to understand what the issue was. The solution was to use an older version of the parcel-bundler 1.12.2 instead of the 1.12.3 which was defined as a default dependency by the instantsearch app
* The documentation suggested the wrong appID and search API key hence the data set was always empty until I noticed that the documentation shown was not my API Keys which wasn't outlined or shown where I can find the keys in the documentation.





