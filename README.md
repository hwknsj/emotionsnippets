# Emotion Snippets for React apps by iJS

Thanks for giving this a go. Hope this helps and makes your coding more efficient and fun.

## Hello.

Animations coming soon.

> Pull requests are most welcome!

## Installation

- Launch the Command Pallete (Ctrl + Shift + P or ⌘Cmd + Shift + P) and type "Install Extensions" (or navigate from the sidebar to Extensions tab).
- In search box type in "iJS" and choose the Emotion Snippets
- Install the extension (you may need to relaunch VS Code)
- Get a coffee, a cookie and celebrate by expanding some emotion.js snippets!

## Supported languages (file extensions)

- JavaScript (.js)
- TypeScript (.ts)
- JavaScript React (.jsx)
- TypeScript React (.tsx)

Below is a list of all available snippets and the triggers of each one. The **⇥** means the `TAB` key.

## Emotion.js Snippet Contents

|      Trigger | Content                                                   |
| -----------: | --------------------------------------------------------- |
|     `ecss →` | Declared an emotion css style variable                    |
|      `ecn →` | Creates ClassNames HOC with render props                  |
|  `eobjcss →` | Declared an emotion css style variable with object styles |
|   `eusthm →` | Declare them with useTheme() from emotion-theming         |
|    `imecn →` | Import ClassNames from @emotion/core                      |
|   `imecss →` | Import css from @emotion/core                             |
|     `imej →` | Imports emotion jsx prop                                  |
|  `imejcss →` | Imports emotion jsx and css props                         |
|    `imesc →` | Import styled from emotion/styled (requires package)      |
| `imeusthm →` | Import useTheme from emotion-theming (requires package)   |
|       `sc →` | Declare styled component                                  |
|      `scw →` | Declare custom component wrapped in a styled component    |

- More snippets to come, stay tuned!

## Expanded Snippets

### imecn - Import ClassNames from @emotion/core

```javascript
import { ClassNames } from "@emotion/core";
```

### imecss - Import css from @emotion/core

```javascript
import { css } from "@emotion/core";
```

### imej - Imports emotion jsx prop

```javascript
// below comment line is required
// it tells babel how to convert properly
/** @jsx jsx */
import { jsx } from "@emotion/core";
```

### imejcss - Imports emotion jsx and css props

```javascript
// below comment line is required
// it tells babel how to convert properly
/** @jsx jsx */
import { jsx, css } from "@emotion/core";
```

### imesc - Import styled from emotion/styled (requires package)

```javascript
import styled from "@emotion/styled";
```

### imeusthm - Import useTheme from emotion-theming (requires package)

```javascript
import { useTheme } from "emotion-theming";
```

### ecss - Declared an emotion css style variable

```javascript
const style| = css`
  |
`;
```

### eobjcss - Declared an emotion css style variable with object styles

```javascript
const objectStyles| = css({
    |
})
```

### eusthm - Declare them with useTheme() from emotion-theming

```javascript
const theme = useTheme();
```

### sc - Declare styled component

```javascript
const sc| = styled.div`
  |
`;
```

### scw - Wrap custom component with emotion styled component

```javascript
const sc| = styled(CustomComp|)`
  |
`;
```

## Release Notes

## [1.1.2] - 2020 March 4rd

### Changed

- [BREAKING]: Final renaming of base snippets

## [1.1.1] - 2020 March 4rd

### Fixes

- `ecn →` | Fix typo to properly close ClassNames element

## [1.1.0] - 2020 March 4rd

### Changed

- [BREAKING]: Refactored most snippets to shorter versions.

## [1.0.2] - 2020 March 4rd

### Added

- `eimpclnm →` | Import ClassNames from @emotion/core
- `eclnm →` | Creates ClassNames HOC with render props

### Changed

- [BREAKING]: Renamed all `em*` snippet instances to `e*`

### Removed

- `stprop →`

## [1.0.1] - 2020 March 3rd

### Changed

- added filename base to styled component definition

## [1.0.0] - 2020 March 3rd

### Added

#### Snippets:

-       `emimpcss→` | Import css from @emotion/core
- `emimpstyled→` | Import styled from emotion
-     `sc→` | Declare styled component
- `scw→` | Declare custom component wrapped in a styled component
-         `stprop→` | Universal destructuring of a prop template literal
-     `emimptheme→` | Import useTheme from emotion
-     `emusetheme→` | Declare them with useTheme() from emotion
-          `emcss→` | Declared an emotion css style variable
-       `emobjcss→` | Declared an emotion css style variable with object styles
-       `emimpjsx→` | Imports emotion jsx prop
- `emimpjsxcss→` | Imports emotion jsx and css props

- Initial Emotion Snippets Release

**Enjoy!**
/ Scott Agirs
