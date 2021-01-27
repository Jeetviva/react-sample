# Gitlab Pages React Example

This is a react app setup to be run easily with a Gitlab pipeline and be deployed to Gitlab pages.

It is to be used with this tutorial - https://dev.to/jtorbett23/react-gitlab-pages-42l6

Gitlab repository - https://gitlab.com/jtorbett23/gitlab-pages-react-example/
Gitlab pages url - https://jtorbett23.gitlab.io/gitlab-pages-react-example/

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner to run all tests.\

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

## Deploying to Gitlab pages

To deploy this project to Gitlab pages first fork this project.

Then create a new Gitlab project and choose "Run CI/CD for external repository".

Once your first pipeline has finished running go to Settings > Pages to find the url the page is hosted.

If you only see a whitescreen make sure to edit the "homepage" attribute in the `package.json` to match your url.

For example my url is "https://jtorbett23.gitlab.io/gitlab-pages-react-example/", so my homepage will need to be "gitlab-pages-react-example".
