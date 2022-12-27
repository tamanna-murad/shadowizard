# what is this?

get perfect shadows every time for the non-designer.

# installation

`npm i shadowizard --save`

then...

```
import {shadowizard} from 'shadowizard';

shadowizard({
     shadow_type: 'soft',
     padding: false
});
```

## options

shadowizard supports 2 options , both of which are optional:

- _shadow_type_ - _hard | soft_ (Default to soft)
- _padding_ - _boolean_ (Default to false)
