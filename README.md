# Fred's List Social Auth

## Description
Using python-social-auth implement at least 2 different social authentication options in addition to the username/password option. 

## Details

### Learning Objectives
* Understanding social authentication
* Basic understanding of OAUTH

### Requirements
* Pull request with django project

### Normal Mode
* Implement at least 2 different social login options
* Ensure that at least 1 view is secured to only authenticated users
* Ensure that a user can use the secured view after only logging in via a social application
* Ensure that a token is generated and can be used to authenticate to the api side

#### Resources
* [Documantation](http://python-social-auth.readthedocs.org/en/latest/)
* [Backend Implementation help](https://github.com/omab/python-social-auth/tree/master/docs/backends)

### Hard Mode
* Implement the email option in the pipeline to allow users to use different backend authentications but still tie to the same user

#### Resources
[Pipelines](http://python-social-auth.readthedocs.org/en/latest/pipeline.html)
