# Image Processing API

This API allows users to perform basic image processing tasks such as resizing images.

# Scripts

- `npm run build` - build the project
- `npm start` - start the build
- `npm run dev` - start the server in development mode
- `npm test` - run the tests
- `npm run lint`-run lint
- `npm run prettify`- Prettify
- `npm run start`-Start Server
Now you need to install the dependencies for the server code.

### Install all dependencies using the package.json file

```bash
npm install
Lint the code using Eslint
npm run lint
Format the code using Prettier
npm run format
Build and Test the app using Jasmine
npm run test
Now that everything is set up, you can test the app by starting the server using nodemon
npm run dev
Usage:
To use the Image Processor API, send a request to the endpoint with the following query parameters:

filename : The filename of the image file to process as stored under assets

width : The intended width of the image file to be returned

height : The intended height of the image file to be returned

Example - http://localhost:7070/api/images?filename=palmtunnel&width=500&height=500
Once the application is running, a sample front-end page can be viewed - http://localhost:5000/ - which displays image thumbnails with varying sizes.

#####Dependencies

Jasmine: npm i jasmine Jasmine spec reporter: npm i jasmine-spec-reporter Express: npm i express Sharp: npm i sharp Supertest: npm i supertest

Jasmine: npm i jasmine
Jasmine spec reporter: npm i jasmine-spec-reporter
Express: npm i express
Sharp: npm i sharp
Supertest: npm i supertest
##############devDependencies

Prettier: npm i --save-dev prettier
ESlint: npm i --save-dev eslint
ESlint config prettier: npm i --save-dev eslint-config-prettier
ESlint plugin prettier: npm i --save-dev eslint-plugin-prettier
Typescript: npm i --save-dev typescript
TS Node: npm i --save-dev ts-node
Node types: npm i --save-dev @types/node
Jasmine types: npm i --save-dev @types/jasmine
Supertest types: npm i --save-dev @types/supertest
Express types: npm i --save-dev @types/express
Nodemon: npm i --save-dev nodemon
Sharp types: npm i --save-dev @types/sharp
Error messages:
401 Bad Request: query parameters are missing, invalid or cannot be determined

404 Not Found: image file could not be found or does not exist under assets
# Endpoint

- `GET /api/images?filename=filename&width=width&height=height` - returns the image with the specified filename, width and height

# Any other functionality

- `GET /{any other route}` - shows the documentation

## License

[License](LICENSE.txt)
