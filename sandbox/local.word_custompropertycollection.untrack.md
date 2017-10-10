[Home](./index) &gt; [local](local.md) &gt; [Word\_CustomPropertyCollection](local.word_custompropertycollection.md) &gt; [untrack](local.word_custompropertycollection.untrack.md)

# Word\_CustomPropertyCollection.untrack method

Release the memory associated with this object, if it has previously been tracked. This call is shorthand for context.trackedObjects.remove(thisObject). Having many tracked objects slows down the host application, so please remember to free any objects you add, once you're done using them. You will need to call "context.sync()" before the memory release takes effect.

**Signature:**
```javascript
untrack(): Word.CustomPropertyCollection;
```
**Returns:** `Word.CustomPropertyCollection`
