# S3 Browser

Render the contents of your Amazon S3 bucket in a beautiful file browser

## Getting started

1. Configure `config.json` for your S3 bucket
1. Configure your AWS S3 bucket for Website hosting
1. Make it public read (lock down IP restrictions if you like).
1. Enable CORS
1. Run `index.html`

# For developers
Install http-server by typing `npm install -g http-server`

Change into your working directory, where index.html lives

Start your http server by issuing `http-server -c-1`

This spins up a Node.js httpd which serves the files in your directory as static files accessible from http://localhost:8080
There are more commandline options available if required, see https://www.npmjs.com/package/http-server.
