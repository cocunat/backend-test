# backend-test

The purpose of this task is to see the ability of the candidate to read other people's code and be able to apply modifications, also we have a similar file and code structure in our codebase so, this will also be useful as introduction.

## Task
The repository is: https://github.com/maguayo/django-starter-api

Right now, it's only possible to authenticate the requests using [JWT](https://tools.ietf.org/html/rfc7519). JWT tokens are useful for the frontend, because the token contains information about the user. But we might need other backend services or APIs to make petitions to our API, so allowing another authentication method might be useful.

1) Implement an alternative authentication mode using Django Rest Framework [tokens](https://www.django-rest-framework.org/api-guide/authentication/#tokenauthentication)
2) Make sure you add some tests
3) Create a PR
