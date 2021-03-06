# AWS Diagram

A simple diagram showing the common relationships between the most popular AWS services.

![The diagram](diagram.svg)

## Usage

Install the [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) font.

```bash
$ brew install graphviz node
$ npm install
$ npm run build
$ open diagram.svg
```

## Development

```bash
$ npm run watch
```

## TODO

- Services: ECS, DynamoDB, Step Functions?
- Paint services according to their type ("Compute", "Storage", "Network & Content Delivery", ... see grouping in AWS Console). See https://jsbin.com/guwazen/4/edit?js,console,output.

## Reference

- [Drawing graphs with (Graphviz) dot](https://graphviz.gitlab.io/_pages/pdf/dotguide.pdf)