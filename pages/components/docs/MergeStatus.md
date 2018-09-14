# MergeStatus


## Default example
```.jsx
<MergeStatus mb={2} state="pending" />
<MergeStatus mb={2} state="invalid" />
<MergeStatus mb={2} state="merged" />
<MergeStatus mb={2} state="ready" />
```

## System props

MergeStatus components get `COMMON` system props. Read our [System Props](/system-props) doc page for a full list of available props.

## Component props

| Prop name | Type | Description |
| :- | :- | :- |
| state | String | Can be one of `ready`, `invalid`, `merged`, or `pending`. Sets the appropriate background and text color on the component. |

export const meta = {displayName: 'MergeStatus'}