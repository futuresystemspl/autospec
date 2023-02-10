## Preview

https://futuresystems.pl/work/2023/autospec/index.html

## Notes

- Date inputs can't be styled on Firefox - calendar icon will be visible for both screen and print. Possible workaround: replace date input with standard text inputs or use JS-based solution.

- Checkbox custom styling relies on background images. Some browsers have printing background images disabled, so it might be required to toggle option on in printing settings (it seems to be the case for pseudoelements as well; toggling is one time only). Workaround: deprecate custom styling and go with native style and colors.