# Detabinator

## Work is now underway to standardize the inert attribute/property. This does everything Detabinator does and more! Check it out at [WICG/inert](https://github.com/WICG/inert).

## ⚠️ Deprecated ⚠️

Toggle tabindex to -1 for an entire tree of children. Preserves existing
`tabindex` on children if one is present.

## Usage

```
const detabinator = new Detabinator(element);
detabinator.inert = true;  // Sets all focusable children of element to tabindex=-1
detabinator.inert = false; // Restores all focusable children of element
```

## Limitations

Doesn't support Shadow DOM v0 but should work with Shadow DOM v1 🤗
