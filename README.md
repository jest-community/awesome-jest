# Awesome Jest [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> An awesome list of [Jest](https://jestjs.io) packages and resources

## Contents

- [Packages](#packages)
  - [Matchers](#matchers)
  - [IDE](#ide)
  - [Linting](#linting)
  - [Runners](#runners)
  - [Reporters](#reporters)
  - [Results Processors](#results-processors)
  - [Environments](#environments)
  - [Coverage](#coverage)
  - [Snapshot](#snapshot)
  - [Migration](#migration)
  - [Library extensions](#library-extensions)
  - [Mocks](#mocks)
  - [Watch Plugins](#watch-plugins)
  - [Processor](#processor)
  - [Presets](#presets)
  - [Generators](#generators)
  - [Debug](#debug)
- [Resources](#resources)

## Packages

### Matchers

- [jest-extended](https://github.com/jest-community/jest-extended) Adds additional matchers to core API making it easy to test everything.
- [expect-more](https://github.com/JamieMason/expect-more/tree/master/packages/expect-more-jest) A huge library of test matchers for a range of common use-cases.
- [jest-axe](https://github.com/nickcolley/jest-axe) Jest matcher for [axe](https://github.com/dequelabs/axe-core) for testing accessibility.
- [jest-enzyme](https://github.com/FormidableLabs/enzyme-matchers/tree/master/packages/jest-enzyme) An assertion library for enzyme.
- [jest-json-schema](https://github.com/americanexpress/jest-json-schema) JSON schema matcher.
- [expect-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/expect-puppeteer) Collection of matchers for Jest & Puppeteer.
- [@testing-library/jest-dom](https://github.com/testing-library/jest-dom) Jest matchers to test the state of the DOM.
- [jest-generator](https://github.com/doniyor2109/jest-generator) Jest matcher for testing generator function.
- [jest-shell-matchers](https://github.com/raingerber/jest-shell-matchers) Test shell scripts while mocking specific commands.
- [@emotion/jest](https://github.com/emotion-js/emotion/tree/main/packages/jest) Jest matcher for testing Emotion components.
- [jest-openapi](https://github.com/openapi-library/OpenAPIValidators/tree/master/packages/jest-openapi) Jest matchers for asserting that HTTP responses satisfy an [OpenAPI](https://swagger.io/docs/specification/about) spec.
- [jest-json](https://github.com/duailibe/jest-json) Jest matchers to assert on JSON strings.
- [@testing-library/jest-native](https://github.com/testing-library/jest-native) Jest matchers to test the state of React Native.
- [@traceloop/jest-opentelemetry](https://github.com/traceloop/jest-opentelemetry) Collection of matchers and runner for end to end tests with Jest & OpenTelemetry.

### IDE

- [vscode-jest](https://github.com/jest-community/vscode-jest) Works out of the box Jest based testing in VS Code.
- [wallaby](https://github.com/wallabyjs/public) The pinnacle of the idea of a test runner integrated into an editor.
- [coc-jest](https://github.com/neoclide/coc-jest) Jest plugin for [coc.nvim](https://github.com/neoclide/coc.nvim).
- [jester](https://github.com/David-Kunz/jester) A Neovim plugin to easily run and debug Jest tests.

### Linting

- [eslint-plugin-jest](https://github.com/jest-community/eslint-plugin-jest) ESLint plugin for Jest.
- [eslint-plugin-jest-formatting](https://github.com/dangreenisrael/eslint-plugin-jest-formatting) ESLint plugin that aims to provide formatting rules (auto-fixable where possible) to ensure consistency and readability in jest test suites.
- [eslint-plugin-jest-extended](https://github.com/jest-community/eslint-plugin-jest-extended) ESLint plugin for [jest-extended](https://github.com/jest-community/jest-extended).
- [eslint-plugin-jest-dom](https://github.com/testing-library/eslint-plugin-jest-dom) ESLint plugin to follow best practices and anticipate common mistakes when writing tests with [@testing-library/jest-dom](https://github.com/testing-library/jest-dom).

### Runners

- [jest-runner-eslint](https://github.com/jest-community/jest-runner-eslint) ESLint runner for Jest.
- [jest-runner-mocha](https://github.com/rogeliog/jest-runner-mocha) Mocha runner for Jest.
- [jest-runner-prettier](https://github.com/keplersj/jest-runner-prettier) Prettier runner for Jest.
- [jest-electron-runner](https://github.com/d4rkr00t/jest-electron-runner) Electron runner for Jest.
- [jest-runner-stylelint](https://github.com/keplersj/jest-runner-stylelint) Stylelint runner for Jest.
- [jest-runner-groups](https://github.com/eugene-manuilov/jest-runner-groups) A runner that lets to group tests and to run groups separately.
- [jest-runner-tsc](https://github.com/azz/jest-runner-tsc) A Jest runner for the TypeScript compiler.
- [jest-runner-tsd](https://github.com/jest-community/jest-runner-tsd) Runner for running TypeScript type tests.
- [jest-light-runner](https://github.com/nicolo-ribaudo/jest-light-runner) Runner that runs tests directly in bare Node.js, without virtualizing the environment.

### Reporters

- [jest-silent-reporter](https://github.com/rickhanlonii/jest-silent-reporter) A silent reporter for Jest.
- [jest-junit](https://github.com/jest-community/jest-junit) A JUnit format reporter for Jest which can integrate with CI systems.
- [jest-xunit](https://github.com/sscaff1/jest-xunit) An xUnit format reporter for Jest.
- [jest-skipped-reporter](https://github.com/rickhanlonii/jest-skipped-reporter) Report skipped tests in Jest.
- [jest-html-reporter](https://github.com/Hargne/jest-html-reporter) A Jest test results processor for generating a summary in HTML.
- [jest-stare](https://github.com/dkelosky/jest-stare) Configurable HTML reporter for filtering, side-by-side snapshot diffs, API, and simple CLI.
- [jest-slow-test-reporter](https://github.com/jodonnell/jest-slow-test-reporter) Prints the slowest tests in your codebase.
- [jest-simple-dot-reporter](https://github.com/jodonnell/jest-simple-dot-reporter) A simple dot reporter - one dot per each test.
- [jest-performance-reporter](https://github.com/sholzmayer/jest-performance-reporter) Identify slow tests and create a report including execution times.
- [jest-progress-bar-reporter](https://github.com/pierreroth64/jest-progress-bar-reporter) Simple reporter with a little progressbar.
- [jest-html-reporters](https://github.com/Hazyzh/jest-html-reporters) A Jest test results processor for generating a summary in HTML.
- [jest-allure](https://github.com/zaqqaz/jest-allure) Add more power to your tests using Jest-Allure with very concise representation of what has been tested in a neat web report form.
- [jest-standard-reporter](https://github.com/chrisgalvan/jest-standard-reporter) Reporter that uses stdout for messages and stderr for errors.
- [jest-github-reporter](https://github.com/hipstersmoothie/jest-github-reporter) Report jest test errors directly in pull requests.
- [jest-email-reporter](https://github.com/tglink/jest-email-reporter) Reporter for jest test errors by e-mail.
- [jest-dashboard](https://github.com/theoutlander/jest-dashboard) Command line dashboard.
- [testrail-jest-reporter](https://github.com/AntonChaukin/testrail-jest-reporter) Report jest test results to TestRail.
- [jest-tesults-reporter](https://github.com/tesults/jest-tesults-reporter) Submits test results data to Tesults for analysis and reporting.
- [github-actions-jest-reporter](https://github.com/MatteoH2O1999/github-actions-jest-reporter) Reports jest test results using Github Actions groups, allowing for an easy navigation of the test logs.
- [jest-ado-reporter](https://github.com/bashaus/jest-ado-reporter) Reports jest test suite progress information to the pipeline step in Azure DevOps.

### Results Processors

- [majestic](https://github.com/Raathigesh/majestic) Zero config UI for Jest.

### Environments

- [jest-environment-webdriver](https://github.com/alexeyraspopov/jest-webdriver) custom environment for WebDriver integration.
- [jest-environment-puppeteer](https://github.com/smooth-code/jest-puppeteer/tree/master/packages/jest-environment-puppeteer) Puppeteer environment for Jest.

### Coverage

- [jest-it-up](https://github.com/rbardini/jest-it-up) Automatically bump up global thresholds whenever coverage goes above them.
- [jest-coverage-thresholds-bumper](https://github.com/Litee/jest-coverage-thresholds-bumper) Similar to `jest-it-up`, but allows to specify where coverage summary is located, supports Jest config in JSON files and `package.json`.
- [jest-a-coverage-slip-detector](https://github.com/GetJobber/jest-a-coverage-slip-detector) Designed for parallelized CI, prevents test coverage from slipping. Features include per-file ratcheting, automatic coverage merging, and custom messages.

### Snapshot

- [snapshot-diff](https://github.com/jest-community/snapshot-diff) Takes two values, and return their difference as a string, ready to be snapshotted with `toMatchSnapshot()`. Especially helpful when testing the difference between different React component states.
- [jest-snapshots-svg](https://github.com/jest-community/jest-snapshots-svg) Take a React component tree, and render it into an SVG.
- [jest-image-snapshot](https://github.com/americanexpress/jest-image-snapshot) Take a snapshot test of an image buffer, and catch when the image changes over a threshold. Commonly used for visual regression testing.
- [enzyme-to-json](https://github.com/adriantoine/enzyme-to-json) Convert Enzyme wrappers to a format compatible with Jest snapshot testing.
- [jest-styled-components](https://github.com/styled-components/jest-styled-components) A set of utilities for testing Styled Components with Jest.
- [jest-img-snapshot](https://github.com/donysukardi/jest-img-snapshot) Image snapshot comparison using pixelmatch with all Jest's snapshot goodies out of the box.
- [jest-file-snapshot](https://github.com/satya164/jest-file-snapshot) Write snapshots to a separate file instead of the default snapshot file used by Jest.
- [Differencify](https://github.com/NimaSoroush/differencify) Visual regression testing tool using Jest and Puppeteer to do Image snapshot comparison.
- [StoryShots](https://github.com/storybooks/storybook/tree/master/addons/storyshots/storyshots-core) StoryShots adds automatic Jest Snapshot Testing for Storybook.
- [jest-large-snapshot-warning](https://github.com/jomaxx/jest-large-snapshot-warning) Add warnings to large snapshots.
- [jest-serializer-react-helmet](https://github.com/keplersj/jest-serializer-react-helmet) Include React Helmet data in component snapshots.
- [jest-serializer-json-ld-script](https://github.com/keplersj/jest-serializer-json-ld-script) Serializes JSON+LD elements as JavaScript objects.
- [@emotion/jest](https://github.com/emotion-js/emotion/tree/main/packages/jest) Include Emotion styles in component snapshots.
- [jest-serializer-xml](https://github.com/keplersj/jest-serializer-xml) Format XML documents to better visualize in Snapshots.
- [1log](https://github.com/ivan7237d/1log) Extensible logger that allows capturing log messages as snapshots.
- [jest-serializer-ansi-escapes](https://github.com/mrazauskas/jest-serializer-ansi-escapes) Snapshot serializer for ANSI escape sequences.

### Migration

- [jest-codemods](https://github.com/skovhus/jest-codemods) Makes it easy to migrate from other test runner and frameworks to Jest.
- [@putout/plugin-jest](https://github.com/coderaiser/putout/blob/master/packages/plugin-jest/README.md#putoutplugin-jest-) 🐊Putout plugin helps to migrate to latest Jest API.

### Library extensions

- [testdouble-jest](https://github.com/testdouble/testdouble-jest) Support for [testdouble.js](https://github.com/testdouble/testdouble.js) for users of Jest.
- [jest-puppe-shots](https://github.com/macku/jest-puppe-shots) A Jest plugin for creating screenshots of [React](https://reactjs.org) components with a little help of [Puppeteer](https://github.com/puppeteer/puppeteer).
- [babel-jest-assertions](https://github.com/mattphillips/babel-jest-assertions) Babel plugin that automatically adds the number of assertions found in each test with `expect.assertions(n)` and `expect.hasAssertions()`.
- [typescript-snapshots-plugin](https://github.com/asvetliakov/typescript-snapshots-plugin) Extends the TypeScript dev server to support hovering and jumping to a snapshot.
- [jest-chain](https://github.com/mattphillips/jest-chain) Chain Jest matchers together to create one powerful assertion.
- [jest-expect-message](https://github.com/mattphillips/jest-expect-message) Add custom message to Jest expects.
- [@bigtest/interactor](https://frontside.com/bigtest/interactors) A testing and assertion library that makes it easy to test UIs at scale while keeping accessibility at the core.
- [@testdeck/jest](https://github.com/testdeck/testdeck) Decorator based wrapper around Jest for object oriented testing. Checkout the [documentation](https://testdeck.org) and a working [seed](https://github.com/testdeck/testdeck-jest-seed) for you to start with.
- [jest-plugin-must-assert](https://github.com/ballercat/jest-plugin-must-assert) A Jest plugin for strict runtime checks. Fails any tests without assertions and prevents async tasks (Promises & timeouts) from leaking across tests.
- [wait-for-expect](https://github.com/TheBrainFamily/wait-for-expect) A await/async function to wait a expect. Useful on e2e test.
- [jest-os-detection](https://github.com/doctolib/jest-os-detection) Dynamically enable or skip tests based on the OS they run on so you can share the same test suite across various platforms.
- [@fast-check/jest](https://www.npmjs.com/package/@fast-check/jest) Bring property based testing (aka fuzzing) into Jest.

### Mocks

- [jest-fetch-mock](https://github.com/jefflau/jest-fetch-mock) Easily mock out `fetch` and set up responses, powered by [Jest mock functions](https://facebook.github.io/jest/docs/en/mock-functions.html).
- [jest-canvas-mock](https://github.com/hustcc/jest-canvas-mock) Mock canvas when run unit test cases with jest.
- [jest-localstorage-mock](https://github.com/clarkbw/jest-localstorage-mock) A module to mock window.localStorage and window.sessionStorage in Jest.
- [jest-date-mock](https://github.com/hustcc/jest-date-mock) Mock `window.Date` when run unit test cases with jest. Make tests of Date easier.
- [jest-mock-extended](https://github.com/marchaos/jest-mock-extended) Create Typesafe mocks for TS interfaces and objects as well as returning argument specific return values.
- [jest-wake-lock-mock](https://github.com/jorisre/jest-wake-lock-mock) Mock Screen Wake Lock API `navigator.wakeLock` with ease and run your tests using Jest.
- [jest-location-mock](https://github.com/evelynhathaway/jest-location-mock) Mock `window.location` easily.
- [@automock/jest](https://github.com/omermorad/automock) Class dependencies auto-mocking.
- [@jest-mock/express](https://github.com/bikk-uk/jest-mock-express) Mock Express.js request and response objects.

### Watch plugins

- [jest-watch-continue](https://github.com/unional/jest-watch-continue) Run test in continue mode.
- [jest-watch-directories](https://github.com/cameronhunter/jest-watch-directories/tree/master/packages/jest-watch-directories) Select directories to test.
- [jest-watch-exec](https://github.com/unional/jest-watch-exec) Execute scripts during the watch cycle.
- [jest-watch-lerna-packages](https://github.com/cameronhunter/jest-watch-directories/blob/master/packages/jest-watch-lerna-packages) Select Lerna packages to test.
- [jest-watch-master](https://github.com/rickhanlonii/jest-watch-master) Check changes since master.
- [jest-watch-random](https://github.com/unional/jest-watch-random) Randomly run some of the test suites.
- [jest-watch-repeat](https://github.com/unional/jest-watch-repeat) Repeat test runs multiple times.
- [jest-watch-select-projects](https://github.com/rogeliog/jest-watch-select-projects) Select which Jest projects to run.
- [jest-watch-suspend](https://github.com/unional/jest-watch-suspend) Suspend watch mode so that your changes would not trigger test runs.
- [jest-watch-toggle-config](https://github.com/jest-community/jest-watch-toggle-config) Toggle boolean settings (e.g. verbosity, test coverage).
- [jest-watch-typeahead](https://github.com/jest-community/jest-watch-typeahead) Filter your tests by file name or test name.
- [jest-watch-yarn-workspaces](https://github.com/cameronhunter/jest-watch-directories/tree/master/packages/jest-watch-yarn-workspaces) Select Yarn workspaces to test.
- [node-recorder](https://github.com/ericclemmons/node-recorder/#using-jest) Toggle recording modes for `node-recorder`.

### Processor

- [jest-nunjucks](https://github.com/denar90/jest-nunjucks) Processor that compiles nunjucks templates.
- [ts-jest](https://github.com/kulshekhar/ts-jest) TypeScript preprocessor with sourcemap support.
- [vue-jest](https://github.com/vuejs/vue-jest) Vue transformer with source map support.
- [marko-jest](https://github.com/abiyasa/marko-jest) Processor for [Marko component](https://markojs.com).
- [awesome-pug-jest](https://github.com/iketari/awesome-pug-jest) Processor for [Pug/Jade](https://pugjs.org).
- [jest-raw-loader](https://github.com/keplersj/jest-raw-loader) Processor mimicking `webpack`'s `raw-loader`.
- [jest-less-loader](https://github.com/hustcc/jest-less-loader) Jest transformer for `.less` file.
- [jest-url-loader](https://github.com/hustcc/jest-url-loader) Similar with webpack's `url-loader` for Jest transformer.

### Presets

- [jest-dynamodb](https://github.com/shelfio/jest-dynamodb) Jest preset for working with DynamoDB.
- [jest-mongodb](https://github.com/shelfio/jest-mongodb) Jest preset for working with MongoDB.
- [jest-elasticsearch](https://github.com/shelfio/jest-elasticsearch) Jest preset for working with ElasticSearch.
- [jest-puppeteer](https://github.com/smooth-code/jest-puppeteer) A Jest preset that enables a ready-to-use environment to write integration tests using Puppeteer.
- [jest-preset-angular](https://github.com/thymikee/jest-preset-angular) Jest preset for [Angular](https://angular.io) projects.
- [jest-preset-gatsby](https://github.com/keplersj/jest-preset-gatsby) Jest preset to streamline unit testing a Gatsby project.

### Generators

- [jest-test-gen](https://github.com/egm0121/jest-test-gen) CLI tool to generate a test file with test scaffold for every class method or function exported.
- [text2jest](https://www.text2jest.com/) A web-based tool to instantly convert a nested list of plain text test names into a Jest file.

### Debug

- [jest-preview](https://github.com/nvh95/jest-preview) Preview Jest tests in a browser.

## Resources

- [Jest cheat sheet](https://github.com/sapegin/jest-cheat-sheet).
- [React Jest workshop](https://github.com/kentcdodds/react-jest-workshop).
- [Jest: How Do I Mock X](https://github.com/magicmark/jest-how-do-i-mock-x).

## Contribute

Contributions welcome! Read the [contribution guidelines](/CONTRIBUTING.md).

## License

[MIT](/LICENSE)
