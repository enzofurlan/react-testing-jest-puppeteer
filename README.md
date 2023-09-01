## Setup

`virtualenv .env`
`source .env/bin/activate`

`yarn install`
`yarn dev`

## Tests

All tests are in the `src/__tests__/` folder. The test cases are:

- `case-1-Checkbox.test.tsx` Tests for a custom checkbox component
- `case-2-ProductTile.test.tsx` Tests for the product tile component
- `case-3-Header.test.tsx` Tests for the page header
- `case-4-ProductStream.test.tsx` Tests for the product grid
- `case-5-FiltersWrapper.test.tsx` Tests for the context wrapper for filters
- `case-6-useFilters.test.tsx` Tests for the useFilters custom hook
- `case-7-useOutsideClick.test.tsx` Tests for the useOutsideClick custom hook

To run:
`yarn test`
