@gov.au/text-inputs
============

> Single and multi-line text inputs.


## Contents

* [Install](#install)
* [Usage](#usage)
* [Dependency graph](#dependency-graph)
* [Tests](#tests)
* [Release History](#release-history)
* [License](#license)


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Install


```shell
yarn add @gov.au/text-inputs
```

```shell
npm install @gov.au/text-inputs --save-dev
```


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Usage


* [React](#react)


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


### React

Usage:

```jsx
import AUtextInput from './text-inputs.js';

<label htmlFor="name" >Your name?</label>
<AUtextInput id="name" block />
```

All props:

```jsx
<TextInput
  as              {/* The kind of input, can be either 'input' or 'textarea', default: 'input' */}
  dark={ false }  {/* A dark variation of the component */}
  block           {/* Add the block variation class */}
  status          {/* Mark this field as either 'valid' or 'invalid' */}
/>
```
_(💡 additional props are spread onto the component)_

For more details have a look at the [usage example](https://github.com/govau/uikit/tree/master/packages/control-input/tests/react/index.js).


**[⬆ back to top](#contents)**



----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Dependency graph

```shell
text-inputs
└─ core
```


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Tests

The visual test: https://uikit.service.gov.au/packages/text-inputs/tests/site/


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## Release History

* v1.0.0 - Moved to AU namespace, added new color themes and spacing
* v0.1.1 - Fixed print background in disabled inputs
* v0.1.0 - 💥 Initial version


**[⬆ back to top](#contents)**


----------------------------------------------------------------------------------------------------------------------------------------------------------------


## License

Copyright (c) Commonwealth of Australia.
Licensed under [MIT](https://raw.githubusercontent.com/govau/uikit/packages/core/master/LICENSE).


**[⬆ back to top](#contents)**

# };
