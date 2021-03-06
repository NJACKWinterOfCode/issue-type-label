<p align="center">
	<img src="./assets/logo.png" alt="issue-type-label" height="150">	
</p>
<h1 align="center">
	issue-type-label
</h1>

[![Build Status](https://travis-ci.org/anshumanv/issue-type-label.svg?branch=master)](https://travis-ci.org/anshumanv/issue-type-label)

> a GitHub App to automatically label issues based on the title.


### See it working
Head over to [this](https://github.com/anshumanv/testing) repository and try opening up an issue.

## Demo

<img src="./assets/demo.gif" alt="Demo" align="center">

## Development
- Clone repo
  ```
  git clone git@github.com:anshumanv/issue-type-label.git
  cd issue-type-label
  npm install
  ```
- Create your own GitHub app: [instructions](https://probot.github.io/docs/development/#configure-a-github-app)
- Store the private key as `private-key.pem` in the repository’s directory
- Start the app with `APP_ID=1234 npm start` where `1234` is your GitHub App’s ID
- update your GitHub App’s `Webhook URL` to your localtunnel.me URL

## Author

Anshuman Verma

[<img src="https://image.flaticon.com/icons/svg/34/34238.svg" width="50" padding="10">](https://twitter.com/Anshumaniac12)
[<img src="https://www.shareicon.net/download/2015/11/02/665921_internet.svg" width="50" padding="10">](https://linkedin.com/in/anshumanv12)
[<img src="https://upload.wikimedia.org/wikipedia/commons/9/91/Octicons-mark-github.svg" width="50" padding="10">](https://github.com/anshumanv)

## Contribute
Found a bug, please [create an issue](https://github.com/anshumanv/issue-type-label/issues/new)

## License
ISC
> © Anshuman Verma
