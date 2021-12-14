# Tiffinger & Thiel GmBH Nestjs Schematics
A fork of [Nestjs Schematics](https://github.com/nestjs/schematics) with our own defaults.

## Description

__IMPORTANT:__ As we only use typescript, the js schemas are untouched!

The Nest CLI is a command-line interface tool that helps you to initialize, develop, and maintain your Nest applications. It assists in multiple ways, including scaffolding the project, serving it in development mode, and building and bundling the application for production distribution. It embodies best-practice architectural patterns to encourage well-structured apps. Read more [here](https://docs.nestjs.com/cli/overview).

## Installation

Note: Run this also to update the local version!
```
$ npm install -D -g @tiffinger-thiel/schematics
```

## Usage

Just update the local version and then use it
```
$ npm install @tiffinger-thiel/schematics @nestjs/cli -g
$ nest new -p yarn -l TypeScript --strict -c @tiffinger-thiel/schematics project-name
```

Learn more in the [official documentation](https://docs.nestjs.com/).

## License

Nest is [MIT licensed](LICENSE).