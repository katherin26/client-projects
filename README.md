# **Personal webpage project client**

1. Using Mobile First
2. Sass and FontAwesome

# **Mobile First : Media Queries**

```
@mixin bp-sm {
  @media (min-width: 40.625em) {
    @content;
  }
}
@mixin bp-md {
  @media (min-width: 56.25em) {
    @content;
  }
}
@mixin bp-lg {
  @media (min-width: 112.5em) {
    @content;
  }
}
```

# **FontAwesome**

1. **Add in variables.scss:** $fa-font-path:

```
"../../webfonts" !default;

```

2. **Add fontawesome folder inside the sass :** fontawesome
3. **Add in main.scss the imports:**

```
@import "./fontawesome/scss/fontawesome.scss";
@import "./fontawesome/scss/solid.scss";
@import "./fontawesome/scss/brands.scss";
```

4. **Copy and paste the webfonts in the public root** : webfonts
