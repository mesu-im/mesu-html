mesu.im
=======

## Dependencies

0. node `0.10.24`+
0. npm `1.3.21`+
0. bower `1.3.2`+
0. compass `0.12.5`+
0. grunt-cli `0.1.11`+
0. grunt `0.4.4`+

## Development

Clone repo:

`git clone git@github.com:suda/mesu-html.git && cd mesu-html && git checkout develop`

Install all dependencies:

`npm install && bower install`

Run `grunt` to start server:

`grunt serve`

Website should be opened automatically ([0.0.0.0:9000](http://0.0.0.0:9000))

## Deployment

Build the project with a `grunt` task:

`grunt build`

### Developer preview

Run `grunt ftp-deploy`. Contents of `dist/` will be uploaded to our [staging](https://mesu.im) automatically.

### Production

Contents of `dist/` should be uploaded manually to the production server.
