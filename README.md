# Reproduction for https://github.com/storybookjs/storybook/issues/18698

- Visit the docpage for the Primary Button story (the underlying component contains PropTypes with JSDocs comment).
  ```js
  Button.propTypes = {
    /**
     * Is this the principal call to action on the page?
     */
    primary: PropTypes.bool,
    //...
  };
  ```
- Notice the lack of description in the props table.
