# What is it?

Get shadows and paddings on images. Made for non-designers.

# Installation

`npm i shadowmage --save`

Then..

```
import { shadowmage } from 'shadowmage';

shadowmage({
    shadow_type: 'soft',
    padding: false
});
```

## Options

Shadowmage supports two options.

* *shadow_type* - _hard | soft_ (Defaults to soft)
* *padding* - _boolean_ (Defaults to false)

Inspired by *DesignCourse*'s tutorial.