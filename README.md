Okta Server Side Lab
=====================

**Background:**

An example server side application that uses OpenId Connect (OIDC) to authenticate users.
The actual application uses Java Spring Boot, but it builds and runs with Docker and you don't need any prior Java knowledge. 

TODO:
- [ ] Flush out readme
- [ ] Change name of Maven artifactId

**Prerequisites** 
- [Docker](https://docs.docker.com/get-docker/)
- [Okta CLI](https://cli.okta.com/)

Clone this repo:

```bash
git clone https://github.com/TBD
cd TBD
```

## Create an Okta OIDC Application

Register your application with Okta, run:

```bash
okta start
```

## Start the application

Start up the application:

```bash
docker compose up
```

Open a private/incognito browser to `http://localhost:8080`, you will be redirected to Okta to sign-in.
