# Keyboard Firmware Builder

## Where did kbfirmware.com go?

Due to a lack of users, as of 13 March 2021, kbfirmware.com has been shut down. Thank you for all the support while the project was active!

Rest in Peace, kbfirmware.com: 9 January 2017 - 13 March 2021

### Docker Image

The latest image of kbfirmware.com is available as a Docker image, available at https://hub.docker.com/repository/docker/ruiqimao/kbfirmware.

By default, this image will use port 80. To use any other port, expose and set the `PORT` environment variable accordingly.

## Setup

To set up the project for development, run `npm install` in the root of the project to install dependencies.

Create a `local.json` file in `src/const`, in the format:

    {
		"API": "URL to server /build route",
		"PRESETS": "URL to static/presets folder"
	}

## Compiling

To compile, run `npm run build`.

## Deploying

To deploy a production version of the application, run `npm run deploy`.
