# React Highlight Search
The React Highlight Search is a powerful and customizable npm package that enables users to search and highlight specific keywords within a series of strings in a React application. This package provides a simple and user-friendly way to visually emphasize searched terms, enhancing the user experience when handling large sets of text data.

## Key Features
1. Keyword Search: The package allows users to specify a target keyword that they want to search for within the provided string.
2. Customizable Highlight Color: Users can easily customize the highlight color to suit the theme of their React application, making the search results visually appealing and seamlessly integrated with their design.
3. Multiple Occurrences: The package can handle multiple occurrences of the search term in the input string, ensuring all instances are properly highlighted.
4. TypeScript Support: The package comes with built-in TypeScript support, enabling developers to benefit from static typing and enhanced code safety when using the package in TypeScript-based projects.

## Usage
The React Highlight Search package is straightforward to implement. Developers can import the HighlightSearch component into their React application and pass the necessary props to initiate the search and highlighting process. The component then takes care of the rest, providing the desired result with highlighted occurrences of the search keyword.

Sample Code:

```javascript
import React from 'react';
import HighlightSearch from 'react-highlight-search';

const SampleComponent = () => {
  const text = 'Lorem ipsum dolor sit amet, consectetur adipiscing elit.';
  const searchWord = 'ipsum';
  const highlightColor = 'yellow';

  return (
    <div>
      <HighlightSearch
        text={text}
        searchWord={searchWord}
        highlightColor={highlightColor}
      />
    </div>
  );
};

export default SampleComponent;
```
With the React Highlight Search package, developers can effortlessly implement an efficient and visually appealing keyword search functionality within their React applications, enhancing the overall user experience.
