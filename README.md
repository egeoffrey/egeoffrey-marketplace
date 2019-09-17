# eGeoffrey Marketplace

The marketplace allows eGeoffrey users to exchange new and original contents. 

## Usage

Access the marketplace from both your eGeoffrey instance under *'eGeoffrey Admin'*/*'Marketplace'* or from the main [eGeofrrey website](https://marketplace.egeoffrey.com).

The marketplace leverages eGeoffrey's modular framework which allows new packages to be easily plugged into the application without further actions or dependencies.

Search the marketplace for packages which could be helpful for your needs and simply follows the installation instructions to add the them to your eGeoffrey.

## Contributing

Have you created a new amazing content and are willing to share with other eGoeffrey users? You are in the right place!

After having created your package and published the source code on your own Github repository and the Docker image on you own Dockerhub account, submit a PR (Pull Request) to this repository to have it included into the Marketplace by adding a file in the `marketplace` directory named as your package name with a `yml` extension (e.g. if your package is named `egeoffrey-service-yourservice`, the file will be `marketplace/egeoffrey-service-yourservice.yml`).

Please ensure you respect eGeoffrey naming convention in naming your package before submitting your request.

The file must contain a single line pointing to the Github `username/repository` where the package resides, e.g.

```
github: username/egeoffrey-service-myservice
```

Once your request will be merged, your package will be available for all the other eGeoffrey users!