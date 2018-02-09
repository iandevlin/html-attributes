# HTML Attributes

This is a list of valid HTML boolean and enumerated attributes.

This list is manually compiled from the [latest recommendation of the W3C HTML Specification](https://www.w3.org/TR/html52/), and the [latest recommendation of the WAI-ARIA Specification](https://www.w3.org/TR/wai-aria-1.1/).

The files are in JSON format for ease of use.

## Boolean attributes

Boolean attributes are attributes that, if the attribute is present, its value must either be the empty string or a value that is an ASCII case-insensitive match for the attribute's canonical name, with no leading or trailing whitespace.

## Enumerated attributes

Enumerated attributes are attributes whose values must be one of a specified list of valid values for that attribute.

Valid values for the `type` attribute depends on the element that it is defined upon, so a valid value for type on an `input` element may not be valid on a `source` element, and vice versa. Additionally, for some elements the values for `type` are enumerated from locations outside of the HTML Specification (e.g. for `source` valid MIME Types are to be used), and for this reason, they are not included here.


## Contributing

Feel free to contribute to this repository by adding missing attributes, values, or even suggesting further file formats.