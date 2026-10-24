# commons.lang Skill

Use this skill to work with Norm module `commons.lang` version 3. Use only declarations listed below.

## `commons.lang`

Source: `JavaArrays.norm`

### `JavaObjectArray`

```norm
class JavaObjectArray<T>
```

Type parameters:

- `T`

#### `JavaObjectArray`

```norm
JavaObjectArray(JavaObjectArrayBindingToken token)
```

Parameters:

- `token`: `JavaObjectArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
T? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `T?`

#### `set`

```norm
Void set(Integer index, T? value)
```

Parameters:

- `index`: `Integer`
- `value`: `T?`

Returns: `Void`

### `javaObjectArrayNew`

```norm
JavaObjectArray<T> javaObjectArrayNew<T>(Integer size)
```

Type parameters:

- `T`

Parameters:

- `size`: `Integer`

Returns: `JavaObjectArray<T>`

### `JavaComparableArray`

```norm
class JavaComparableArray<T>
```

Type parameters:

- `T`

#### `JavaComparableArray`

```norm
JavaComparableArray(JavaComparableArrayBindingToken token)
```

Parameters:

- `token`: `JavaComparableArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
T? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `T?`

#### `set`

```norm
Void set(Integer index, T? value)
```

Parameters:

- `index`: `Integer`
- `value`: `T?`

Returns: `Void`

### `javaComparableArrayNew`

```norm
JavaComparableArray<T> javaComparableArrayNew<T>(Integer size)
```

Type parameters:

- `T`

Parameters:

- `size`: `Integer`

Returns: `JavaComparableArray<T>`

### `JavaCharArray`

```norm
class JavaCharArray
```

#### `JavaCharArray`

```norm
JavaCharArray(JavaCharArrayBindingToken token)
```

Parameters:

- `token`: `JavaCharArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
CodePoint get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `CodePoint`

#### `set`

```norm
Void set(Integer index, CodePoint value)
```

Parameters:

- `index`: `Integer`
- `value`: `CodePoint`

Returns: `Void`

### `javaCharArrayNew`

```norm
JavaCharArray javaCharArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaCharArray`

### `JavaByteArray`

```norm
class JavaByteArray
```

#### `JavaByteArray`

```norm
JavaByteArray(JavaByteArrayBindingToken token)
```

Parameters:

- `token`: `JavaByteArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Integer get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Integer`

#### `set`

```norm
Void set(Integer index, Integer value)
```

Parameters:

- `index`: `Integer`
- `value`: `Integer`

Returns: `Void`

### `javaByteArrayNew`

```norm
JavaByteArray javaByteArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaByteArray`

### `JavaDoubleArray`

```norm
class JavaDoubleArray
```

#### `JavaDoubleArray`

```norm
JavaDoubleArray(JavaDoubleArrayBindingToken token)
```

Parameters:

- `token`: `JavaDoubleArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Double get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Double`

#### `set`

```norm
Void set(Integer index, Double value)
```

Parameters:

- `index`: `Integer`
- `value`: `Double`

Returns: `Void`

### `javaDoubleArrayNew`

```norm
JavaDoubleArray javaDoubleArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaDoubleArray`

### `JavaFloatArray`

```norm
class JavaFloatArray
```

#### `JavaFloatArray`

```norm
JavaFloatArray(JavaFloatArrayBindingToken token)
```

Parameters:

- `token`: `JavaFloatArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Float get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Float`

#### `set`

```norm
Void set(Integer index, Float value)
```

Parameters:

- `index`: `Integer`
- `value`: `Float`

Returns: `Void`

### `javaFloatArrayNew`

```norm
JavaFloatArray javaFloatArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaFloatArray`

### `JavaIntArray`

```norm
class JavaIntArray
```

#### `JavaIntArray`

```norm
JavaIntArray(JavaIntArrayBindingToken token)
```

Parameters:

- `token`: `JavaIntArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Integer get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Integer`

#### `set`

```norm
Void set(Integer index, Integer value)
```

Parameters:

- `index`: `Integer`
- `value`: `Integer`

Returns: `Void`

### `javaIntArrayNew`

```norm
JavaIntArray javaIntArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaIntArray`

### `JavaLongArray`

```norm
class JavaLongArray
```

#### `JavaLongArray`

```norm
JavaLongArray(JavaLongArrayBindingToken token)
```

Parameters:

- `token`: `JavaLongArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Long get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Long`

#### `set`

```norm
Void set(Integer index, Long value)
```

Parameters:

- `index`: `Integer`
- `value`: `Long`

Returns: `Void`

### `javaLongArrayNew`

```norm
JavaLongArray javaLongArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaLongArray`

### `JavaAnyArray`

```norm
class JavaAnyArray
```

#### `JavaAnyArray`

```norm
JavaAnyArray(JavaAnyArrayBindingToken token)
```

Parameters:

- `token`: `JavaAnyArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Any? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Any?`

#### `set`

```norm
Void set(Integer index, Any? value)
```

Parameters:

- `index`: `Integer`
- `value`: `Any?`

Returns: `Void`

### `javaAnyArrayNew`

```norm
JavaAnyArray javaAnyArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaAnyArray`

### `JavaShortArray`

```norm
class JavaShortArray
```

#### `JavaShortArray`

```norm
JavaShortArray(JavaShortArrayBindingToken token)
```

Parameters:

- `token`: `JavaShortArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Integer get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Integer`

#### `set`

```norm
Void set(Integer index, Integer value)
```

Parameters:

- `index`: `Integer`
- `value`: `Integer`

Returns: `Void`

### `javaShortArrayNew`

```norm
JavaShortArray javaShortArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaShortArray`

### `JavaBooleanArray`

```norm
class JavaBooleanArray
```

#### `JavaBooleanArray`

```norm
JavaBooleanArray(JavaBooleanArrayBindingToken token)
```

Parameters:

- `token`: `JavaBooleanArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
Boolean get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `Boolean`

#### `set`

```norm
Void set(Integer index, Boolean value)
```

Parameters:

- `index`: `Integer`
- `value`: `Boolean`

Returns: `Void`

### `javaBooleanArrayNew`

```norm
JavaBooleanArray javaBooleanArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaBooleanArray`

### `JavaStringArray`

```norm
class JavaStringArray
```

#### `JavaStringArray`

```norm
JavaStringArray(JavaStringArrayBindingToken token)
```

Parameters:

- `token`: `JavaStringArrayBindingToken`

#### `size`

```norm
Integer size()
```

Returns: `Integer`

#### `get`

```norm
String? get(Integer index)
```

Parameters:

- `index`: `Integer`

Returns: `String?`

#### `set`

```norm
Void set(Integer index, String? value)
```

Parameters:

- `index`: `Integer`
- `value`: `String?`

Returns: `Void`

### `javaStringArrayNew`

```norm
JavaStringArray javaStringArrayNew(Integer size)
```

Parameters:

- `size`: `Integer`

Returns: `JavaStringArray`

## `commons.lang`

Source: `ObjectUtils.norm`

### `ObjectUtils`

```norm
class ObjectUtils
```

#### `ObjectUtils`

```norm
ObjectUtils(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `objectUtilsCompare`

```norm
Integer objectUtilsCompare<T extends Comparable<T>>(T? arg0, T? arg1)
```

Type parameters:

- `T` extends `Comparable<T>`

Parameters:

- `arg0`: `T?`
- `arg1`: `T?`

Returns: `Integer`

### `objectUtilsCompare`

```norm
Integer objectUtilsCompare<T extends Comparable<T>>(T? arg0, T? arg1, Boolean arg2)
```

Type parameters:

- `T` extends `Comparable<T>`

Parameters:

- `arg0`: `T?`
- `arg1`: `T?`
- `arg2`: `Boolean`

Returns: `Integer`

### `objectUtilsFirstNonNull`

```norm
T? objectUtilsFirstNonNull<T>(JavaObjectArray<T>? arg0)
```

Type parameters:

- `T`

Parameters:

- `arg0`: `JavaObjectArray<T>?`

Returns: `T?`

### `objectUtilsIsEmpty`

```norm
Boolean objectUtilsIsEmpty(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

### `objectUtilsIsNotEmpty`

```norm
Boolean objectUtilsIsNotEmpty(Any? arg0)
```

Parameters:

- `arg0`: `Any?`

Returns: `Boolean`

### `objectUtilsMax`

```norm
T? objectUtilsMax<T extends Comparable<T>>(JavaComparableArray<T>? arg0)
```

Type parameters:

- `T` extends `Comparable<T>`

Parameters:

- `arg0`: `JavaComparableArray<T>?`

Returns: `T?`

### `objectUtilsMin`

```norm
T? objectUtilsMin<T extends Comparable<T>>(JavaComparableArray<T>? arg0)
```

Type parameters:

- `T` extends `Comparable<T>`

Parameters:

- `arg0`: `JavaComparableArray<T>?`

Returns: `T?`

## `commons.lang`

Source: `StringUtils.norm`

### `StringUtils`

```norm
class StringUtils
```

#### `StringUtils`

```norm
StringUtils(__JarBindingToken token)
```

Parameters:

- `token`: `__JarBindingToken`

### `stringUtilsFieldGetEmpty`

```norm
String? stringUtilsFieldGetEmpty()
```

Returns: `String?`

### `stringUtilsAbbreviate`

```norm
String? stringUtilsAbbreviate(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsAbbreviate`

```norm
String? stringUtilsAbbreviate(String? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `String?`

### `stringUtilsAbbreviate`

```norm
String? stringUtilsAbbreviate(String? arg0, String? arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Integer`

Returns: `String?`

### `stringUtilsAbbreviate`

```norm
String? stringUtilsAbbreviate(String? arg0, String? arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsCapitalize`

```norm
String? stringUtilsCapitalize(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsCenter`

```norm
String? stringUtilsCenter(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsCenter`

```norm
String? stringUtilsCenter(String? arg0, Integer arg1, CodePoint arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `CodePoint`

Returns: `String?`

### `stringUtilsCenter`

```norm
String? stringUtilsCenter(String? arg0, Integer arg1, String? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `String?`

Returns: `String?`

### `stringUtilsChomp`

```norm
String? stringUtilsChomp(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsChop`

```norm
String? stringUtilsChop(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsCompare`

```norm
Integer stringUtilsCompare(String? arg0, String? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Boolean`

Returns: `Integer`

### `stringUtilsCompareIgnoreCase`

```norm
Integer stringUtilsCompareIgnoreCase(String? arg0, String? arg1, Boolean arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Boolean`

Returns: `Integer`

### `stringUtilsContains`

```norm
Boolean stringUtilsContains(CharSequence? arg0, Integer arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `Integer`

Returns: `Boolean`

### `stringUtilsContainsAny`

```norm
Boolean stringUtilsContainsAny(CharSequence? arg0, CharSequence? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsContainsAny`

```norm
Boolean stringUtilsContainsAny(CharSequence? arg0, JavaCharArray? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `JavaCharArray?`

Returns: `Boolean`

### `stringUtilsCountMatches`

```norm
Integer stringUtilsCountMatches(CharSequence? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `CodePoint`

Returns: `Integer`

### `stringUtilsCountMatches`

```norm
Integer stringUtilsCountMatches(CharSequence? arg0, CharSequence? arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `CharSequence?`

Returns: `Integer`

### `stringUtilsDefaultString`

```norm
String? stringUtilsDefaultString(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsIndexOf`

```norm
Integer stringUtilsIndexOf(CharSequence? arg0, Integer arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `Integer`

Returns: `Integer`

### `stringUtilsIndexOf`

```norm
Integer stringUtilsIndexOf(CharSequence? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `Integer`

### `stringUtilsIsAlpha`

```norm
Boolean stringUtilsIsAlpha(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsAlphanumeric`

```norm
Boolean stringUtilsIsAlphanumeric(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsBlank`

```norm
Boolean stringUtilsIsBlank(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsEmpty`

```norm
Boolean stringUtilsIsEmpty(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsNotBlank`

```norm
Boolean stringUtilsIsNotBlank(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsNotEmpty`

```norm
Boolean stringUtilsIsNotEmpty(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsNumeric`

```norm
Boolean stringUtilsIsNumeric(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsIsWhitespace`

```norm
Boolean stringUtilsIsWhitespace(CharSequence? arg0)
```

Parameters:

- `arg0`: `CharSequence?`

Returns: `Boolean`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(Function<Iterator<Any>?()>? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `Function<Iterator<Any>?()>?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(Function<Iterator<Any>?()>? arg0, String? arg1)
```

Parameters:

- `arg0`: `Function<Iterator<Any>?()>?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(Iterator<?>? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `Iterator<?>?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(Iterator<?>? arg0, String? arg1)
```

Parameters:

- `arg0`: `Iterator<?>?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaList<?>? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaList<?>?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaList<?>? arg0, String? arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaList<?>?`
- `arg1`: `String?`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaByteArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaByteArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaByteArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaByteArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaCharArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaCharArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaCharArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaCharArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaDoubleArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaDoubleArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaDoubleArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaDoubleArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaFloatArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaFloatArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaFloatArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaFloatArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaIntArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaIntArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaIntArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaIntArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaLongArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaLongArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaLongArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaLongArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin<T>(JavaObjectArray<T>? arg0)
```

Type parameters:

- `T`

Parameters:

- `arg0`: `JavaObjectArray<T>?`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaAnyArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaAnyArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaAnyArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaAnyArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaAnyArray? arg0, String? arg1)
```

Parameters:

- `arg0`: `JavaAnyArray?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaAnyArray? arg0, String? arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaAnyArray?`
- `arg1`: `String?`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaShortArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaShortArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaShortArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaShortArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaBooleanArray? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `JavaBooleanArray?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsJoin`

```norm
String? stringUtilsJoin(JavaBooleanArray? arg0, CodePoint arg1, Integer arg2, Integer arg3)
```

Parameters:

- `arg0`: `JavaBooleanArray?`
- `arg1`: `CodePoint`
- `arg2`: `Integer`
- `arg3`: `Integer`

Returns: `String?`

### `stringUtilsLastIndexOf`

```norm
Integer stringUtilsLastIndexOf(CharSequence? arg0, Integer arg1)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `Integer`

Returns: `Integer`

### `stringUtilsLastIndexOf`

```norm
Integer stringUtilsLastIndexOf(CharSequence? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `CharSequence?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `Integer`

### `stringUtilsLeft`

```norm
String? stringUtilsLeft(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsLeftPad`

```norm
String? stringUtilsLeftPad(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsLeftPad`

```norm
String? stringUtilsLeftPad(String? arg0, Integer arg1, CodePoint arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `CodePoint`

Returns: `String?`

### `stringUtilsLeftPad`

```norm
String? stringUtilsLeftPad(String? arg0, Integer arg1, String? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `String?`

Returns: `String?`

### `stringUtilsMid`

```norm
String? stringUtilsMid(String? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `String?`

### `stringUtilsNormalizeSpace`

```norm
String? stringUtilsNormalizeSpace(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsRemove`

```norm
String? stringUtilsRemove(String? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsRemoveStart`

```norm
String? stringUtilsRemoveStart(String? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `CodePoint`

Returns: `String?`

### `stringUtilsRepeat`

```norm
String? stringUtilsRepeat(CodePoint arg0, Integer arg1)
```

Parameters:

- `arg0`: `CodePoint`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsRepeat`

```norm
String? stringUtilsRepeat(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsRepeat`

```norm
String? stringUtilsRepeat(String? arg0, String? arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Integer`

Returns: `String?`

### `stringUtilsReverse`

```norm
String? stringUtilsReverse(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsRight`

```norm
String? stringUtilsRight(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsRightPad`

```norm
String? stringUtilsRightPad(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsRightPad`

```norm
String? stringUtilsRightPad(String? arg0, Integer arg1, CodePoint arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `CodePoint`

Returns: `String?`

### `stringUtilsRightPad`

```norm
String? stringUtilsRightPad(String? arg0, Integer arg1, String? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `String?`

Returns: `String?`

### `stringUtilsSplit`

```norm
JavaStringArray? stringUtilsSplit(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JavaStringArray?`

### `stringUtilsSplit`

```norm
JavaStringArray? stringUtilsSplit(String? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `CodePoint`

Returns: `JavaStringArray?`

### `stringUtilsSplit`

```norm
JavaStringArray? stringUtilsSplit(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `JavaStringArray?`

### `stringUtilsSplit`

```norm
JavaStringArray? stringUtilsSplit(String? arg0, String? arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Integer`

Returns: `JavaStringArray?`

### `stringUtilsSplitPreserveAllTokens`

```norm
JavaStringArray? stringUtilsSplitPreserveAllTokens(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `JavaStringArray?`

### `stringUtilsSplitPreserveAllTokens`

```norm
JavaStringArray? stringUtilsSplitPreserveAllTokens(String? arg0, CodePoint arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `CodePoint`

Returns: `JavaStringArray?`

### `stringUtilsSplitPreserveAllTokens`

```norm
JavaStringArray? stringUtilsSplitPreserveAllTokens(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `JavaStringArray?`

### `stringUtilsSplitPreserveAllTokens`

```norm
JavaStringArray? stringUtilsSplitPreserveAllTokens(String? arg0, String? arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `Integer`

Returns: `JavaStringArray?`

### `stringUtilsStrip`

```norm
String? stringUtilsStrip(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsStrip`

```norm
String? stringUtilsStrip(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsStripEnd`

```norm
String? stringUtilsStripEnd(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsStripStart`

```norm
String? stringUtilsStripStart(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsStripToEmpty`

```norm
String? stringUtilsStripToEmpty(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsStripToNull`

```norm
String? stringUtilsStripToNull(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsSubstring`

```norm
String? stringUtilsSubstring(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsSubstring`

```norm
String? stringUtilsSubstring(String? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `String?`

### `stringUtilsSubstringAfter`

```norm
String? stringUtilsSubstringAfter(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsSubstringAfter`

```norm
String? stringUtilsSubstringAfter(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsSubstringAfterLast`

```norm
String? stringUtilsSubstringAfterLast(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsSubstringAfterLast`

```norm
String? stringUtilsSubstringAfterLast(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsSubstringBefore`

```norm
String? stringUtilsSubstringBefore(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsSubstringBefore`

```norm
String? stringUtilsSubstringBefore(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsSubstringBeforeLast`

```norm
String? stringUtilsSubstringBeforeLast(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsSubstringBetween`

```norm
String? stringUtilsSubstringBetween(String? arg0, String? arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`

Returns: `String?`

### `stringUtilsSubstringBetween`

```norm
String? stringUtilsSubstringBetween(String? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `String?`

### `stringUtilsSubstringsBetween`

```norm
JavaStringArray? stringUtilsSubstringsBetween(String? arg0, String? arg1, String? arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `String?`
- `arg2`: `String?`

Returns: `JavaStringArray?`

### `stringUtilsSwapCase`

```norm
String? stringUtilsSwapCase(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsTrim`

```norm
String? stringUtilsTrim(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsTrimToEmpty`

```norm
String? stringUtilsTrimToEmpty(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsTrimToNull`

```norm
String? stringUtilsTrimToNull(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

### `stringUtilsTruncate`

```norm
String? stringUtilsTruncate(String? arg0, Integer arg1)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`

Returns: `String?`

### `stringUtilsTruncate`

```norm
String? stringUtilsTruncate(String? arg0, Integer arg1, Integer arg2)
```

Parameters:

- `arg0`: `String?`
- `arg1`: `Integer`
- `arg2`: `Integer`

Returns: `String?`

### `stringUtilsUncapitalize`

```norm
String? stringUtilsUncapitalize(String? arg0)
```

Parameters:

- `arg0`: `String?`

Returns: `String?`

