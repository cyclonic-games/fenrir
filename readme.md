# fenrir
Proxy based unit testing library built for vorge

## WIP (ignore below code)

```javascript
const Specification = require('fenrir/core/Specification');
const Foo = require('../../plugins/std/common/modules/Foo');

module.exports = new Specification('Description of specification', test => {
    const foo = new Foo('foo', test);

    test.case('Description of test case').run(expect => {
        const spy = foo.spy(foo);
    });
});
```
