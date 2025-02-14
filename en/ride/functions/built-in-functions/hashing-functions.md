# Hashing functions

|#| Name | Description | Complexity |
|:---| :--- | :--- | :--- |
|1| [blake2b256(ByteVector): ByteVector](#blake2b256) | [blake2b256](https://en.wikipedia.org/wiki/BLAKE_%28hash_function%29) hash function | 10 |
|2| [keccak256(ByteVector): ByteVector](#keccak256)| [SHA-3-256](https://en.wikipedia.org/wiki/SHA-3) hash function | 10 |
|3| [sha256(ByteVector): ByteVector](#sha256) | [SHA-256](https://en.wikipedia.org/wiki/SHA-2) hash function | 10 |

## blake2b256(ByteVector): ByteVector<a id="blake2b256"></a>

[blake2b256](https://en.wikipedia.org/wiki/BLAKE_%28hash_function%29) hash function.

```
blake2b256(bytes: ByteVector): ByteVector
```

### Parameters

#### `bytes`: ByteVector

The array of bytes to encode.

## keccak256(ByteVector): ByteVector<a id="keccak256"></a>

[SHA-3-256](https://en.wikipedia.org/wiki/SHA-3) hash function.

```
keccak256(bytes: ByteVector): ByteVector
```

### Parameters

#### `bytes`: ByteVector

The array of bytes to encode.

## sha256(ByteVector): ByteVector<a id="sha256"></a>

[SHA-256](https://en.wikipedia.org/wiki/SHA-2) hash function.

```
sha256(bytes: ByteVector): ByteVector
```

### Parameters

#### `bytes`: ByteVector

The array of bytes to encode.
