# REMIND - Sendinblue

This extensions adds a form finisher to create a new Sendinblue contact using double-opt-in.


## Installation

Use comoser to install the extension using `composer install remind/sendinblue`. Import typoscript in backend or your provider extension.


## Configuration

- set *SENDINBLUE_API_KEY* environment variable
- add the *Sendinblue Registration Finisher* to a form 
- set comma separated list of Sendinblue Contact List IDs in finisher configuration
- set double-opt-in Sendinblue Template ID in finisher configuration
- set redirect URL (after DOI-Mail confirmation link has been clicked) in finisher configuration
