# developer.nrel.gov

Have questions, feedback, or issues with the APIs available at [developer.nrel.gov](https://developer.nrel.gov/)? [Contact us](https://developer.nrel.gov/contact/) or let us know in the [issue tracker](https://github.com/NREL/developer.nrel.gov/issues).

This repository stores the website content and documentation for [developer.nrel.gov](https://developer.nrel.gov). Contributions are welcome. To submit a change, fork this repo, commit your changes, and send us a [pull request](https://help.github.com/articles/using-pull-requests).

## Development

The content files to edit are in [`./source`](https://github.com/NREL/developer.nrel.gov/tree/master/source). To preview your changes you can use the [Middleman](https://middlemanapp.com) preview server. To run Middleman:

1. Install [Docker](https://www.docker.com/community-edition) on your computer.
2. Checkout the `developer.nrel.gov` repository on your computer (`git clone https://github.com/NREL/developer.nrel.gov.git`).
3. Inside the `developer.nrel.gov` directory, run `docker-compose up`.
4. View your changes at: http://localhost:4480/

## Deploy

- Changes committed to the `staging` branch will automatically be deployed to the staging site.
- Changes committed to the `master` branch will automatically be deployed to the production site.

Deploys may take a few minutes after pushing before they show up. You can check the status on our internal Jenkins server (under the "developer.nrel.gov-deploy" job).
