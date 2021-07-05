## ID

Super simple ID gen

- the ID is broken into two part
  - date the id was created
  - random number defaulted to 100000

### Example

```javascript
import id from '@destinio/id'

array.map((item) => {
  const keyId = id() // 1625502956169-14374
  return (
    <div className="list-item" key={keyId}>
      I'm a list item that need a unique key
    </div>
  )
})
```

### Cheers
